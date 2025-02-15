- [1. Introdução](#1-introdução)
- [2. Casos de Uso](#2-casos-de-uso)

# 1. Introdução

- Nesse exemplo, é demonstrado o uso da injeção de Dependência na _POO_, e seus problemas de **DESIGN**.

# 2. Casos de Uso

- Nesse exemplo foi utilizada a Injeção de Dependência de forma a evitar que o objeto crie sua função como ocorre na Composição, ou seja, o animal já nasce sabendo o que tem que fazer.
  - Essas informações ficam na `Main` que basicamente funciona como uma Central de Controle.
  - Dessa forma caso seja necessária alteração em alguma comportamento basta realizá-la em sua respectiva classe(Andar, Voar, Respirar, etc).