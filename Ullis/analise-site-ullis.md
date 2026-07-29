# Análise Completa — Site Ullis + Plano do Novo Site

## Contexto
- **Site atual:** ullis.com.br (WordPress, design cinza escuro)
- **Protótipo existente:** 177.154.191.140/~wwwulliscom (Elementor, cores da marca)
- **Instagram:** @ullistecnicaortopedica — 433 posts, 2.994 seguidores, ativo
- **Empresa:** Ullis Técnica Ortopédica — fundada em 1986, 4 unidades em SC

---

## Scores do site atual

| Dimensão | Nota | Status |
|---|---|---|
| SEO | 2/10 | 🔴 Crítico |
| UX Design | 4/10 | 🟡 Precisa melhorar |
| Conteúdo | 3/10 | 🔴 Crítico |
| Performance | 5/10 | 🟡 Médio |

---

## Problemas SEO (Críticos)

1. **Zero tags H1** no site inteiro — o erro mais grave possível
2. **Meta description vazia** em todas as páginas
3. **Apenas 311 palavras** no site todo — Google não ranqueia
4. **Sem blog** — impossível competir por keywords como "prótese Florianópolis"
5. **Alt text das imagens** são nomes de arquivo (CABEÇALHO.png, etc.)
6. **Sem schema markup** — sem LocalBusiness, MedicalBusiness, FAQ
7. **Título em caixa alta** — deveria ser "Próteses e Órteses em Florianópolis | Ullis"
8. **Sem Open Graph description** — compartilhamento no WhatsApp/redes sem preview

---

## Problemas UX Design

1. **Vídeo do YouTube quebrado** — conta encerrada, péssima primeira impressão
2. **Página "Nossos Serviços"** tem apenas 2 imagens, sem texto, vai direto pro footer
3. **Menu com 3 itens** — faltam Quem Somos, Blog, Contato, Unidades
4. **Design não usa cores da marca** — site usa cinza escuro, cores reais são teal #1C8292 + dourado #FBAE32
5. **Sem depoimentos** — Instagram tem casos reais, site tem zero prova social
6. **CTA WhatsApp** sem texto, só ícone
7. **Todo texto em caixa alta** — dificulta leitura

---

## Pontos Fortes (amplificar no novo site)

- 🏆 **40 anos de mercado** (fundada em 1986) — quase não mencionado
- 🥇 **Prêmio Top de Marcas e Qualidade Catarinense** — sem destaque visual
- 📍 **4 unidades** — Florianópolis, Criciúma, Balneário Camboriú, Joinville
- 📱 **Instagram ativo** com cases reais e depoimentos de pacientes
- 👨‍⚕️ **Equipe com rosto** — Valter Lisboa, Ulla Lisboa, Davi V. Lisboa
- 🦿 **Especialização** — próteses e órteses adulto, infantil, membro sup/inf, esporte
- ✅ **Avaliação gratuita** — CTA diferenciado e pouco explorado

---

## Design Brief — Novo Site

### Identidade Visual
- **Fontes:** Prompt (títulos/nav) + Epilogue (corpo)
- **Cor primária:** #1C8292 (teal)
- **Cor secundária:** #FBAE32 (dourado — CTAs)
- **Background:** #F0F0FF (lavanda claro), #FFFFFF
- **Texto:** #333333

### Estrutura de Páginas

| Página | Objetivo |
|---|---|
| Home | Hero + credenciais + serviços + depoimentos + unidades + CTA |
| Quem Somos | 40 anos de história, fundadores, equipe, missão/visão, prêmios |
| Próteses | Membro inferior, superior, infantis, esportivas — conteúdo rico |
| Órteses | Tipos, indicações, processo, FAQ |
| Avaliação Gratuita | Formulário + WhatsApp + o que esperar |
| Unidades | Mapa das 4 unidades com Google Maps |
| Blog | Artigos SEO por keyword — casos de sucesso, como funciona X |
| Contato | Formulário + WhatsApp + endereços + Google Maps |

### Requisitos Técnicos

**Performance:**
- Next.js (SSG) ou HTML/CSS puro
- Imagens em WebP + lazy loading
- Font subsetting
- LCP < 2.5s, CLS < 0.1
- CDN + cache headers

**SEO:**
- H1 único e otimizado por página
- Meta description 150 chars em todas as páginas
- Schema markup: LocalBusiness + MedicalBusiness
- Sitemap XML + robots.txt
- Open Graph + Twitter Cards

**Conversão:**
- WhatsApp flutuante sempre visível
- CTA "Avaliação Gratuita" no hero e em cada página
- Formulário simples (nome, telefone, cidade)
- Depoimentos com foto e nome

---

## Keywords prioritárias para SEO

- prótese Florianópolis
- órtese Florianópolis
- prótese de perna SC
- clínica ortopédica Florianópolis
- prótese infantil Santa Catarina
- órtese para coluna
- prótese esportiva
- reabilitação ortopédica Florianópolis

---

## Próximos passos

1. [ ] Criar estrutura HTML do novo site
2. [ ] Implementar home page com todas as seções
3. [ ] Criar páginas de serviço (Próteses e Órteses) com conteúdo rico
4. [ ] Criar página Quem Somos
5. [ ] Criar estrutura de Blog
6. [ ] Implementar SEO técnico (meta tags, schema, sitemap)
7. [ ] Otimizar imagens e performance
8. [ ] Deploy
