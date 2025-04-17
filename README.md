# 💻 Comandos Git Mais Usados – Colinha do Pai

# 🔥 Configuração Inicial
```
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"
```

# 🏠 Criar ou clonar repositório
```
git init
git clone https://github.com/usuario/repositorio.git
```

# 📂 Adicionar e confirmar mudanças
```
git add .
git commit -m "mensagem do commit"
```

# 🚀 Enviar pro GitHub
```
git remote add origin https://github.com/usuario/repositorio.git
git push -u origin main
git push
```

# 🔄 Baixar mudanças do GitHub
```
git pull origin main
```

# 🧑‍🤝‍🧑 Branches
```
git branch nome-da-branch
git checkout nome-da-branch
git checkout -b nome-da-branch
git branch -d nome-da-branch
```

# ⚙️ Outros úteis
```
git status
git log
git remote -v
```

# 🔥 Dicas úteis
```
git reset --soft HEAD^
git reset --hard HEAD^
git checkout -- nome-do-arquivo
git tag -a v1.0 -m "Primeira versão"
git show commit-hash
git diff commit-hash1 commit-hash2
git diff
git log --oneline
git fetch
```
