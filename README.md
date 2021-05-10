
# Desafio Front-end - Olist Pax (📺 maratonator)

## Objetivo e proposta

O objetivo desse desafio é avaliar os conhecimentos técnicos dos candidatos às vagas de Desenvolvedor Front End no Olist Pax.

Deverá ser criada uma aplicação onde você calcula o quanto de tempo é necessário para maratonar a sua série favorita. Além disso você também deve ver um resumo da série e seus personagens principais.

## Instruções e descrição das funcionalidades

Crie uma aplicação utilizando o seguinte layout: https://www.figma.com/file/LhWyHZ1vSfPPPxwmoIyMM5/Teste-Front-End-Maratonator?node-id=0%3A1:

- **Header**:
Localizado no topo da página, contendo o logo do lado esquerdo (📺 maratonator), e a navegação para as páginas (início e sobre) do lado direito

- **Início**:
    - Ao entrar na página, deverá ser exibida uma sessão no meio do navegador com uma frase/busca/pergunta configurável:
    > Consigo maratonar **Game of Thrones¹** em **1³** **semana²**?
    1. **Busca de séries:** Na frase, deverá ter um input de busca de séries com o placeholder *Game of Thrones*. Ao clicar nesse input, o mesmo deverá crescer até um determinado tamanho para melhor usabilidade. Ao digitar, será realizado uma consulta em uma API e os resultado serão listados em um box abaixo desse input com alguns itens. Cada item deverá conter o poster, nome e ano da série.
    2. **Seletor de período de tempo**: Na frase, ao clicar na palavra de período de tempo (dia, semana, mês ou ano) deverá alterar ciclicamente esse período.
    3. **Seletor de multiplicador do período de tempo**: No fim da frase, deverá conter duas setas para aumentar ou diminuir o multiplicador de período. Caso o multiplicador seja maior que 1, a frase deverá contemplar os nomes de período de tempo no plural (dias, semanas, meses ou anos).
	- Ao selecionar uma série nos resultados da busca, deverão ser exibidos:
		- Abaixo da pergunta, uma frase com o cálculo de acordo com o *seletor de período de tempo* e o *seletor de multiplicador do período de tempo*:
		> Sim, se você assistir 10 episódios por dia.
		- No box principal da pergunta, o fundo deverá ter o tom de cor de acordo com o poster da série e uma imagem da série.
		- Ao lado da pergunta, deverá ter um poster da série e o nome dá série flutuando atrás.
		- Abaixo do box principal, deverá ter o nome, ano, categorias, sinopse e personagens principais em formato de cards com o seu respectivo nome.
		
- **Sobre**:
Texto simples com o conteúdo do layout. Sugerimos copiar esse README e inserir nessa tela com as formatações. 

### Vídeos demonstrativos das funcionalidades:
**Desktop**: https://www.loom.com/share/9280f618307d451bb4c1b79f589d41d2
**Mobile**: https://www.loom.com/share/f9a2954c695d4ed68c39d19e3ca0ec76

## Requisitos técnicos
- Criação de um repositório GIT com o código da sua aplicação.
- A aplicação deve ser construída em Vue utilizando a Vue CLI:
    - VueX para controle do estado da aplicação.
    - Vue Router para controle das rotas.
    - SCSS para estilização dos componentes.
- Utilização da API do [TMDB (The Movie Database)](https://developers.themoviedb.org/3/getting-started/introduction).
- A aplicação precisa ser responsiva.
- Deverá ser desenvolvido um README explicando o passo-a-passo para executar o projeto e/ou algo mais que você achar necessário.

## O que iremos avaliar:
- Assertividade no funcionamento das funcionalidades (caso algo fique faltando, documente no README).
- Atenção aos detalhes do layout (tamanhos, espaçamentos, fontes e cores).
- Código limpo, bem organizado, componentizado, legível e estruturado.
- Performance da aplicação.
- Histórico, qualidade e estrutura dos commits.

## Ganham mais pontos na avaliação:
- Animações, desde que sejam performáticas.
- Atomic Design e/ou BEM na estruturação dos componentes.
- Implementação de funcionalidades além das requisitadas nas instruções e no layout.
- Implementação de testes unitários utilizando o Jest ou testes e2e utilizando o Cypress.
- Disponibilizar uma URL pública com a aplicação.

## Finalizou? Como envio o teste?

Envie um e-mail para gabriel.caputo@olistpax.com com cópia para gabriel.gelado@olistpax.com com o título:

> SEU NOME - Desafio Front-end - Olist Pax

No corpo do e-mail envie o link do repositório com o teste e/ou algo mais que você achar necessário.

Boa sorte!
