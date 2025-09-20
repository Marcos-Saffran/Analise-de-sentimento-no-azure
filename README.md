# Introdução aos Serviços de IA (Azure) — Guias de Exploração

Este repositório contém dois guias práticos para explorar os serviços de Inteligência Artificial do Azure usando as ferramentas online do Language Studio e do Speech Studio. Os documentos fornecem passos claros, capturas de tela e instruções para testar recursos importantes como análise de sentimento, extração de opiniões e conversão de texto em fala.

- **Arquivo:** [Languague_studio.md](./Languague_studio.md) — Guia para explorar o Azure AI Language (Language Studio).
- **Arquivo:** [Speech_studio.md](./Speech_studio.md) — Guia para explorar o Azure AI Speech (Speech Studio).

## Objetivo

Fornecer instruções rápidas e reproduzíveis para que um usuário consiga: 1) testar a análise de sentimento e mineração de opiniões no Language Studio; 2) experimentar a conversão de texto em fala no Speech Studio.

## Pré-requisitos

- Navegador web moderno (`Edge`, `Chrome`, `Firefox` ou `Safari`).
- Conexão com a Internet.
- Conta Microsoft/Azure (opcional para alguns recursos; os guias usam as ferramentas públicas disponíveis nas páginas do Language Studio e Speech Studio).

Estrutura do repositório

- `Languague_studio.md` — Passo a passo para usar o recurso "Analyze sentiment and mine opinions" no Language Studio. Inclui imagens em `imagens/language_service/`.
- `Speech_studio.md` — Passo a passo para experimentar a conversão de texto em fala. Inclui imagens em `imagens/speech_studio/`.
- `imagens/` — Contém capturas de tela que ilustram os passos em cada guia.

Como usar estes guias

1. Abra este repositório localmente no seu editor de preferência (por exemplo, VS Code).
2. Leia o arquivo correspondente ao serviço que deseja testar:
   - Para testar análise de sentimento e extração de opiniões, abra `Languague_studio.md`.
   - Para testar texto → fala, abra `Speech_studio.md`.
3. Siga os passos descritos em cada arquivo. As imagens referenciadas são locais e podem ser visualizadas diretamente no editor ou em um visualizador de imagens.

Links úteis

- Language Studio: [https://language.cognitive.azure.com/](https://language.cognitive.azure.com/)
- Speech Studio: [https://speech.microsoft.com/portal](https://speech.microsoft.com/portal)

## Observações e dicas

- As telas dos serviços podem mudar com o tempo. Caso um item do passo a passo não esteja exatamente no mesmo local, procure por palavras-chave mencionadas no guia (por exemplo, `Classify text`, `Analyze sentiment`, `Voice Gallery`).
- Se quiser executar testes com uma conta Azure para coletar resultados programaticamente, utilize os SDKs oficiais do Azure AI (documentação no portal do Azure) e crie recursos no portal do Azure com as chaves e endpoints apropriados.

### Imagens e ativos

As imagens usadas nos guias estão na pasta `imagens/` e organizadas por serviço:

- `imagens/language_service/` — capturas de tela e ilustrações para `Languague_studio.md`.
- `imagens/speech_studio/` — capturas de tela e ilustrações para `Speech_studio.md`.

Você pode abrir as imagens diretamente no VS Code ou em qualquer visualizador de imagens para acompanhar os passos descritos nos arquivos Markdown.

Contribuições

Se quiser melhorar os guias (ex.: adicionar mais exemplos, atualizar imagens, incluir comandos de SDK), abra um pull request ou envie sugestões diretamente nos arquivos `.md`.

Contato

Para dúvidas ou ajuda adicional, adicione uma issue neste repositório com a descrição do problema e passos para reproduzir.
