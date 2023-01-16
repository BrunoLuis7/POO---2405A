# POO---2405A/**
 * You can edit, run, and share this code.
 * play.kotlinlang.org
 */
fun main() {
     / var num1 = 70 
/ var num1 = 69
/*
if(numero > 0){
    println("o numero é maior que zero")
    
}else if(numero < 0)
   println("o numero é menor que zero"){
       
   }else{
       println("o numero é igual a zero")
   }

  */ 
// repeat - repita 
// 
// estrutura do repeat
// 
// repeat(vezes que vai ser repetido){
// ações
// }
/*
repeat(10){
    println("por ordem dos peaky blinders")
   
}*/
// laço do.. while -> faça enquanto 
// 
// executa a ação enquanto for verdadeira
// 
// estrutura do.. while
// 
//  do{
//  ação
//  }while(condição)}
//  
/*
// laço for - para 
// estrutura do for
// 
// for(i in intervalo/conllection)
// {
// ações
// }
 */
 for(alunos in 1..20){
     println("feliz carnaval!!")
 }
// fça uma tabuada de um numero(que não seja a do 1 e do 10)
// até o décimo multiplo usando, o laço for
for(i in t..10){
    println(i*8)
}
// POO - programação Orienta a Objetios - simular coisas da realidade na programação 
// 
//a POO é dividida:
//
//Classes- são modelos que servem para a construção de objs derivados del mesmo(Wx classe pessoa)
//
//Métodos - sera as intancias da classe, as formas de agir 
//estrutura de uma classe 
//class Nome(){ocorridos e um obj}
/*
val ricardo = Pessoa() // instanciando um obj
ricardo.nome = "Ricardo franco oliveira"
ricardo altura = 2.15
ricardo.corDosolhos = "verde"
ricardo.peso =100.0
println(ricardo.altura) //para exibir um atributo em especifico)
*/
val convidado1= pessoa("claudio", 1.79, "castanhos",183.0)
println($convidado1.peso)
val convidado2 = pessoa("juliana", 1.5, "azul", 53.5)
}// exercio: criem um churras e exiba a lista de convidados no console, no min 6 pessoas
val convidado1= pessoa("messi", 1.79, "castanho",70.0)
val convidado2= pessoa("tobwy miguare", 1.5, "castanho",70.0)
val convidado3= pessoa("franco", 1.80, "castanho escuro",70.0)
val convidado4= pessoa("vini jr", 1.76, "castanho escuro",73.0)
val convidado5= pessoa("eu", 1.80, "castanho",80.0)
val convidado6= pessoa("pelé", 1.5, "fechados",-3.0)



class Pessoa(val nome: String,
            val altura: Double,
            val corDosOlhos: String,
            val peso: Double){
    //declarando atributos para a classe
    /*
    val nome = ""
    val altura = 0.0
    val cor de olhos = ""
    val peso = 0
    */
     
}
