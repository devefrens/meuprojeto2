<<<<<<< HEAD
# Como configurar e enviar um projeto para o GitHub

Este guia descreve os passos para configurar e enviar um repositório Git local para o GitHub.

---

## **1. Navegar para o diretório correto**
Certifique-se de que você está no diretório clonado:

```cmd
cd meuprojeto2
```

---

## **2. Verificar se o repositório foi clonado corretamente**
Dentro do diretório `meuprojeto2`, verifique se ele é um repositório Git:

```cmd
git status
```

- Se o comando funcionar, você está no lugar certo.
- Se aparecer um erro, o repositório pode não ter sido clonado corretamente. Nesse caso, clone novamente:

```cmd
git clone git@github.com:devefrens/meuprojeto2.git
cd meuprojeto2
```

---

## **3. Adicionar o arquivo e fazer o commit**
Agora que você está no repositório correto, siga os passos abaixo:

### **3.1. Criar ou editar o arquivo README.md**
Crie um arquivo README.md para descrever seu projeto:

```cmd
echo "# meuprojeto2" > README.md
```

### **3.2. Adicionar o arquivo ao Git**
Adicione o arquivo ao sistema de controle de versão do Git:

```cmd
git add README.md
```

### **3.3. Fazer o commit**
Registre a alteração no histórico do repositório com uma mensagem de commit:

```cmd
git commit -m "Adiciona o arquivo README.md"
```

### **3.4. Enviar para o GitHub**
Envie as alterações locais para o repositório remoto no GitHub:

```cmd
git push -u origin main
```

---

Agora o seu projeto está configurado e publicado no GitHub! 🎉
=======
# meuprojeto2
>>>>>>> origin/main
