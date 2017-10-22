## why

https://www.webcomponents.org/search/date

moment.js – all of them. Let's be leaner
- https://www.webcomponents.org/element/RoXuS/range-datepicker
- https://www.webcomponents.org/element/bendavis78/paper-date-picker

maybe not in vaadin - take a closers look: https://github.com/vaadin/vaadin-date-picker

## todos

- end is always past start even if user goes leftwards
- headers with nice arrows for going backward and forward
- cancel and apply buttons
- disable all before/after (pass function)
- responsive: `flex-direction: column;`

## good to haves

- render to custom elements when [issue resolved](https://github.com/sveltejs/svelte/issues/875)

```html
<cntdys-calendar year="2017" month="10" day="01"></cntdys-calendar>
```

## usage

Don't use `bundle.css` and define all styles yourself!
