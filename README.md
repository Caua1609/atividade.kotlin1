# atividade.kotlin1

### Atividade 1
```kotlin
fun main() {
    var celsius = 25
    var fahrenheit = celsius * 9/5 + 32
    println(fahrenheit)
}
```

### Atividade 2
```kotlin
fun main() {
    var fahrenheit = 77
    var celsius = (fahrenheit - 32) * 5/9
    println(celsius)
}
```

### Atividade 3
```kotlin
fun main() {
    var raio = 5
    var altura = 10
    var volume = 3.14 * raio * raio * altura
    println(volume)
}
```

### Atividade 4
```kotlin
fun main() {
    var distancia = 240 
    var consumo = 12 
    var litro_combustivel = distancia / consumo
    println(litro_combustivel)
}
```

### Atividade 5
```kotlin
fun main() {
    var valor_original = 1000 
    var meses_atraso = 3
    var taxa_juros = 1
    var valor = valor_original * (1 + (taxa_juros / 100) * meses_atraso)
    println(valor)
}
```

### Atividade 6 
```kotlin
fun main() {
    var base = 2
    var expoente = 3
    var resultado = base * base * base 
    
    println(resultado)
}
```

### Atividade 7
```kotlin
fun main() {
    var medida_pes = 20 
    var metros = medida_pes * 0.3048
    println(metros)
}
```

### Atividade 8
```kotlin
fun main() {
    var numero_inteiro = 5
    var sucessor = 6 
    var antecessor = 4
    var resultado = "Antecessor: 4, Sucessor: 6"
    println(resultado)
}

```

### Atividade 9
```kotlin
fun main() {
    var numero_inteiro1 = 10
    var numero_inteiro2 = 5 
    var diferença = numero_inteiro1 - numero_inteiro2
    println(diferença)
}

```

### Atividade 10
```kotlin
fun main() {
    var valor1 = 10 
    var valor2 = 5 

    var multiplicacao = valor1 * valor2
    var divisao = valor1 / valor2
    var soma = valor1 + valor2
    var subtracao = valor1 - valor2

    var resultado = 
        "Multiplicação: $multiplicacao\n" +
        "Divisão: $divisao\n" +
        "Soma: $soma\n" +
        "Subtração: $subtracao"

    println(resultado)
}

```

### Atividade 11
```kotlin
fun main() {
    var valor_dolar = 50
    val cotaçao_dolar = 5.60
    var converçao_real = valor_dolar * cotaçao_dolar

    println(converçao_real)
}

```

### Atividade 12 
```kotlin
fun main() {
    var raio = 5 
    var area = 3.14 * raio * raio
    println(area)
}
```

### Atividade 13
```kotlin
fun main() {
    var raio = 5 
    var volume = (4/3) * 3.14 * raio * raio * raio 
    println(volume)
}
```

### Atividade 14
```kotlin
fun main() {
    val a = 1.0
    val b = -3.0
    val c = -4.0

    val delta = b * b - 4 * a * c

    val x1 = (-b + Math.sqrt(delta)) / (2 * a)
    val x2 = (-b - Math.sqrt(delta)) / (2 * a)

    println("x1 = $x1")
    println("x2 = $x2")
}

```

### Atividade 15
```kotlin
fun main() {
    var valor1 = 10
    var valor2 = 5
    var valor3 = 8
    var valor4 = 12
    var valor5 = 3 

    var maior = valor1
    var menor = valor1

    if (valor2 > maior) maior = valor2
    if (valor3 > maior) maior = valor3
    if (valor4 > maior) maior = valor4
    if (valor5 > maior) maior = valor5

    if (valor2 < menor) menor = valor2
    if (valor3 < menor) menor = valor3
    if (valor4 < menor) menor = valor4
    if (valor5 < menor) menor = valor5

    var resultado = "Maior número: $maior\nMenor número: $menor"

    println(resultado)
}

```
