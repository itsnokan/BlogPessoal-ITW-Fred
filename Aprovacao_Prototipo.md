# Aprovação de Protótipo / Proposta

**Tema:** Blog Pessoal
**Cliente:** (Professor / Entidade Avaliadora)
**Data:** 02 de Junho de 2026

---

## 1. Decisões de Design
O protótipo do **Blog Pessoal** foi desenvolvido focando na usabilidade, clareza e numa estética moderna, respeitando todas as diretrizes da Unidade Curricular de Interfaces e Tecnologias Web. 

- **Layout e Responsividade:** Utilizou-se CSS nativo com *Flexbox* e *CSS Grid*. Para elevar o nível visual, foram introduzidos conceitos de **Glassmorphism** (efeitos de vidro translúcido no cabeçalho) e **Neumorfismo** (sombras suaves dinâmicas), garantindo um design verdadeiramente *Premium*. Tudo feito com código CSS limpo, ideal para um aluno de 1º ano explicar.
- **Tipografia e Cores:** Foi selecionada a fonte *Inter* e *Georgia*. O esquema de cores em tons de terra (castanhos, bege e creme) transmite serenidade.
- **Identidade Visual e Marca (IA):** Foi criada uma marca própria "Fred Daniel" com imagens exclusivas (geradas via Inteligência Artificial) que misturam o ambiente de estúdio de um Beatmaker com a estética Cristã, dispensando fotos de stock genéricas.
- **Navegação:** Menu *sticky* com *Glassmorphism* que se mantém elegante enquanto faz scroll. O rodapé contém as ligações para as redes sociais através de ícones FontAwesome.
- **Multimédia:** Foram estrategicamente colocados elementos de áudio e vídeo (YouTube) para aumentar o tempo de retenção do utilizador e tornar a experiência mais interativa.

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
3. **Fase 3: Funcionalidades Dinâmicas** - Ativação real do formulário de contactos via envio de email (PHP/Node.js) e otimização de SEO (Search Engine Optimization). (Prazo: 1 Semana)
4. **Fase 4: Testes Finais e Lançamento** - Publicação no servidor web final, configuração de domínio e testes de segurança. (Prazo: 1 Semana)
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
