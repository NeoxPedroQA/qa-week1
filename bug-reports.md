# 🐞 Bug Reports - Semana 1 (QA)

---

## 🐞 Bug 1: Login permite envio com campos vazios

- **ID:** BUG-01  
- **Severidade:** Alta  
- **Prioridade:** Alta  

### 📌 Descrição
Foi identificado um defeito no sistema de login onde é possível tentar realizar autenticação sem preencher os campos obrigatórios.

---

### 🔁 Passos para reproduzir
1. Acessar a página de login  
2. Deixar os campos de email e senha vazios  
3. Clicar em "Entrar"  

---

### ✅ Resultado esperado
O sistema deve impedir o envio e exibir mensagens informando que os campos são obrigatórios.

---

### ❌ Resultado atual
O sistema permite a tentativa de login sem preenchimento dos campos.

---

---

## 🐞 Bug 2: Sistema aceita senha com menos de 8 caracteres

- **ID:** BUG-02  
- **Severidade:** Alta  
- **Prioridade:** Média  

### 📌 Descrição
Foi identificado que o sistema permite autenticação com senha inferior a 8 caracteres, contrariando a regra de segurança.

---

### 🔁 Passos para reproduzir
1. Acessar a página de login  
2. Inserir email válido  
3. Inserir senha com menos de 8 caracteres  
4. Clicar em "Entrar"  

---

### ✅ Resultado esperado
O sistema deve impedir o login e informar o tamanho mínimo da senha.

---

### ❌ Resultado atual
O sistema permite o login com senha inválida.

---

---

## 🐞 Bug 3: Mensagem de erro pouco clara ao inserir senha incorreta

- **ID:** BUG-03  
- **Severidade:** Média  
- **Prioridade:** Baixa  

### 📌 Descrição
A mensagem exibida ao inserir senha incorreta não é clara o suficiente para orientar o usuário.

---

### 🔁 Passos para reproduzir
1. Acessar a página de login  
2. Inserir email válido  
3. Inserir senha incorreta  
4. Clicar em "Entrar"  

---

### ✅ Resultado esperado
O sistema deve exibir mensagem clara informando que a senha está incorreta.

---

### ❌ Resultado atual
A mensagem exibida é genérica ou confusa.
