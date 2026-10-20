# O que pesquiso quando busco na HDB?

Apresentação em Quarto/RevealJS para o grupo de pesquisa **Imprensa e História**, realizada em 20 de outubro de 2026.

## Apresentação

A versão publicada está disponível em:

[ericbrasil.com.br/imp-hist](https://ericbrasil.com.br/imp-hist/)

O repositório contém a fonte editável e o HTML renderizado da apresentação.

## Conteúdo

A apresentação discute:

- a Hemeroteca Digital Brasileira como infraestrutura de pesquisa;
- interfaces, OCR, metadados e acesso programático;
- problemas metodológicos e epistemológicos da pesquisa digital;
- inteligência artificial e agentes de IA;
- diferenças entre interface, API, modelo e agente;
- rastreabilidade, crítica da fonte e responsabilidade humana;
- experiências e projetos relacionados ao LABHDUFBA.

A estrutura visual inicial segue a apresentação [`slacsc`](https://github.com/ericbrasiln/slacsc).

## Produção com agente de IA

A apresentação foi produzida com o **Hermes Agent**, utilizando um modelo de linguagem e *skills* voltadas para pesquisa acadêmica, História Digital, produção de apresentações e gestão de repositórios.

O agente foi utilizado para:

- organizar e revisar o roteiro;
- redigir e editar o conteúdo dos slides;
- estruturar o arquivo Quarto;
- produzir o HTML com RevealJS;
- gerar e incorporar o QR code;
- incorporar e verificar imagens e GIFs;
- executar verificações de renderização, ordem dos slides e carregamento dos arquivos;
- atualizar o repositório local e o repositório remoto.

A produção ocorreu sob supervisão, orientação e revisão de **Eric Brasil**, que mantém a responsabilidade intelectual pelo argumento, pelas decisões de conteúdo, pela seleção das fontes e pelo uso público da apresentação.

O uso do agente não substitui a autoria intelectual nem a revisão histórica. O agente executa operações de pesquisa e produção, mas não possui autonomia epistemológica para validar sozinho interpretações, fontes ou conclusões.

## Renderização local

Requisitos:

- [Quarto](https://quarto.org/);
- navegador compatível com HTML5.

Renderize com:

```bash
quarto render index.qmd
```

O resultado principal será `index.html`.

## Estrutura do repositório

- `index.qmd`: fonte da apresentação e notas do apresentador.
- `index.html`: apresentação HTML renderizada.
- `styles.css`: identidade visual.
- `index_files/`: bibliotecas e arquivos gerados pelo Quarto.
- `imgs/`: imagens, GIFs e QR code usados nos slides.
- `LICENSE.md`: licença Creative Commons do repositório.
- `CITATION.cff`: metadados para citação do projeto.

## Citação

Use o arquivo [`CITATION.cff`](CITATION.cff) ou cite o repositório da seguinte forma:

> BRASIL, Eric. *O que pesquiso quando busco na HDB?* Apresentação em Quarto/RevealJS. 2026. Disponível em: <https://ericbrasil.com.br/imp-hist/>. Código-fonte: <https://github.com/ericbrasiln/imp-hist>.

## Licença

O conteúdo deste repositório está licenciado sob a licença [Creative Commons Atribuição-NãoComercial-CompartilhaIgual 4.0 Internacional](LICENSE.md).
