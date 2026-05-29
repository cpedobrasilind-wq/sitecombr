# CPE do Brasil - Site Institucional

Site institucional profissional da CPE do Brasil - Componentes Profissionais para Eletrônica.

## Sobre

Site desenvolvido com React 19 + Tailwind CSS 4, compilado para HTML/CSS/JS estático para hospedagem no GitHub Pages.

## Estrutura

- `index.html` - Página principal (SPA)
- `404.html` - Página de erro (redireciona para index.html para SPA routing)
- `assets/` - Arquivos CSS e JavaScript compilados
- `__manus__/` - Armazenamento de imagens e assets
- `.nojekyll` - Arquivo para desabilitar Jekyll no GitHub Pages

## Como Hospedar no GitHub Pages

### 1. Criar um repositório no GitHub
```bash
gh repo create cpe-do-brasil --public --source=. --remote=origin --push
```

### 2. Configurar GitHub Pages
- Vá para Settings → Pages
- Em "Source", selecione "Deploy from a branch"
- Em "Branch", selecione "main" e pasta "/ (root)"
- Clique em Save

### 3. O site estará disponível em
```
https://seu-usuario.github.io/cpe-do-brasil
```

## Arquivos Inclusos

- `index.html` - Página compilada com todo o conteúdo
- `assets/index-*.css` - Estilos compilados
- `assets/index-*.js` - JavaScript compilado
- `404.html` - Tratamento de rotas para SPA

## Notas

- Todas as imagens estão hospedadas em CDN externo (Manus Storage)
- O site é totalmente responsivo e funciona em todos os navegadores modernos
- Não há dependências externas além dos assets gerados

## Atualizações Futuras

Para atualizar o site:

1. Faça as alterações no projeto React original
2. Execute `pnpm build`
3. Copie os arquivos de `dist/public/` para o repositório GitHub
4. Commit e push para atualizar o site

---

**CPE do Brasil** | Pinhais-PR | www.cpedobrasil.ind.br
