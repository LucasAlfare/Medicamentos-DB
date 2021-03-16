# Medicamentos-DB
Repositório para guardar/reunir diversas informações sobre os principais medicamentos em uso no Brasil.

# Fontes
As fontes podem ser as mais variadas. Por enquanto, nas versões iniciais, estarão sendo reunidas as informações contidas no documento https://files.cercomp.ufg.br/weby/up/734/o/Guia_de_Interacoes_Medicamentosas.pdf?140905.

# Contribuindo
As contribuições são bem vindas desde que acompanhem as devidas referências bibliográficas.

Todas as contribuições devem ser submetidas em formato de dados CSV (entenda o formato CSV: https://pt.wikipedia.org/wiki/Comma-separated_values).

Por enquanto está sendo suportada apenas as colunas na seguinte ordem:

```
Medicamento | Interage com | Efeito Clínico | Grau da Interação | Início da Ação | Recomendação
```

Para manter o formato do arquivo estável, as contribuições devem ter em mente os seguintes pontos:

- Faça um fork deste repositório para sua conta e enviei commits ao seu fork;
- Novos formatos ainda estão sendo discutidos portanto apenas contribuições com formato CSV serão implementadas (mediante a avaliação prévia);
- Caso uma das informações que estiverem para ser adicionadas não tenha nenhuma informação relevante, sugere-se por escrever a abreviatura `--`;
- Se for necessário adicionar uma nova coluna, como por exemplo, para uma nova informação sobre uma substância, por favor, envie a contribuição para uma ramificação à parte (_branch_) para que possa, assim, ser posteriormente implementada.

# Licença
Este repositório é totalmente livre e aberto, os dados aqui são livres para qualquer usuário os utilizar, desde que o mesmo adicione as devidas referências bibliográficas para tais informações.
