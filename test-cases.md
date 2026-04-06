# ✅ Casos de Teste - Semana 1 (QA)

## 🔐 Funcionalidade: Login

---

### 🧪 Caso de Teste 1: Login com dados válidos

- **ID:** CT-01  
- **Descrição:** Validar login com credenciais corretas  

**Passos:**
1. Acessar página de login  
2. Inserir email válido  
3. Inserir senha válida  
4. Clicar em "Entrar"  

**Resultado Esperado:**
Usuário deve ser autenticado com sucesso e redirecionado para a página inicial.

---

### 🧪 Caso de Teste 2: Login com senha incorreta

- **ID:** CT-02  
- **Descrição:** Validar comportamento com senha inválida  

**Passos:**
1. Acessar página de login  
2. Inserir email válido  
3. Inserir senha incorreta  
4. Clicar em "Entrar"  

**Resultado Esperado:**
Sistema deve exibir mensagem de erro informando que a senha está incorreta.

---

### 🧪 Caso de Teste 3: Campos vazios

- **ID:** CT-03  
- **Descrição:** Validar envio com campos em branco  

**Passos:**
1. Acessar página de login  
2. Deixar campos de email e senha vazios  
3. Clicar em "Entrar"  

**Resultado Esperado:**
Sistema deve impedir o envio e exibir mensagens obrigatórias.

---

### 🧪 Caso de Teste 4: Email inválido

- **ID:** CT-04  
- **Descrição:** Validar formato de email inválido  

**Passos:**
1. Acessar página de login  
2. Inserir email em formato inválido (ex: teste@)  
3. Inserir senha válida  
4. Clicar em "Entrar"  

**Resultado Esperado:**
Sistema deve exibir mensagem de erro informando formato inválido de email.

---

### 🧪 Caso de Teste 5: Senha muito curta

- **ID:** CT-05  
- **Descrição:** Validar senha com menos de 8 caracteres  

**Passos:**
1. Acessar página de login  
2. Inserir email válido  
3. Inserir senha com menos de 8 caracteres  
4. Clicar em "Entrar"  

**Resultado Esperado:**
Sistema deve impedir o login e exibir mensagem informando o tamanho mínimo da senha.
