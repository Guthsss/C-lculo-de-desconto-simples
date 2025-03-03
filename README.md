# C-lculo-de-desconto-simples
Portugol Studio

    programa {
      funcao inicio() {
    
      real desconto, valor , valorFinal

      escreva("Digite o valor da compra ")
      leia(valor)

      escreva("Digite o desconto feito ")
      leia(desconto)

      valorFinal = valor - valor*(desconto/100)
      escreva(valorFinal)
  }
}
