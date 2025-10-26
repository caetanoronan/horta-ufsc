# 🚀 Como Publicar no GitHub Pages

## Passo a Passo para Publicar o Site da Horta Comunitária UFSC

### 1. Criar uma Conta no GitHub
- Acesse [github.com](https://github.com)
- Clique em "Sign up" e crie sua conta
- Confirme seu email

### 2. Criar um Novo Repositório
- Faça login no GitHub
- Clique no botão "+" no canto superior direito
- Selecione "New repository"
- Nome sugerido: `horta-ufsc` (ou outro nome de sua preferência)
- Deixe como **público** (necessário para GitHub Pages gratuito)
- **NÃO** marque "Initialize this repository with a README"
- Clique em "Create repository"

### 3. Conectar seu Projeto Local ao GitHub
Abra o terminal/PowerShell na pasta do projeto e execute:

```powershell
# Adicionar a origem remota (substitua [SEU-USUARIO] pelo seu username do GitHub)
git remote add origin https://github.com/[SEU-USUARIO]/horta-ufsc.git

# Renomear a branch principal para 'main' (padrão atual do GitHub)
git branch -M main

# Enviar o código para o GitHub
git push -u origin main
```

### 4. Configurar o GitHub Pages
1. No seu repositório no GitHub, clique na aba "Settings"
2. Role até a seção "Pages" no menu lateral esquerdo
3. Em "Source", selecione "Deploy from a branch"
4. Em "Branch", selecione "main"
5. Em "Folder", deixe "/ (root)"
6. Clique em "Save"

### 5. Acessar seu Site
- Aguarde alguns minutos (pode levar até 10 minutos)
- Seu site estará disponível em: `https://[SEU-USUARIO].github.io/horta-ufsc`
- O GitHub mostrará a URL na seção Pages das configurações

### 6. Atualizações Futuras
Para fazer atualizações no site:

```powershell
# Fazer mudanças nos arquivos
# Adicionar as mudanças ao Git
git add .

# Fazer commit das mudanças
git commit -m "Descrição da mudança"

# Enviar para o GitHub
git push origin main
```

O site será atualizado automaticamente em alguns minutos.

### 📋 Checklist de Publicação
- [ ] Conta criada no GitHub
- [ ] Repositório criado como público
- [ ] Código enviado para o GitHub
- [ ] GitHub Pages configurado
- [ ] Site acessível via URL do GitHub Pages
- [ ] README.md atualizado com a URL correta do site

### 🛠️ Comandos Úteis

**Ver status do repositório:**
```powershell
git status
```

**Ver histórico de commits:**
```powershell
git log --oneline
```

**Verificar conexão com GitHub:**
```powershell
git remote -v
```

### ⚠️ Notas Importantes
1. O repositório deve ser **público** para usar GitHub Pages gratuitamente
2. O arquivo principal deve se chamar `index.html`
3. Mudanças podem levar alguns minutos para aparecer no site
4. Use sempre URLs relativas para links internos (como `assets/css/style.css`)

### 🆘 Problemas Comuns
- **Site não carrega**: Verifique se o repositório é público e se o GitHub Pages está ativo
- **CSS não aparece**: Verifique se os caminhos dos arquivos estão corretos (use barras `/` não `\`)
- **404 Error**: Certifique-se de que o arquivo se chama `index.html` (minúsculo)

---

📞 **Precisa de ajuda?** Entre em contato com a equipe de TI da UFSC ou consulte a documentação oficial do GitHub Pages.