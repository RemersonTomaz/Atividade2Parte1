#  Atividade 2 - Parte 1

---

**JSON (JavaScript Object Notation)** é um formato de **texto usado para guardar e trocar informações** entre diferentes programas ou sistemas.  
Ele é inspirado na forma como o **JavaScript** organiza objetos, mas pode ser utilizado em praticamente qualquer linguagem.

---

## Estrutura básica

O JSON usa:

- **Chaves e valores** → `"produto": "Mouse Gamer"`
- **Listas (arrays)** → `"cores": ["preto", "vermelho", "azul"]`
- **Objetos dentro de objetos** → `"fabricante": {"nome": "Redragon", "pais": "China"}`

### **Exemplo:**

```json
{
  "produto": "Mouse Gamer",
  "preco": 149.90,
  "emEstoque": true,
  "cores": ["preto", "vermelho", "azul"],
  "fabricante": {
    "nome": "Redragon",
    "pais": "China"
  }
}
```

### Por que o JSON ficou tão popular

Fácil de entender e leve:
Ele é simples, ocupa pouco espaço e é bem mais fácil de ler do que formatos antigos, como o XML.

Compatível com várias linguagens:
Pode ser usado em praticamente qualquer linguagem de programação — como Python, Java, PHP, C#, etc.

Muito usado em APIs:
É o formato mais comum para trocar informações entre sites, aplicativos e servidores.

Conversão prática:
É fácil transformar um JSON em um objeto dentro do código, sem precisar de muito esforço.

O JSON é popular porque é simples, leve e funciona em qualquer lugar, sendo o jeito mais comum de trocar dados na internet hoje em dia.

## Diferença entre `JSON.stringify()` e `JSON.parse()`

Essas duas funções servem para **converter dados** entre **objeto JavaScript** e **texto no formato JSON**, mas cada uma faz o contrário da outra.

---

### `JSON.stringify()`
Essa função **transforma um objeto em texto JSON**.  
Usamos quando queremos **enviar os dados para algum lugar** ou **guardar** em algum local que só aceita texto.

#### Exemplo:
```js
const aluno = { nome: "Lucas", idade: 18, curso: "Informática" };
const textoJSON = JSON.stringify(aluno);

console.log(textoJSON);
// Resultado: {"nome":"Lucas","idade":18,"curso":"Informática"}
```

Quando usar:

Para enviar dados para uma API ou servidor.

Para salvar dados no localStorage do navegador.

JSON.parse()

Essa função faz o contrário: ela transforma um texto JSON em um objeto JavaScript.
Usamos quando queremos pegar um texto que veio de fora (como de uma API) e usar os dados no código.

Exemplo:
const textoJSON = '{"nome":"Lucas","idade":18,"curso":"Informática"}';
const aluno = JSON.parse(textoJSON);

console.log(aluno.curso);
// Resultado: Informática


### Quando usar:

Para ler dados que vieram de uma API.
Para pegar dados salvos no localStorage e usar no programa.

JSON.stringify()	Transforma um objeto em texto JSON	Usado pra enviar ou guardar dados
JSON.parse()	Transforma um texto JSON em objeto	Usado pra ler ou usar dados recebidos
