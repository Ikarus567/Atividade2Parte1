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
```

## Questão 2
### Qual a diferença fundamental entre JSON.stringify() e JSON.parse()? Dê um exemplo prático de quando usar cada um.

**JSON.stringify()** ele basicamente converte um objeto JavaScript em uma string JSON, e é usado quando for necessário **enviar dados** (por exemplo, para uma API ou para salvar em um arquivo). 

**JSON.parse()** este faz o contrario do **JSON.stringify()** sendo que ele converte uma string JSON em um objeto JavaScript, e é usado quando for **recebe dados** (por exemplo, de uma API) e quer manipulá-los no código.

### Exemplo prático:

```javascript
const usuario = {
  nome: "Bruno",
  idade: 41,
  profissao : "Professor",
};

const jsonString = JSON.stringify(usuario);
console.log(jsonString);

const usuarioObj = JSON.parse(jsonString);
console.log(usuarioObj.nome);
```

## Questão 3
### Considerando a string "JavaScript é baseada em ECMA Script", quais métodos você usaria para:
#### ● Verificar se contém a palavra "Script";
#### ● Remover a palavra "JavaScript" e gerar uma nova string;
#### ● Substituir "baseada" por "tem origem"

