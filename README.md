# VERIFICADOR DE IDADE
👨‍🏫PROJETO FEITO PARA O CURSO DE HTML E CSS DO CURSO EM VIDEO.

[![GitHub Repo stars](https://img.shields.io/badge/VILHALVA-GITHUB-03A9F4?logo=github)](https://github.com/VILHALVA)
[![GitHub Repo stars](https://img.shields.io/badge/MEUS-CURSOS-03A9F4?logo=github)](https://github.com/VILHALVA?tab=repositories&q=CURSO&type=public&language=&sort=) <br>

<img src="https://pt.seaicons.com/wp-content/uploads/2015/10/Age-Child-Male-Light-icon.png" align="center" width="280"> <br>

## DESCRIÇÃO:
Esse é um código HTML que cria uma página simples para verificar a idade com base no ano de nascimento e sexo. Ele utiliza JavaScript para realizar a verificação e apresentar uma imagem correspondente à faixa etária e ao gênero.

Aqui estão as principais partes do código:

### HTML (`CODIGO.html`):
1. **Meta Tags e Título:**
   - Define o conjunto de caracteres, a compatibilidade com o Internet Explorer e a escala de visualização.
   - O título da página é "IDADE".

2. **Vinculação de Estilos e Scripts:**
   - Vincula um arquivo de script JavaScript (`CODIGO.js`) e um arquivo de estilo CSS (`CODIGO.css`).

3. **Corpo do Documento (`<body>`):**
   - Contém um cabeçalho (`<header>`), uma seção (`<section>`) com campos para inserção de dados (ano de nascimento, sexo) e um rodapé (`<footer>`).

### CSS (`CODIGO.css`):
1. **Estilos:**
   - Define estilos para o corpo da página, cabeçalho, seção, div, imagem e rodapé.
   - Usa cores, fontes e sombras para estilizar a página.

### JavaScript (`CODIGO.js`):
1. **Função `verificar()`:**
   - Obtém o ano atual.
   - Obtém o ano de nascimento e verifica se é válido.
   - Determina o gênero selecionado.
   - Calcula a idade.
   - Com base na idade e gênero, seleciona uma imagem correspondente.
   - Exibe a idade, gênero e imagem no elemento com o ID 'res'.

### Observações Adicionais:
   - O script JavaScript usa a função `createElement` para criar uma imagem dinamicamente e atribui propriedades a ela.
   - A página tem uma estrutura básica, com um cabeçalho informativo, campos para entrada de dados e uma área para exibição dos resultados.
   - O design é estilizado usando o arquivo CSS fornecido.
   - Imagens específicas estão vinculadas no script com base no gênero e na faixa etária.

Essencialmente, a página verifica a idade com base no ano de nascimento e exibe uma imagem correspondente ao gênero e à faixa etária.