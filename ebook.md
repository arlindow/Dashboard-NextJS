### npm run dev ###
# Criando um novo projeto
## Recomendamos usarpnpmcomo seu gerenciador de pacotes, pois é mais rápido e eficiente que npmou yarn. Se você não tiver pnpm instalado, você pode instalá-lo globalmente executando: ##
npm install -g pnpm

-------------------------------------------------------------------------------------------------------
# Para criar um aplicativo Next.js, abra seu terminal,cdna pasta onde você deseja manter seu projeto e execute o seguinte comando: 

npx create-next-app@latest nextjs-dashboard --example "https://github.com/vercel/next-learn/tree/main/dashboard/starter-example" --use-pnpm


## Esse comando utiliza o utilitário `npx` para criar um novo projeto Next.js com o nome `nextjs-dashboard`, usando um exemplo específico de um repositório GitHub. Vamos detalhar cada parte:

1. **`npx create-next-app@latest`**: 
   - O `npx` executa pacotes Node.js diretamente da linha de comando, sem a necessidade de instalação prévia.
   - O pacote `create-next-app` é utilizado para criar um novo aplicativo Next.js. O sufixo `@latest` garante que a versão mais recente do pacote seja utilizada.

2. **`nextjs-dashboard`**:
   - Esse é o nome da pasta do projeto que será criada. Todos os arquivos do projeto serão salvos dentro desta pasta.

3. **`--example "https://github.com/vercel/next-learn/tree/main/dashboard/starter-example"`**:
   - O parâmetro `--example` permite que você use um projeto de exemplo como ponto de partida para o seu próprio projeto.
   - O link especificado (`https://github.com/vercel/next-learn/tree/main/dashboard/starter-example`) aponta para um exemplo de "Dashboard" fornecido pela Vercel. O código deste exemplo será clonado para o novo projeto.

4. **`--use-pnpm`**:
   - Esse parâmetro força o uso do gerenciador de pacotes `pnpm` ao invés do `npm` ou `yarn`, o que pode ser útil em casos onde se deseja gerenciar dependências de forma mais eficiente (especialmente em projetos maiores).

Em resumo, esse comando cria um novo projeto Next.js com o nome `nextjs-dashboard`, baseado em um exemplo de "Dashboard" retirado de um repositório GitHub, e utiliza o `pnpm` para gerenciar as dependências.
----------------------------------------------------------------------------------------------------------

Para atualizar o Node.js pelo terminal, o processo varia dependendo do seu sistema operacional. Aqui estão os métodos para os principais sistemas:

### **Windows (via `nvm-windows`)**

1. **Instalar `nvm-windows`** (Node Version Manager):
   - Se você ainda não tem o `nvm-windows`, pode baixá-lo [aqui](https://github.com/coreybutler/nvm-windows/releases). Isso permitirá gerenciar várias versões do Node.js facilmente.
   - Instale o `nvm-windows` seguindo as instruções no site.

2. **Verificar a versão do Node.js instalada**:
   ```bash
   node -v
   ```

3. **Instalar a nova versão do Node.js**:
   - Use o `nvm` para listar as versões disponíveis do Node.js:
     ```bash
     nvm list available
     ```
   - Para instalar a versão mais recente (por exemplo, 18.17.0 ou superior):
     ```bash
     nvm install 18.17.0
     ```

4. **Usar a nova versão**:
   - Para ativar a nova versão:
     ```bash
     nvm use 18.17.0
     ```

5. **Verificar a versão ativa**:
   ```bash
   node -v
   ```
----------------------------------------------------------------------------------------------------------
