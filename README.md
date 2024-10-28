## Primeiros passos
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

## Manipulação de branch

1. **Consultar as branches disponíveis**: No seu terminal, acesse o repositório e use o comando:
   ```bash
   git branch
   ```
   -   Esse comando mostrará todas as branches disponíveis no seu repositório local.

2. **Trocar para a branch desejada**: Para mudar para uma branch específica, use:
   ```bash
   git checkout nome-da-branch
   ```
   -   Substitua `nome-da-branch` pelo nome da branch que deseja acessar.

3. **Confirme a mudança de branch**: Após o comando, você deve ver uma mensagem indicando que mudou para a nova branch. Você também pode verificar novamente com:
   ```bash
   git branch
   ```
   -   A branch atual será indicada com um asterisco `*`.

### Comando Alternativo (Git 2.23 ou mais recente)
Se tiver uma versão mais recente do Git, você pode usar o comando `git switch`:
```bash
git switch nome-da-branch
```

Após fazer as mudanças na branch desejada, você pode subir suas alterações para o GitHub usando:
```bash
git push origin nome-da-branch
```
