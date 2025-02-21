## 🚀 Como iniciar com Git e GitHub em projetos pessoais 

### 1️⃣ Instalando o Git  
Baixe e instale pelo site oficial:  
🔗 [https://git-scm.com/](https://git-scm.com/)  

Após instalar, verifique se a instalação foi concluída corretamente:  
```bash
#Comando para verificar a versao do git, nos programas git bash ou cmd ou shel
git --version
```

## 2️⃣ Criando uma conta no GitHub

1. Acesse 🔗 [https://github.com/](https://github.com/).  
2. Clique em **Sign up**.  
3. Escolha entre se cadastrar com **Google** ou com um **e-mail e senha**.  
4. Confirme sua conta pelo e-mail e faça login.  
5. Após o login, vá até a aba **Repositórios** e clique em **New**.  

## 3️⃣ Configurando o Git pela primeira vez

Após instalar o Git, abra o Git Bash e configure seu nome e e-mail:

```bash
# Configurar nome e e-mail globalmente
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"

# Verificar configurações salvas
git config --global --list

#Para excluir a configuração global, use os seguintes comandos:
git config --global --unset user.name
git config --global --unset user.email
```

## 4️⃣ Criando um repositório no GitHub

1. No GitHub, clique em **New Repository**.  
2. Defina um nome para o repositório (ex: `meu-projeto`).  
3. Escolha a visibilidade do repositório:  
   - **Público:** Qualquer pessoa pode ver o projeto.  
   - **Privado:** Apenas você e convidados podem acessar.  
4. Clique em **Create repository**.  

## 5️⃣ Conectando o repositório local ao GitLab

🔹 **Criando um novo repositório local e conectando ao GitLab**

```bash
# Criar uma pasta e entrar nela
mkdir meu-projeto && cd meu-projeto

# Inicializar o repositório Git
git init  

# Criar um arquivo README.md
echo "# Meu Projeto" > README.md

# Adicionar e fazer o primeiro commit
git add .
git commit -m "Primeiro commit"

# Conectar ao repositório remoto
git remote add origin https://gitlab.com/seu-usuario/meu-projeto.git

# Definir o branch principal como 'main'
git branch -M main

# Enviar o projeto para o GitLab
git push -u origin main
```

## 6️⃣ Clonando um repositório GitLab

Se precisar baixar um repositório existente para seu computador, use o seguinte comando:

```bash
git clone https://gitlab.com/seu-usuario/meu-projeto.git
```

## 7️⃣ Atualizando seu repositório

Para obter as últimas mudanças do repositório remoto, use o seguinte comando:

```bash
git pull origin main
git add .
git commit -m "Adicionando novas funcionalidades"
git push origin main
```