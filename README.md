1. **Crie um repositório no GitHub**:
   - Acesse [GitHub](https://github.com) e faça login.
   - Clique em **"New repository"**.
   - Dê um nome ao seu repositório e, se desejar, adicione uma descrição.
   - Escolha se o repositório será público ou privado.
   - Clique em **"Create repository"**.

2. **Configure o Git no seu computador**:
   - Abra o terminal (ou prompt de comando).
   - Navegue até a pasta do seu projeto.
   - Inicialize o repositório Git local com o comando:
     ```bash
     git init
     ```

3. **Adicione os arquivos do projeto**:
   - Adicione todos os arquivos do projeto ao repositório com o comando:
     ```bash
     git add .
     ```

4. **Faça o commit das alterações**:
   - Crie um commit com uma mensagem descritiva:
     ```bash
     git commit -m "Primeiro commit"
     ```

5. **Conecte o repositório local ao GitHub**:
   - Adicione a URL do repositório remoto:
     ```bash
     git remote add origin https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
     ```

6. **Renomeie a branch principal para `main`**:
   - Renomeie a branch `master` para `main` com o comando:
     ```bash
     git branch -M main
     ```

7. **Envie os arquivos para o GitHub**:
   - Envie os arquivos com o comando:
     ```bash
     git push -u origin main
     ```
