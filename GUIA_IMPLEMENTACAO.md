# 🚀 Mercearia do Campo - Guia de Implementação Final

## ✅ Website Completo e Atualizado

### 📄 Estrutura do Website

```
Mercearia do Campo Website
├── index.html          → Landing Page Premium (Página Principal)
├── loja.html           → Loja Virtual (Catálogo de Produtos)
└── logo-mercearia.png  → Logo Oficial
```

---

## 🔗 Navegação Entre Páginas

### **Landing Page → Loja Virtual**
A landing page (`index.html`) tem **múltiplos pontos de entrada** para a loja:

1. **Header** - Botão "Ir para a Loja" (sempre visível)
2. **Menu de Navegação** - Link "Loja Online"
3. **Hero Section** - Botão "Começar a Comprar"
4. **Secção de Categorias** - Botão "Ver Todos os Produtos"
5. **CTA Final** - Botão "Ir para a Loja Online"

### **Loja Virtual → Landing Page**
A loja virtual (`loja.html`) permite voltar à landing page através de:

1. **Logo no Header** - Clique no logo
2. **Botão "Início"** no header
3. **Links no Footer** - "Sobre Nós" redireciona para `index.html#sobre`
4. **Navegação Mobile** - Botão "Início" na barra inferior

---

## 📞 Informações de Contacto Atualizadas

| Campo | Valor |
|-------|-------|
| **Telefone** | [+351 915 517 815](tel:+351915517815) |
| **Email Principal** | [encomendas@merceariadocampo.pt](mailto:encomendas@merceariadocampo.pt) |
| **Email Geral** | geral@merceariadocampo.pt |
| **Morada** | Calçada da Quinta da Serrana 4, 2500-581 Cachoeiras |

---

## 🚚 Informações de Entrega

- **Zonas de Entrega**: Vila Franca de Xira, Arruda e Alenquer
- **Horário de Entregas**: Segunda a Sexta
  - 12:30h - 15:30h
  - 19:30h - 20:30h
- **Entrega Grátis**: Compras acima de **25€** (código: **BEMVINDO**)

---

## 🎨 Identidade Visual

- ✅ **Logo Oficial** integrado (branco, sem fundo)
- ✅ **Cores da Marca**: Verde Esmeralda (#10b981) e tons de cinza
- ✅ **Tipografia**: Inter (Google Fonts)
- ✅ **Design**: Premium, moderno e responsivo

---

## 📱 Responsividade

O website está **100% responsivo** para:
- 📱 **Mobile** (< 768px) - Navegação inferior fixa
- 📲 **Tablet** (768px - 1024px)
- 💻 **Desktop** (> 1024px)

---

## 🌐 Como Publicar no Hostinger

### **Opção 1: Substituir Página Atual**

Esta landing page foi criada para **substituir** a página atual em `www.merceariadocampo.pt`.

#### Passos:

1. **Aceder ao Painel Hostinger**
   - Login em [hpanel.hostinger.com](https://hpanel.hostinger.com)

2. **Ir para File Manager**
   - Websites → merceariadocampo.pt → File Manager

3. **Fazer Backup** (importante!)
   - Descarregar a pasta `public_html` atual

4. **Substituir Ficheiros**
   - Fazer upload de:
     - `index.html` (nova landing page)
     - `loja.html` (catálogo de produtos)
     - `logo-mercearia.png`

5. **Configurar Domínio**
   - Garantir que `index.html` é a página principal
   - A loja virtual fica acessível em `www.merceariadocampo.pt/loja.html`

---

### **Opção 2: Usar Hostinger Website Builder**

Se preferires manter o builder do Hostinger:

1. **Criar Página Personalizada**
   - No Aura Website Builder, adicionar uma nova página
   - Usar elemento "HTML Personalizado"

2. **Copiar Código**
   - Copiar todo o conteúdo de `index.html`
   - Colar no elemento HTML personalizado

3. **Upload do Logo**
   - Fazer upload de `logo-mercearia.png` através do gestor de media
   - Atualizar o caminho no código HTML

---

## 🔍 Checklist Pré-Publicação

Antes de publicar, verificar:

- [ ] Logo está a carregar corretamente
- [ ] Todos os links de navegação funcionam
- [ ] Telefone e email estão corretos e clicáveis
- [ ] Horários de entrega estão corretos
- [ ] Código promocional BEMVINDO está visível
- [ ] Testar navegação mobile
- [ ] Testar em diferentes browsers (Chrome, Firefox, Safari)
- [ ] Links para redes sociais (adicionar URLs reais)

---

## 🎯 Próximos Passos Recomendados

### **Curto Prazo**
1. ✅ Publicar landing page no Hostinger
2. ⚠️ Adicionar links reais das redes sociais (Facebook, Instagram)
3. ⚠️ Configurar Google Analytics (opcional)
4. ⚠️ Testar processo de compra completo

### **Médio Prazo**
1. Integrar sistema de pagamento real (Stripe/MBWay)
2. Adicionar funcionalidade de carrinho de compras
3. Sistema de gestão de encomendas
4. Email marketing / Newsletter

### **Longo Prazo**
1. App móvel (opcional)
2. Programa de fidelização
3. Sistema de avaliações de produtos

---

## 📊 Estrutura de URLs

Depois de publicar, o website terá:

- **Página Principal**: `https://www.merceariadocampo.pt/`
- **Loja Virtual**: `https://www.merceariadocampo.pt/loja.html`
- **Secção Sobre Nós**: `https://www.merceariadocampo.pt/#sobre`
- **Secção Entregas**: `https://www.merceariadocampo.pt/#entregas`
- **Secção Contacto**: `https://www.merceariadocampo.pt/#contacto`

---

## 🆘 Suporte

Se encontrares algum problema:

1. **Verificar Caminhos** - Garantir que `logo-mercearia.png` está na mesma pasta
2. **Limpar Cache** - Ctrl+F5 para forçar refresh
3. **Verificar Console** - F12 no browser para ver erros
4. **Testar Links** - Clicar em todos os botões e links

---

## 📝 Notas Importantes

> [!IMPORTANT]
> Esta landing page foi criada para **substituir** a página atual do Hostinger. Certifica-te de fazer backup antes de substituir!

> [!WARNING]
> Não te esqueças de atualizar os links das redes sociais no footer antes de publicar!

> [!TIP]
> Podes testar localmente abrindo `index.html` no browser antes de fazer upload para o Hostinger.

---

**✨ Website pronto para publicação!**

Todos os dados estão atualizados e a navegação entre páginas está funcional. Boa sorte com o lançamento! 🚀
