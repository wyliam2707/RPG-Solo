# Livro da Campanha

A pasta `livro/` guarda a história jogada e o ponto exato de continuidade.

## Estrutura

- `estado-atual.md` — **somente o presente**: cena atual, condições ativas e ponto de retomada.
- `indice.md` — mapa dos capítulos, títulos e tags para localizar fatos antigos.
- `capitulo-01.md`, `capitulo-02.md`, etc. — registro histórico completo da aventura.

## Regra principal para campanha longa

Não transformar `estado-atual.md` em um resumo cumulativo infinito.

Quando um capítulo termina:

1. salvar a prosa completa no novo `capitulo-XX.md`;
2. registrar no fim do capítulo um `Resumo de continuidade` com os fatos daquele capítulo;
3. **substituir** `estado-atual.md` pelo novo estado presente;
4. atualizar `indice.md` com título e tags do novo capítulo;
5. mover regras permanentes para os arquivos de referência apropriados;
6. mover mistérios ainda ativos para `referencia/fios-abertos.md`;
7. atualizar NPCs/itens em `referencia/npcs-recursos.md` quando necessário.

## Como retomar depois de uma pausa

Ler nesta ordem:

1. `livro/estado-atual.md`;
2. `referencia/guia-operacional.md`;
3. `referencia/fios-abertos.md`;
4. `referencia/npcs-recursos.md`;
5. último capítulo concluído apenas se a cena exigir detalhes;
6. arquivos profundos (`personagem.md`, `dinamica-trio.md`, `poderes.md`, `cenario.md`, `estilo-narrativo.md`) somente conforme o assunto.

## Capítulos são históricos

Capítulos concluídos não devem ser reescritos apenas porque os personagens aprenderam algo depois.

Se um capítulo registra uma interpretação antiga que foi corrigida posteriormente, preservar o capítulo e registrar a correção nos documentos atuais. Isso mantém a evolução real da campanha.

## Proteção contra spoilers

Arquivos acessíveis de continuidade registram apenas fatos já ocorridos ou conhecidos pelo personagem.

Não gravar soluções futuras, motivações ocultas ainda não reveladas ou segredos de preparação do narrador como se já fossem canon conhecido.

## Ritmo de fechamento

Um capítulo pode encerrar em:

- mudança natural de objetivo;
- mudança de local relevante;
- revelação importante;
- confronto encerrado;
- passagem de tempo significativa;
- conclusão de pequeno arco;
- gancho forte para nova aventura.

O tamanho é secundário; o corte deve servir à história.
