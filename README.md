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
