import kotlin.math.pow

const val OPCAO = 3
fun main() {
    print("O número 1 é: ")
    var numero1:Float? = 10F
    println(numero1)
    print("O número 2 é: ")
    var numero2:Float? = 2.5F
    println(numero2)
    print("A sua escolha de operação foi: ")
    println(OPCAO)
    
    if(numero1?.equals(null) == null){
       print("Verificamos que o numero1 = null. Tente trocar o valor!")
       
    }else if(numero2?.equals(null) == null){
       print("Verificamos que o numero2 = null. Tente trocar o valor!")
    }else{
    when (OPCAO){
        1 -> print("A adição de $numero1 + $numero2 é: " + numero1.plus(numero2))
        2 -> print("A subtração de $numero1 - $numero2 é: " + numero1.minus(numero2))
        3 -> print("A divisão de $numero1/$numero2 é: " + numero1.div(numero2))
        4 -> print("A multiplicação de $numero1 * $numero2 é: " + numero1.times(numero2))
        5 -> print("A potência de $numero1 ^ $numero2 é: " + numero1.pow((numero2)))
        6 -> print("A conta de ($numero1/$numero2)*100 é: " + numero1.div(numero2).times(100))
        else -> print("Ops. Verificamos que foi atribuído o valor null. Tente novamente!")
    }
  }  
}
