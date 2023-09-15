
# Interpreta��o de c�digo

Tente responder os exerc�cios dessa se��o sem executar o c�digo. Se ficar muito dif�cil, pode rodar no seu computador para analisar e pensar sobre o resultado.

---

#### 1. Indique todas as mensagens impressas no console, sem executar o programa.

```
let array
console.log('a. ', array)

array = null
console.log('b. ', array)

array = [3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13]
console.log('c. ', array.length)

let i = 0
console.log('d. ', array[i])

array[i+1] = 19
console.log('e. ', array)

const valor = array[i+6]
console.log('f. ', valor)
```

---

#### 2. Leia o c�digo abaixo com aten��o.

```
const frase = prompt("Digite uma frase")

console.log(frase.toUpperCase().replaceAll("A", "I"), frase.length)
```

Qual ser� o valor impresso no console se a entrada do usu�rio for: `"Subi num �nibus em Marrocos"`?
