# Projeto 60 Dias — Aula 01

**Data:** 15/09/2026  
**Foco:** Revisão e consolidação de HTML, CSS e responsividade

## Objetivo da aula

Reforçar a base de Front-end antes de avançar para JavaScript, revisando estrutura, layout e responsividade com exemplos aplicados à Mobi Systems.

## Conteúdos revisados

### HTML
- `header`
- `nav`
- `main`
- `section`
- `div`
- `class`
- `id`
- `h2` e `h3`
- `p`

### CSS
- `display: flex`
- `display: grid`
- `gap`
- `padding`
- `margin`
- `grid-template-columns`
- unidade `fr`
- `@media`
- `max-width`
- `width: 100%`
- `box-sizing: border-box`
- `justify-content`
- `align-items`
- `flex-wrap`
- `border-radius`
- `transition`
- `transform`
- `translateX()`
- `translateY()`
- `:hover`

## Prática realizada

Foi praticada a criação de cards para serviços da Mobi Systems usando Flexbox e Grid, incluindo responsividade e efeito de hover.

Exemplo:

```css
.cards {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
}

.card {
    width: 100%;
    max-width: 300px;
    padding: 20px;
    border-radius: 12px;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-6px);
}
```

## Git e GitHub revisados

Comandos reforçados:

```bash
git status
git add .
git commit -m "mensagem do commit"
git push
```

Também foi revisada a função do `README.md` como apresentação e registro da evolução do projeto.

## Resultado

Base de HTML e CSS revisada e pronta para início de JavaScript.

**Status:** ✅ Aula concluída
