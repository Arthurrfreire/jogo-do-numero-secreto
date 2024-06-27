# Jogo do Número Secreto

Este é um simples jogo de adivinhação de números onde o jogador deve adivinhar um número secreto gerado aleatoriamente entre 1 e 10. O jogo dá dicas se o número secreto é maior ou menor que o chute do jogador e fornece feedback em voz.

Esse projeto foi desenvolvido para o curso de Lógica de programação da Alura junto com a Oracle

## Estrutura do Projeto

O projeto é composto pelos seguintes arquivos:

- `index.html`: Contém a estrutura HTML do jogo.
- `style.css`: Contém os estilos CSS para o layout e design do jogo.
- `app.js`: Contém o código JavaScript responsável pela lógica do jogo.
- `img/`: Contém as imagens usadas no projeto.

## Funcionalidades

- **Gerar Número Aleatório**: Gera um número secreto aleatório entre 1 e 10.
- **Verificar Chute**: Compara o chute do jogador com o número secreto e fornece feedback.
- **Feedback em Voz**: Utiliza a biblioteca `responsiveVoice` para dar feedback em voz.
- **Reiniciar Jogo**: Permite ao jogador reiniciar o jogo após descobrir o número secreto.

## Como Usar

1. Clone este repositório ou baixe os arquivos.
2. Abra o arquivo `index.html` em um navegador.
3. Digite um número entre 1 e 10 no campo de entrada.
4. Clique no botão "Chutar" para verificar se o seu chute está correto.
5. Receba feedback visual e auditivo sobre o seu chute.
6. Clique no botão "Novo jogo" para reiniciar o jogo.

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript
- [responsiveVoice](https://responsivevoice.org/)

## Estrutura do Código

### `index.html`

Contém a estrutura básica do HTML e inclui o script `responsiveVoice` e o arquivo `app.js`.

## `style.css`
Contém os estilos para o layout e design do jogo, garantindo uma experiência visual agradável.

## `app.js`
Contém a lógica do jogo, incluindo a geração de números aleatórios, verificação do chute e reinicialização do jogo.

## Como Contribuir

* Fork este repositório.

* Crie uma branch: git checkout -b minha-nova-funcionalidade.

* Faça suas alterações e commit: git commit -m 'Adicionar nova funcionalidade'.

* Faça push para a branch: git push origin minha-nova-funcionalidade.

* Abra um pull request.

## Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

