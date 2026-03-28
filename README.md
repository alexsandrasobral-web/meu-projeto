# 🚀 Guia Git (Bash) — Criar, Subir e Atualizar

![imagem git](https://hermes.dio.me/articles/cover/7eba3ee3-b467-4cae-89d9-536af1d6f092.png)

## 📁 1. Criar um repositório local

```bash
mkdir meu-projeto
cd meu-projeto
git init
```

---

## 📄 2. Criar arquivos no projeto

```bash
echo "# Meu Projeto" > README.md
```

---

## ➕ 3. Adicionar arquivos

```bash
git add .
```

---

## 💾 4. Fazer o primeiro commit

```bash
git commit -m "Primeiro commit"
```

---

## 🔗 5. Conectar ao repositório remoto (GitHub, GitLab, etc.)

```bash
git remote add origin https://github.com/usuario/meu-projeto.git
```

---

## ⬆️ 6. Subir o projeto (push)

```bash
git branch -M main
git push -u origin main
```

---

## 🔄 7. Atualizar o projeto (fluxo diário)

### 👉 Fazer alterações nos arquivos e depois:

```bash
git add .
git commit -m "Descrição da alteração"
git push
```

---

## ⬇️ 8. Baixar atualizações do remoto

```bash
git pull
```

---

## 🔍 9. Verificar status e histórico

```bash
git status
git log --oneline
```

---

## ⚠️ 10. Resolver erro comum (repositório já tem conteúdo)

```bash
git pull origin main --allow-unrelated-histories
```

---

# 🔁 Fluxo resumido do dia a dia

```bash
git add .
git commit -m "mensagem"
git push
```

---

## 💡 Dica importante

Se estiver usando **Bash (Linux, Git Bash ou terminal do VS Code)**, todos esses comandos funcionam da mesma forma.



