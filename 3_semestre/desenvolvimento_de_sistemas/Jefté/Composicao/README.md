- [1. Introdução](#1-introdução)
- [2. Casos de Uso](#2-casos-de-uso)

# 1. Introdução

- Nesse exemplo, é demonstrado o uso da Composição na _POO_, e seus problemas de **DESIGN**.

# 2. Casos de Uso

- Nesse exemplo foi usada a Composição para separar os métodos, andar(), respirar(), falar(), nadar() e voar() em diferentes classes.
  - Dessa forma a classe `Peixe` adiquire apenas os comportamentos que lhe são necessários.
  - Porém para fazer caso fossem necessárias alterações estas deveriam ser feitas em todas as classes, já que os metódos estão instanciados nas classes de cada animal(Cachorro, Passaro, Peixe, etc).