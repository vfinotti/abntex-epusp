# Repositório contendo o template ABNTex com o arquivo de estilo EPUSP

## Porque usar este modelo?
O intuito de usar os o arquivo .sty em conjunto com os .tex da ABNTex é
justamente facilitar a edição e elaboração de documentos em LaTeX no padrão
ABNT. Por serem mantido pelo próprio grupo ABNTex, tais modelos sempre estarão
atualizados, evitando que problemas com pacotes que ficam obsoletos ocorram.

1. Escolher um modelo canônico de documento disponível em
   https://github.com/abntex/abntex2/tree/master/doc/latex/abntex2/examples
1. Caso queira, escolher uma folha de estilo de uma instituição
   disponível em https://github.com/abntex/abntex2/wiki/CustomizacoesConhecidas
1. Colocar o arquivo de estilo .sty na mesma pasta que o modelo canônico e
   chamar ele através do comando
   ```TeX
   \usepackage{capa-epusp-abntex2}
   ```
1. Usar o seu editor favorito para editar o documento =))

## Como usar o modelo de projeto de pesquisa deste respositório?
Neste repositório tem os arquivos necessários para já começar a criar um projeto
de pesquisa segundo o exigido na Escola Politécnica da USP. Segue uma relação dos arquivos e o que eles são:

- **.gitignore**, **LICENSE** e **README.md**: Arquivos do git. Não se preocupar com eles.
- **abntex2-modelo-img-grafico.pdf**: Imagem de um gráfico usado no documento
- **abntex2-modelo-img-marca.pdf**: Imagem usada no documento
- **abntex2-modelo-include-comandos.tex**: Arquivos com vários exemplos de
  textos e que são chamados pelo arquivo principal. Retire o comando
  *\include{abntex2-modelo-include-comandos}* do arquivo principal para poder
  deletar este arquivo
- **abntex2-modelo-projeto-pesquisa.pdf**: Arquivo principal compilado
- **abntex2-modelo-projeto-pesquisa.tex**: Arquivo principal. É nele que vc deve
  basear seu documento.
- **abntex2-modelo-references.bib**: Referências bibliográficas usadas pelo
  arquivo principal
- **capa-epusp-abntex2.sty**: Arquivo de estilos da EPUSP

Mais informações em https://github.com/abntex/abntex2
