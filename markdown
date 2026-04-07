# Conceitos de Margin, Padding e Border

## Margin
- Espaço **externo** ao redor de um elemento.
- Afasta o elemento dos outros.
- Exemplo: `margin: 20px;`

## Padding
- Espaço **interno** entre o conteúdo e a borda do elemento.
- Aumenta a área de fundo sem alterar o tamanho da borda.
- Exemplo: `padding: 15px;`

## Border
- A borda que envolve o conteúdo + padding.
- Pode ter espessura, estilo e cor.
- Exemplo: `border: 2px solid black;`

---

### Diferenças principais
- **Margin**: espaço fora do elemento.  
- **Padding**: espaço dentro do elemento.  
- **Border**: linha que contorna o elemento.  

---

### Exemplos visuais
```css
div {
  margin: 20px;       /* espaço externo */
  padding: 15px;      /* espaço interno */
  border: 2px solid blue; /* borda */
}
