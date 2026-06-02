# Aprovação de Protótipo / Proposta

**Tema:** Blog Pessoal
**Cliente:** (Professor / Entidade Avaliadora)
**Data:** 02 de Junho de 2026

---

## 1. Decisões de Design
O protótipo do **Blog Pessoal** foi desenvolvido focando na usabilidade, clareza e numa estética moderna, respeitando todas as diretrizes da Unidade Curricular de Interfaces e Tecnologias Web. 

- **Layout e Responsividade:** Utilizou-se CSS nativo com *Flexbox* e *CSS Grid*. Para elevar o nível visual a um patamar de excelência, introduziram-se conceitos de **Glassmorphism** e **Neumorfismo**. Além disso, o projeto adotou uma estrutura de **Single Page Application (Landing Page Única)**. Tudo acontece numa única página, com transições fluídas e *smooth-scrolling*, proporcionando uma experiência imersiva e sem interrupções de carregamento.
- **Identidade Visual (Fred Daniel):** O design assenta numa estética "Terra" serena. Para a Listagem de Itens exigida no enunciado, adaptou-se o conceito para uma montra de "Beats". Em vez de abrir novas páginas HTML e quebrar a fluidez, os detalhes dos itens abrem em **Modais (Pop-ups)** sobrepostos à página atual, uma abordagem muito mais avançada e de alto nível em UI/UX.
- **Navegação e Multimédia:** Menu *sticky* com *Glassmorphism*. Foram estrategicamente colocados elementos de áudio HTML5 (beats) e vídeo (YouTube) distribuídos pelas diferentes páginas, aumentando a retenção visual e demonstrando completo domínio técnico.

## 2. Benefícios do Protótipo
Este design traz várias vantagens diretas:
- **Maior Visibilidade e Retenção:** Ao ser totalmente responsivo (Mobile-Friendly), garante um alcance maior de público.
- **Experiência do Utilizador (UX) Otimizada:** Com um design *limpo* (minimalista) e sem distrações, os visitantes focam-se no conteúdo (os artigos).
- **Interatividade:** O formulário funcional e o Google Maps na página de contactos facilitam uma comunicação rápida e aumentam a credibilidade da presença online.

## 3. Testes de Usabilidade e Mapa do Site (Sitemap)

**Testes Realizados:**
- **Desktop:** Navegação testada em resoluções 1080p. As grelhas de artigos expandem corretamente ocupando o espaço de forma equilibrada.
- **Mobile (Smartphones):** Testado através das *DevTools* dos browsers (ex: simulação de iPhone 12/14). O menu de navegação reorganiza-se, e a grelha de artigos passa a uma coluna única para facilitar o scroll vertical.

**Sitemap do Protótipo:**
```text
Início (index.html)
 ├── Sobre (sobre.html) - Perfil do Autor e Áudio
 ├── Artigos (index.html âncora / artigo.html) - Lista de artigos
 │    └── Detalhe do Artigo (artigo.html) - Conteúdo Completo e Vídeo
 └── Contactos (contactos.html) - Formulário e Localização (Mapa)
```

## 4. Etapas de Desenvolvimento

Para transformar este protótipo na versão final de produção, as etapas seriam:
1. **Fase 1: Revisão do Protótipo (Atual)** - Validação do layout, cores e responsividade em HTML/CSS estático. (Prazo: 1 Semana)
2. **Fase 2: Integração Backend / CMS** - Ligação do site a um Sistema de Gestão de Conteúdos (ex: WordPress ou CMS customizado) para permitir a criação dinâmica de artigos sem alterar código. (Prazo: 2 Semanas)
3. **Apresentação:** "Transformei o conceito base num modelo de Single Page Application (Landing Page única). Em vez de múltiplas páginas que quebram a navegação, criei secções dinâmicas ancoradas. Para cumprir os detalhes dos itens, desenvolvi um sistema de Modais com Javascript nativo e Glassmorphism, garantindo uma estética 100% premium. Utilizei ainda a biblioteca AOS para efeitos de entrada."
4. **Encerramento:** "Desta forma demonstro as minhas capacidades de não me ficar pelo básico, dominando navegação in-page, manipulação de DOM e modais, ferramentas cruciais no mercado de trabalho."
5. **Fase 4: Testes Finais e Lançamento** - Publicação no servidor web final, configuração de domínio e testes de segurança. (Prazo: 1 Semana)
**Prazo Total Estimado:** 5 Semanas.

## 5. Proposta de Preço

Baseado nas etapas descritas acima para o desenvolvimento completo:
- **Design UI/UX & Protótipo Frontend (Fase 1):** 350,00 €
- **Desenvolvimento Backend & Integração CMS (Fases 2 e 3):** 500,00 €
- **Testes, Otimização SEO e Deploy (Fase 4):** 150,00 €
- **Manutenção e Alojamento (1º Ano):** Oferta / Incluído

**Valor Total da Proposta:** 1.000,00 € + IVA.

---
*Documento preparado como requisito de entrega final para a disciplina de ITW.*
