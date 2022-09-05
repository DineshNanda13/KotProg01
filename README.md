# KotProg01
import java.util.Scanner

fun main(args: Array<String>) {
//1. Print an Integer (Entered by the User)

    /*
    val reader = Scanner(System.`in`)
    println("Enter a number: ")

    var num : Int = reader.nextInt()
    println("You've entered: $num")
    */

//2. Kotlin Program to Add Two Integers
    /*val num1 = 2
    val num2 = 3
    println("The sume is: ${num1+num2}")*/

//3. Kotlin Program to Swap Two Numbers
    /*var a = 3
    var b = 4
    var c = a
    a = b
    b = c
    println(a)
    println(b)*/

//4. Check Whether an Alphabet is Vowel or Consonant
    /*val ch = 'i'

    val vowelConsonant =
        if (ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u')
            "vowel"
        else
            "consonant"

    println("$ch is $vowelConsonant")*/

//5. Kotlin Program to Find the Largest Among Three Numbers
    val n1 = -4.5
    val n2 = 3.9
    val n3 = 2.5

    if (n1 >= n2 && n1 >= n3)
        println("n1 = $n1 is the largest number.")
    else if (n2 >= n1 && n2 >= n3)
        println("n2 = $n2 is the largest number.")
    else
        println("n3 = $n3 is the largest number.")
}
