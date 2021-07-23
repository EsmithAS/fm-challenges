# Frontend Mentor - Stats preview card component solution

Esta es una solución para el desafío del [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Los desafíos de Frontend Mentor le ayudan a mejorar sus habilidades de codificación mediante la creación de proyectos realistas. 


## Visión general

### Reto

Los usuarios deben ser capaces de:

- Ver el diseño óptimo en función del tamaño de pantalla de su dispositivo

### Captura de resultado

![](./images/result-desktop.jpeg)


### Enlaces

- [URL Solución](https://www.frontendmentor.io/solutions/stats-preview-card-component-3OzThv6t_)
- [URL del sitio en vivo](https://fm-statspreviewcardcomponent.netlify.app/)

## Mi proceso

### Construido con

- Semantic HTML5 markup
- CSS custom properties

### Lo que aprendí

De este reto aprendí el uso de una nueva propieda de CSS "mix-blend-mode", que use para mezclar la imagen con el color fondo, que sin duda asemeja más al resultado del reto. 

```html
<div class="card__img">
</div>
```
```css
.card__img::before {
    mix-blend-mode: multiply;
}
```

## Autor

- Website - [Esmith Sánchez](https://esmithas.github.io/)
- Frontend Mentor - [@EsmithAS](https://www.frontendmentor.io/profile/EsmithAS)