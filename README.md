# Identificador Whatsapp Web — distribuição

Repositório público de distribuição do aplicativo desenvolvido pela
[Noctu.com.br](https://noctu.com.br).

Este repositório contém somente:

- manifesto da versão mais recente;
- catálogo de hashes de licenças;
- executáveis publicados em GitHub Releases.

O código-fonte e os seriais não são armazenados aqui. O arquivo `licenses.json`
contém apenas hashes SHA-256, plano, validade e situação de cada licença.

## Administração

As licenças são criadas e revogadas pelas ferramentas mantidas no repositório
privado do aplicativo. Depois de alterar `licenses.json`, registre e envie a
mudança para a branch `main`.

Os executáveis são publicados como assets de Releases com tags semânticas,
por exemplo `v1.4.0`. O `version.json` aponta para o release atual e registra o
SHA-256 que o aplicativo confere antes de instalar.
