-animações CSS
  @keyframes
   animation-name
   animation-duration
   animation-delay
   animation-iteration-count
   animation-direction
   animation-timing-function
   animation-fill-mode
   animation

Propriedade abreviada de animação
O exemplo abaixo usa seis das propriedades de animação:

div {
  animation-name: example;
  animation-duration: 5s;
  animation-timing-function: linear;
  animation-delay: 2s;
  animation-iteration-count: infinite;
  animation-direction: alternate;
}

O mesmo efeito de animação acima pode ser obtido usando a animationpropriedade abreviada:

div {
  animation: example 5s linear 2s infinite alternate;
}

rotate

 transform: translate();