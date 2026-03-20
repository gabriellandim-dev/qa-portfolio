# 🐞 Bug Report - Camicado

## 📌 Título
Busca com "@@@" causa erro "Bad Request" no desktop e comportamento inconsistente com mobile

---

## 🌐 Ambiente
- Site: Camicado
- Navegador: Chrome
- Dispositivo: Desktop (PC)
- Comparação: Mobile
- Data: 20/03/2026

---

## 🧪 Cenário
Usuário realiza busca com caracteres especiais

---

## 🔁 Passos para reproduzir
1. Acessar o site da Camicado
2. Digitar "@@@" na barra de busca
3. Pressionar Enter

---

## ✅ Resultado esperado
Sistema deve tratar a entrada inválida e exibir mensagem amigável ou sugestão de busca, mantendo comportamento consistente entre dispositivos

---

## ❌ Resultado atual
- Desktop: retorna erro "Bad Request" com informações técnicas (IP, Request ID, Edge Location)
- Mobile: exibe mensagem amigável "Ops, não encontramos nenhum resultado"

---

## 🚨 Severidade
Alta

---

## 📊 Prioridade
Alta

---

## 💡 Observações
- O erro ocorre com três caracteres "@"
- Com um ou dois caracteres, funciona normalmente
- Indica possível falha de validação de entrada no ambiente desktop
- Comportamento inconsistente entre plataformas

---

## 📷 Evidência

### Desktop
![Erro Bad Request Desktop](https://github.com/user-attachments/assets/d626e4f0-6996-4014-9927-f0f5de725a4c)


### Mobile
![Mensagem de erro amigável no mobile](https://github.com/user-attachments/assets/6a482c29-ff8d-475b-9046-00d5bd31d9e8)
