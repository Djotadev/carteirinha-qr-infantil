# Carteirinha QR infantil 🦖

Um cartão com QR code que explica, em segundos, como ajudar uma criança com uma condição que ninguém vê (como TDAH ou autismo).

**Demo (dados fictícios):** https://djotadev.github.io/carteirinha-qr-infantil/

<!-- Cole aqui o link do vídeo e, se tiver, um GIF: ![demo](docs/demo.gif) -->

## O problema

Condições como TDAH e autismo não aparecem à primeira vista. Por isso a família acaba repetindo a mesma explicação na escola, no mercado, em todo lugar.

## A solução

Quem escaneia o QR code abre uma página com:

- quem é a criança e uma frase sobre como ela é;
- um botão grande para **ligar para o responsável**;
- dicas simples de como ajudar.

## Como funciona

- Cada página é montada a partir de **um objeto de dados** (nome, responsáveis, dicas, tema). O resto do código não muda.
- Cinco temas visuais: dinossauro, espaço, fundo do mar, unicórnio e princesas.
- **Sem servidor:** é HTML, CSS e JavaScript puro. Os dados ficam no arquivo da própria página.

## Decisões

- **Ação principal primeiro:** o botão de ligar vem antes de qualquer texto, porque quem escaneia está numa situação de ajuda.
- **Privacidade desde o começo:** nenhum dado vai para servidor, e o laudo médico vem **desligado por padrão**.
- **Textos inseridos como texto, não como HTML**, para evitar injeção de código.
- **Uso no celular:** botões grandes, fonte arredondada e foco visível para navegação por teclado.

## Tecnologias

HTML, CSS (variáveis para os temas), JavaScript e hospedagem estática.

## Limitações

- É um cartão **informativo**: não substitui documentos oficiais nem garante atendimento prioritário.
- A demo usa só dados fictícios.

## Sobre o desenvolvimento

Usei o Claude como ferramenta de apoio durante o desenvolvimento.

## Autor

Matheus (Djotadev) · designer gráfico migrando para front-end, em busca da primeira vaga como dev júnior.
LinkedIn: https://www.linkedin.com/in/matheus-reis-9abb15258/

## Licença

Todos os direitos reservados. O código está público para consulta e avaliação. Veja o arquivo [LICENSE](LICENSE).
