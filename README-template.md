# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).

### Screenshot

![Alt Text](./images/testimonials-grid.png)

### Links

- Github: (https://github.com/AmakaEguzoro/testimonial-grid)

## My process

### Built with

- HTML5
- SASS

### What I learned

```css
.wrapper {
  max-width: 1400px;
  padding: 6.5rem;
  margin-bottom: 1.3rem;
  margin-left: auto;
  margin-right: auto;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: auto;
  grid-template-areas:
    "purple purple grey white-tall"
    "purple purple grey white-tall"
    "white black black white-tall";
  gap: 20px;
  height: auto;
  background-color: var(--light-grayish-blue);
}
```
