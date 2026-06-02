# Aprovação de Protótipo / Proposta

**Tema:** Blog Pessoal
**Cliente:** (Professor / Entidade Avaliadora)
**Data:** 02 de Junho de 2026

---

## 1. Decisões de Design
O protótipo do **Blog Pessoal** foi desenvolvido usando as matérias ensinadas na cadeira de Interfaces e Tecnologias Web.

- **Layout e Responsividade:** Utilizou-se CSS nativo com **Flexbox** e **CSS Grid** para organizar os conteúdos. O site foi todo estruturado numa única página ("Single Page Application") usando IDs e links internos de âncora para navegar sem recarregar a página. O esquema de cores é um Dark Theme que implementei com variáveis de CSS (`:root`).
- **Identidade Visual e Copywriting:** Como foi pedido um "Blog Pessoal", escrevi os textos de forma genuína sobre a minha experiência em LEI e a conciliação com a música, dividindo as secções por "Setup", "Diário de Bordo" e a minha parceira.
- **Interatividade (Os Modais):** Para cumprir a exigência do enunciado (Listagem de Itens e Detalhe do Item), em vez de criar várias páginas `.html` separadas que são confusas, criei um sistema de Pop-ups (Modais) com Javascript base. Usei o simples `document.getElementById('modal').style.display = 'block'` que aprendemos nas teóricas, sem precisar de bibliotecas pesadas do mercado.

## 2. Benefícios do Protótipo
- **Velocidade:** Sem plugins pesados, o CSS e JS carregam instantaneamente.
- **Fácil Manutenção:** O CSS está organizado em secções (`header`, `section-wrapper`, `caixa-escura`), facilitando a leitura para o professor corrigir.

## 3. Road-map para Produção
1. **Fase Atual:** HTML/CSS/JS estático para avaliação de ITW.
2. **Apresentação ao Professor:** Vou demonstrar como usei CSS Grid na grelha de projetos e Flexbox na navbar. Vou destacar que os Modais resolvem o problema dos detalhes do item usando apenas manipulação de DOM básica de 1º ano.
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
