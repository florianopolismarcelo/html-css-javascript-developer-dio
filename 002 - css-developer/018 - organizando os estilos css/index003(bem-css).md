[B] bloco
[E] elemento
[M] Modificador

*BEM faz alusão a programação orientada a Objetos (POO), uma maneira de descrever a relidade no código, com uma variedade de padrões e uma maneira de pensar nas entidades do programa.*

> - Varga Stepanova, desenvolvedora front-end do projeto.

- Bloco (Block):
  - Entidade independente (bloco de construção)
  - Elemento pai
  - [BLOCO] (.btn)

- Elemento (Elements)
  - Elemento filho
  - Não independente
  - vinculado a um bloco
  - [BLOCO]__[ELEMENTO] (.btn__price)

- Modificador (Modifier)
  - Modifica um bloco ou elemento
  - Variante para alterar a aparência
    - Variar uma propriedade 
    - Atribuir um estado
  - [BLOCO]__[ELEMENTO]--[MODIFICADOR]
    .menu--dark
    .btn--orange
    .menu__link--disabled

