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
