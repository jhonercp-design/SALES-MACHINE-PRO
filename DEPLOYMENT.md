# DEPLOYMENT.md - Guia de Deploy

## 🚀 Deploy no Vercel (Recomendado)

A forma mais rápida e fácil de fazer deploy do SALES MACHINE PRO é usando o Vercel.

### Passo 1: Preparar seu Repositório

Certifique-se que:
- [ ] Seu repositório está atualizado no GitHub
- [ ] Todos os arquivos de código estão commitados
- [ ] O arquivo `.env.example` está presente

### Passo 2: Acessar Vercel

1. Vá para https://vercel.com
2. Clique em "Sign Up" (ou faça login se já possui conta)
3. Escolha "Continue with GitHub"
4. Autorize o Vercel a acessar seus repositórios

### Passo 3: Importar Projeto

1. Após logar, clique em "Add New Project"
2. Selecione "Import Git Repository"
3. Procure por "SALES-MACHINE-PRO"
4. Clique em "Import"

### Passo 4: Configurar Variáveis de Ambiente

1. Na página de configuração do projeto, vá até "Environment Variables"
2. Adicione as seguintes variáveis:

```
VITE_API_URL=https://seu-backend.com
VITE_GEMINI_API_KEY=sua_chave_aqui
```

3. Clique em "Save"

### Passo 5: Deploy

1. Clique em "Deploy"
2. Aguarde o processo de build (geralmente 2-3 minutos)
3. Quando terminar, você verá "Congratulations!" com o link da seu site

🎉 **Pronto!** Seu site está online!

---

## 📱 Acessar seu Site

Depois do deploy, você poderá acessar seu site em:
```
https://sales-machine-pro-seu-usuario.vercel.app
```

Ou configure um domínio customizado nas configurações do Vercel.

---

## 🔄 Atualizações Automáticas

Por padrão, o Vercel fará deploy automático sempre que você fizer push para a branch `main`.

Se quiser desabilitar isso:
1. Vá em "Project Settings"
2. Em "Git", desabilite "Automatically deploy on push"

---

## 🐛 Resolvendo Problemas

### Erro: "Build failed"

1. Verifique se todas as dependências foram instaladas
2. Verifique se não há erros de TypeScript: `npm run build`
3. Verifique as variáveis de ambiente

### Erro: "Module not found"

Certifique-se que todos os imports estão corretos e os módulos estão instalados.

### Aplicação em branco

Verifique:
- [ ] Não há erros de CSS
- [ ] Todos os assets estão na pasta `public/`
- [ ] O arquivo `vite.config.ts` está configurado corretamente

---

## 📊 Monitorar Performance

No dashboard do Vercel você pode:
- Ver logs de deploy
- Monitorar performance
- Gerenciar domínios
- Gerenciar equipes

---

## 🔐 Segurança em Produção

Antes de fazer deploy:

- [ ] Remove todos os `console.log` de debug
- [ ] Verify que não há informações sensíveis no código
- [ ] Implement proper error handling
- [ ] Verificar se HTTPS está ativado (automático no Vercel)

---

## 📝 Variáveis de Ambiente

Crie um arquivo `.env.local` com as variáveis necessárias:

```bash
cp .env.example .env.local
```

**Não commit `.env.local` no GitHub!**

---

## ✅ Checklist Final

- [ ] Repositório Git está sincronizado
- [ ] Variáveis de ambiente configuradas
- [ ] Build local testa OK (`npm run build`)
- [ ] Sem erros TypeScript
- [ ] Sem warnings importantes
- [ ] README.md atualizado
- [ ] Domínio customizado configurado (opcional)

---

**Parabéns! Seu SALES MACHINE PRO está no ar! 🎉**
