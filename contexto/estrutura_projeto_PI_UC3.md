# Documentação — Estrutura do Projeto

## 1. Objetivo

Este documento apresenta a estrutura atual do projeto **PI_UC3**, conforme a organização definida no Visual Studio Code.

A documentação tem como finalidade explicar a função de cada pasta e arquivo, deixando claro onde devem ficar os documentos de contexto, estilos, imagens e telas do projeto.

A estrutura deve ser mantida organizada para facilitar a manutenção, o desenvolvimento das telas e a futura expansão do sistema.

---

# 2. Estrutura geral do projeto

A organização atual do projeto é composta pelos seguintes elementos:

- **PI_UC3**
  - **contexto**
    - `contexto.md`
    - `documentacao_telas_universos.md`
  - **css**
    - `universos.css`
  - **imagens**
    - `cyberpunk.jpg`
  - **telas**
  - `README.MD`

Essa estrutura separa os diferentes tipos de arquivos de acordo com sua finalidade.

---

# 3. Pasta principal — PI_UC3

A pasta **PI_UC3** é a pasta principal do projeto.

Ela funciona como o diretório raiz, reunindo todos os arquivos e pastas utilizados no desenvolvimento.

Dentro dela ficam separados:

- documentos de contexto;
- documentação das telas;
- arquivos de estilo;
- imagens;
- telas do sistema;
- documentação geral do projeto.

A separação desses conteúdos evita que todos os arquivos fiquem misturados na raiz do projeto.

---

# 4. Pasta contexto

A pasta **contexto** é destinada aos documentos que explicam o projeto e suas regras.

Ela contém atualmente dois arquivos:

- `contexto.md`
- `documentacao_telas_universos.md`

## 4.1 contexto.md

O arquivo **contexto.md** é destinado às informações gerais do projeto.

Ele deve reunir informações que ajudem a compreender:

- objetivo do projeto;
- proposta do sistema;
- contexto de desenvolvimento;
- regras gerais;
- informações importantes para quem estiver trabalhando no projeto.

Esse arquivo funciona como uma referência geral para compreender o projeto antes de iniciar ou alterar alguma parte do desenvolvimento.

## 4.2 documentacao_telas_universos.md

O arquivo **documentacao_telas_universos.md** é responsável por documentar as telas relacionadas ao sistema de Universos.

Ele deve explicar, de forma organizada:

- estrutura das telas;
- organização dos elementos;
- relação entre Universos e Personagens;
- funcionamento visual das categorias;
- estrutura da tela inicial;
- estrutura da tela de Universos;
- estrutura da tela de Personagens;
- estrutura da tela de Batalha;
- áreas destinadas futuramente a comentários e teorias;
- organização visual apresentada nas imagens de referência.

Esse documento deve ser utilizado como guia para que o desenvolvimento das telas siga o protótipo apresentado.

---

# 5. Pasta css

A pasta **css** é destinada aos arquivos responsáveis pela aparência visual das páginas.

Atualmente existe o arquivo:

- `universos.css`

## 5.1 universos.css

O arquivo **universos.css** é responsável pelos estilos relacionados às telas do projeto de Universos.

Ele deve concentrar as definições visuais necessárias para manter o padrão apresentado nas referências.

Entre os elementos que podem ser organizados por esse arquivo estão:

- cores;
- fontes;
- tamanhos;
- espaçamentos;
- posicionamento;
- cards;
- menus;
- barras laterais;
- botões;
- campos;
- áreas de conteúdo;
- responsividade;
- aparência das categorias;
- aparência das telas de Universos e Personagens.

A intenção é evitar que as regras visuais fiquem espalhadas desnecessariamente entre diferentes arquivos.

---

# 6. Pasta imagens

A pasta **imagens** é destinada exclusivamente aos arquivos de imagem utilizados pelo projeto.

Atualmente existe:

- `cyberpunk.jpg`

## 6.1 cyberpunk.jpg

A imagem **cyberpunk.jpg** é um recurso visual utilizado pelo projeto.

Ela deve permanecer dentro da pasta **imagens**, evitando que arquivos de imagem sejam colocados diretamente na raiz do projeto.

Sempre que novas imagens forem adicionadas, elas devem ser organizadas nessa pasta.

Exemplos de conteúdos que poderão ficar nessa pasta futuramente:

- imagens de personagens;
- imagens de universos;
- banners;
- logos;
- imagens de batalhas;
- imagens de destaque;
- avatares;
- outros recursos visuais.

---

# 7. Pasta telas

A pasta **telas** é destinada às páginas que serão desenvolvidas para o sistema.

Ela deve concentrar os arquivos responsáveis pela apresentação das diferentes telas do projeto.

A organização das páginas deve seguir a divisão apresentada nas referências visuais.

Entre as telas previstas estão:

- tela inicial;
- tela de Universos;
- tela de Personagens;
- tela de Batalha.

A pasta **telas** deve ser utilizada para manter essas páginas separadas dos arquivos de documentação, estilos e imagens.

---

# 8. README.MD

O arquivo **README.MD** fica na raiz do projeto.

Ele deve funcionar como a documentação principal e mais rápida de consulta do projeto.

Seu conteúdo pode apresentar:

- nome do projeto;
- descrição resumida;
- objetivo;
- tecnologias utilizadas;
- organização das pastas;
- instruções básicas;
- informações importantes para execução;
- referências para outras documentações.

Enquanto os arquivos dentro da pasta **contexto** possuem informações mais específicas, o `README.MD` deve fornecer uma visão geral do projeto.

---

# 9. Organização por responsabilidade

A estrutura do projeto segue uma divisão por responsabilidade.

## Documentação

Local:

**contexto**

Responsabilidade:

- explicar o projeto;
- registrar decisões;
- documentar telas;
- descrever regras e funcionalidades.

## Estilos

Local:

**css**

Responsabilidade:

- controlar a aparência das páginas;
- manter o padrão visual;
- organizar cores, tamanhos e posicionamentos.

## Imagens

Local:

**imagens**

Responsabilidade:

- armazenar todos os recursos gráficos utilizados pelo projeto.

## Telas

Local:

**telas**

Responsabilidade:

- armazenar as páginas que compõem a interface do sistema.

## Documentação principal

Local:

**README.MD**

Responsabilidade:

- apresentar o projeto de forma geral;
- orientar quem estiver acessando o repositório pela primeira vez.

---

# 10. Relação entre as pastas

A estrutura pode ser entendida da seguinte forma:

**PI_UC3** é o projeto principal.

Dentro dele:

**contexto** explica o projeto.

**css** define a aparência.

**imagens** fornece os recursos visuais.

**telas** contém as páginas do sistema.

**README.MD** apresenta uma visão geral do projeto.

Essa separação facilita a localização dos arquivos e reduz a possibilidade de misturar documentação, estilos, imagens e páginas.

---

# 11. Estrutura das telas do projeto

As telas documentadas dentro do projeto possuem uma relação entre si.

## Tela inicial

É a entrada principal do sistema.

Sua função é apresentar os principais conteúdos e direcionar o usuário para outras áreas.

Entre os elementos previstos estão:

- destaque principal;
- batalha em destaque;
- área para iniciar uma batalha;
- destaque de teorias da comunidade.

## Tela de Universos

É responsável por apresentar os universos cadastrados.

Possui uma organização por categorias e cards de conteúdos.

Entre os universos podem existir diferentes tipos de conteúdo, como:

- filmes;
- televisão;
- literatura;
- cartoons;
- anime e manga;
- games;
- comics;
- web comics;
- teatro;
- super-heróis.

## Tela de Personagens

A tela de Personagens está relacionada diretamente à categoria **Universos**.

Ela não deve ser tratada como um universo independente.

A relação esperada é:

**Universo → Personagens pertencentes ao universo**

Por exemplo:

**Star Wars**

pode possuir personagens como:

- Darth Vader;
- Obi-Wan Kenobi;
- Leia;
- Yoda.

A tela deve apresentar informações sobre os personagens e permitir que eles sejam utilizados na criação de uma batalha.

## Tela de Batalha

A tela de Batalha apresenta dois personagens em confronto.

Ela deve mostrar:

- personagem do lado esquerdo;
- personagem do lado direito;
- identificação dos personagens;
- símbolo de confronto;
- área de resultado ou escolha;
- área separada para discussão da comunidade.

---

# 12. Categorias e expansão de conteúdo

As categorias apresentadas na tela de Universos devem funcionar como áreas organizadoras do conteúdo.

Ao selecionar uma categoria, a área correspondente deve aparecer no local relacionado à categoria.

A intenção é permitir que o usuário visualize os conteúdos sem precisar abandonar a organização principal da página.

As categorias previstas são:

1. Superheroes
2. Movies
3. Television
4. Literature
5. Cartoons
6. Anime e Manga
7. Gaming
8. Comics
9. Web comics
10. Theatre

A categoria **Personagens** está relacionada ao conteúdo de Universos e deve apresentar os personagens pertencentes ao universo selecionado.

---

# 13. Imagens e placeholders

Os locais destinados às imagens devem ser identificados claramente durante o desenvolvimento.

Quando uma imagem definitiva ainda não estiver disponível, deve existir uma área reservada para indicar onde ela será colocada.

Isso se aplica principalmente a:

- logos dos universos;
- imagens de personagens;
- banners;
- imagens de batalhas;
- imagens de destaque;
- avatares;
- imagens de cards.

A documentação das telas deve sempre indicar a finalidade da imagem para facilitar sua substituição posteriormente.

---

# 14. Comentários e teorias

O projeto possui elementos relacionados à comunidade, como:

- comentários;
- teorias;
- discussões;
- votos;
- destaques de teorias;
- discussões sobre batalhas.

Esses elementos fazem parte da proposta do sistema, porém sua implementação pode ser realizada em uma etapa posterior.

Nesta etapa, a documentação deve apenas indicar onde essas áreas existem e qual será sua finalidade.

A área de discussão da comunidade deve permanecer separada da área principal da batalha para facilitar futuras implementações.

---

# 15. Organização futura

Conforme o projeto crescer, novas pastas e arquivos poderão ser adicionados.

Entretanto, deve-se manter o mesmo princípio de organização:

- documentos dentro de áreas de documentação;
- estilos dentro da pasta de CSS;
- imagens dentro da pasta de imagens;
- páginas dentro da pasta de telas;
- informações gerais no README.

A estrutura deve ser atualizada sempre que novas funcionalidades forem adicionadas.

---

# 16. Resumo da estrutura atual

| Local | Finalidade |
|---|---|
| `PI_UC3` | Pasta principal do projeto |
| `contexto` | Documentações e informações de contexto |
| `contexto/contexto.md` | Informações gerais sobre o projeto |
| `contexto/documentacao_telas_universos.md` | Documentação das telas de Universos, Personagens e Batalha |
| `css` | Arquivos de estilos |
| `css/universos.css` | Estilos relacionados às telas de Universos |
| `imagens` | Armazenamento de imagens |
| `imagens/cyberpunk.jpg` | Imagem atualmente presente no projeto |
| `telas` | Páginas e telas do sistema |
| `README.MD` | Documentação geral e apresentação do projeto |

---

# 17. Regra principal de organização

A estrutura do projeto deve permanecer clara e separada por função.

A regra principal é:

**Contexto documenta.  
CSS estiliza.  
Imagens armazenam recursos visuais.  
Telas apresentam o sistema.  
README apresenta o projeto.**

Essa organização deve ser mantida durante o desenvolvimento para facilitar a manutenção, a compreensão do projeto e a colaboração entre os integrantes da equipe.
