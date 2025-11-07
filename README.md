#  Atividade 2 - Parte 1  

##  Questão 1  
### O que é JSON e por que ele se tornou tão popular para troca de dados entre aplicações?

**JSON (JavaScript Object Notation)** é um basicamente um formato leve de compartilhammento de dados, baseado em texto e é principalmente utilizado para armazenamento e trasmissão de dados, ele é derivado do java script mas é indepente, significando que ele pode ser usadas por varias linguagens de programação. O JSON se tornou popular por ser leve, simples de se entender e escrever e pela sua independência de linguagem.

### Exemplo de JSON
```json
{
  "nome": "Maria",
  "idade": 25,
  "curso": "Engenharia de Software",
  "habilidades": ["JavaScript", "Python", "HTML"]
}

### 2. Diferença entre `JSON.stringify()` e `JSON.parse()`

A diferença fundamental entre os dois métodos é o **sentido da conversão**:

- **`JSON.stringify()`** → **converte um objeto JavaScript em uma string JSON**.  
  É usado quando você precisa **enviar dados** (por exemplo, para uma API ou para salvar em um arquivo).

- **`JSON.parse()`** → **converte uma string JSON em um objeto JavaScript**.  
  É usado quando você **recebe dados** (por exemplo, de uma API) e quer manipulá-los no código.