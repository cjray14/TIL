```javascript
export default function init ({ el, context }) {
  const colourButton = context.getElement(`.${context.className}_Button`)

  colourButton.addEventListener('click', e => {
    e.preventDefault()

    el.classList.toggle('prd-ProductVariants-active')
  })
}
```
