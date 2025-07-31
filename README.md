1. Instalar Java e JDK
2. Instalar Node - LTS
3. Instalar Android Studio 
4. Instalar Reactive native (Depois de instalar Node) - `npx create-expo-app@latest`

### **Colocar o projeto no Github:**

`git branch --set-upstream-to=origin/main main`   

`git pull origin main --allow-unrelated-histories`

`git branch -m master main`

### 1. **Inicialize seu repositório local**

Se você ainda não inicializou seu repositório local, vá até a pasta do seu projeto e execute:

```bash
git init
```

### 2. **Adicione os arquivos ao repositório**

Adicione os arquivos que deseja enviar ao repositório remoto:

```bash
git add .
```

### 3. **Faça um commit das suas alterações**

Crie um commit com uma mensagem descritiva:

```bash
git commit -m "Mensagem do commit"
```

### 4. **Crie o repositório remoto**

Acesse uma plataforma de hospedagem de repositórios (como GitHub, GitLab, ou Bitbucket) e crie um novo repositório. Após criar, você terá uma URL do repositório remoto.

### 5. **Adicione o repositório remoto ao seu repositório local**

Substitua `<URL-do-repositorio>` pela URL que você obteve ao criar o repositório remoto. Execute o seguinte comando:

```bash
git remote add origin <URL-do-repositorio>
```

### 6. **Envie seu código para o repositório remoto**

Agora, envie seu código para o repositório remoto na branch `main`:

```bash
git push -u origin main
```

Se você estiver enviando pela primeira vez, pode ser solicitado que você autentique sua conta (dependendo da plataforma que está usando).

### 7. **Verifique se o código foi enviado**

Acesse o repositório remoto na sua plataforma de hospedagem para confirmar que os arquivos foram enviados corretamente.

### 8. **Próximos passos**

Para futuras alterações, você pode seguir os passos de adicionar, commitar e enviar novamente:

```bash
git add .
git commit -m "Sua mensagem de commit"
git push

```
