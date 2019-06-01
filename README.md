# Trabalho final alfa
Local onde devem entregar o trabalho final de Git / Composer / Docker

## O que deve conter no trabalho
- Uma aplicação simples em HTML/CSS contendo o nome completo do aluno, um e-mail, um texto qualquer e isso estilizado com css
 - index.html
 - styles.css
- A aplicação deve ser embutida em uma imagem do Docker e disponibilizada no docker hub em um repositório público seu.
(Não se esqueça de dar um commit na sua imagem docker depois de instalar as coisas)

## O que a imagem do docker deve conter
- Apache
- PHP
- Composer
- A aplicação respondendo no apache (pasta /var/www/html)

## Como entregar o trabalho
- Pelo github
- Realizar um fork desse projeto
- Baixar um clone para a máquina
- Adicionar um arquivo texto com seu nome na pasta alunos (Ex: alunos/Joao da Silva.txt)
- O arquivo texto deve conter apenas a linha de comando para fazer o pull de seu repositório no docker hub que contém sua imagem (Ex: docker push programadorreal/aderbal:tagname). Você consegue essa linha no seu repositório.
- Depois será enviado por Pull Request para o projeto original (este).
