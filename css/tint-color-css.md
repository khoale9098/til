# Tint color CSS

```css
.svg-icon {
  width: 48px;
  height: 48px;
  margin: 24px;
  /* for chromium based browsers */
  -webkit-mask: url("/images/icon.svg") center / contain no-repeat;
  mask: url("/images/icon.svg") center / contain no-repeat;

  background-color: red;
}

.svg-icon.blue {
  background: blue;
}
```
