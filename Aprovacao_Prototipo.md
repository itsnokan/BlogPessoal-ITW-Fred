# Aprovação de Protótipo / Proposta

**Tema:** Blog Pessoal
**Cliente:** (Professor / Entidade Avaliadora)
**Data:** 02 de Junho de 2026

---

## 1. Decisões de Design
O protótipo do **Blog Pessoal** foi desenvolvido focando na excelência máxima de UI/UX, aplicando ferramentas modernas e indo além do currículo base.

- **Layout e Responsividade:** Utilizou-se CSS nativo com **Flexbox** e **CSS Grid**, mas elevado com **Modo Noturno (Dark Mode)**, **Glassmorphism Dinâmico** e **Efeitos 3D**. O projeto opera como uma verdadeira **Single Page Application (Landing Page Única)** com transições altamente polidas e cinemáticas através da biblioteca AOS.js.
- **Identidade Visual e Copywriting:** Como foi pedido um "Blog Pessoal", escrevi os textos de forma genuína sobre a minha experiência em LEI e a conciliação com a música, dividindo as secções por "Setup", "Diário de Bordo" e a minha parceira.
- **Interatividade (Os Modais):** Para cumprir a exigência do enunciado (Listagem de Itens e Detalhe do Item), criei um sistema de Pop-ups (Modais) flutuantes super elegantes. Os cartões reagem fisicamente ao rato (Tilt 3D) usando VanillaTilt.js.

## 2. Benefícios do Protótipo
- **Velocidade:** Sem plugins pesados, o CSS e JS carregam instantaneamente.
- **Fácil Manutenção:** O CSS está organizado em secções (`header`, `section-wrapper`, `caixa-escura`), facilitando a leitura para o professor corrigir.

## 3. Testes de Usabilidade e Mapa do Site (Sitemap)

**Testes Realizados:**
- **Desktop:** Navegação testada em monitores. O CSS Grid organiza os projetos e o Flexbox alinha o cabeçalho.
- **Mobile:** O site adapta-se, escondendo a navegação complexa e empilhando os conteúdos verticalmente.

**Sitemap Lógico (Single Page Application):**
Como o site é uma página única para maior modernidade, o fluxo lógico é:
```text
index.html (Página Principal)
 ├── Início (Hero Banner)
 ├── Blog Pessoal (Secções Sobre Mim, Setup, Diário e Autores)
 ├── Detalhes dos Itens (Modais JS sobrepostos para cada projeto/beat)
 └── Contactos (Formulário e Google Maps)
```

## 4. Road-map para Produção
1. **Fase Atual:** HTML/CSS/JS estático para avaliação de ITW (1 Semana).
2. **Apresentação ao Professor:** Vou demonstrar como implementei as bibliotecas `AOS.js` e `VanillaTilt.js` para ir além do básico, criando uma experiência verdadeiramente cinemática.

## 5. Proposta de Orçamento
Caso este projeto fosse desenvolvido para um cliente real de produção musical:
- **Design e UI/UX (Landing Page Moderna):** 300€
- **Desenvolvimento Front-end (HTML/CSS/JS):** 450€
- **Integração de Multimédia (Áudio, Vídeo, Maps):** 100€
- **Total Estimado:** 850€
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
