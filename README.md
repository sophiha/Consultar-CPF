# 🔍 Consulta de CPF ou Nome completo

Um sistema de consulta de CPF ou Nome completo direto pelo Discord. Rápido, fácil e totalmente **gratuito**

[![Entrar no Discord](https://img.shields.io/badge/Entrar%20no%20Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/3xYsYXZR2y)

---

## 🖼️ Previews

**Consulta por CPF**

![Preview CPF](https://i.imgur.com/oyuZmF7.png)

**Consulta por Nome completo**

![Preview Nome completo](https://i.imgur.com/b0WXiei.png)

---

## 🔧 Como usar a API

Para realizar consultas, utilize os seguintes endpoints:

**Consulta por Nome completo**

```
GET http:/51.81.22.2:3000/?tipo=nome&valor=GLEDE BERNACCI GOLLUSCIO&key=CHAVE
GET http:/51.81.22.2.193:3000/?tipo=nome&valor=GLEDE BERNACCI GOLLUSCIO&idade=87&key=CHAVE (idade é opcional)
```

**Consulta por CPF**

```
GET http:/51.81.22.2:3000/?tipo=cpf&valor=11111111111&key=CHAVE
```

## 💡 Observações

- A consulta é **100% gratuita** via Discord
- A versao via site será lançada **quando eu tiver vontade**, sem previsao
