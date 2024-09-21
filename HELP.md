### 1. **Iniciar um novo site:**
   ```bash
   hugo new site <nome-do-site>
   ```
   Cria um novo projeto Hugo na pasta especificada.

### 2. **Servir o site localmente (modo de desenvolvimento):**
   ```bash
   hugo server
   ```
   Inicia um servidor local para ver as alterações em tempo real. O site estará disponível em `http://localhost:1313`.

### 3. **Criar um novo post ou página:**
   ```bash
   hugo new <pasta>/<nome-do-post>.md
   ```
   Exemplo para criar um novo post:
   ```bash
   hugo new posts/meu-primeiro-post.md
   ```

### 4. **Gerar o site estático:**
   ```bash
   hugo
   ```
   Gera a versão estática do site na pasta `public`.

### 5. **Especificar um diretório de destino para a build:**
   ```bash
   hugo -d <diretório>
   ```
   Especifica um diretório diferente para a saída dos arquivos gerados.

### 6. **Incluir drafts no servidor local:**
   ```bash
   hugo server -D
   ```
   Por padrão, Hugo não inclui os drafts (rascunhos) quando gera o site ou o servidor local. Esse comando inclui os rascunhos.

### 7. **Listar todas as configurações possíveis:**
   ```bash
   hugo config
   ```
   Mostra todas as configurações que podem ser definidas no `config.toml` ou `config.yaml`.

### 8. **Criar um conteúdo com data futura (futuro post):**
   ```bash
   hugo server --buildFuture
   ```
   Inclui conteúdos que têm datas futuras definidas no front matter ao servir o site localmente.

### 9. **Incluir conteúdo expirado:**
   ```bash
   hugo server --buildExpired
   ```
   Exibe conteúdo expirado localmente.

### 10. **Verificar a versão do Hugo:**
   ```bash
   hugo version
   ```
