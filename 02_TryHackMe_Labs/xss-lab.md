# 🧪 TryHackMe – XSS Lab

## 🎯 Objetivo do Lab

Explorar falhas de **Cross-Site Scripting (XSS)** e entender como é possível injetar scripts maliciosos em páginas vulneráveis para afetar outros usuários.

## 🛠️ Ferramentas Utilizadas

- Navegador (TryHackMe Web Interface)
- Console do navegador (para ver execução dos scripts)
- Burp Suite (opcional, para capturar requisições)

## 🧾 Exemplos de Payloads Usados

```html
<script>alert('Hacked by Simone')</script>
<img src="x" onerror="alert('XSS')">
