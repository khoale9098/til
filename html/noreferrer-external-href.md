# a tag rel="noreferrer" for external links

- Set rel="noreferrer" for all the external links on sensitive pages of a website

```javascript
<a href="https://fb.com/khoale.stand.up" target="_blank" rel="noreferrer">
  Facebook
</a>
```

Why:

- For security purposes because URL of the webpage, from where the external link is opened, is by default passed in the Referrer request header.
- ref="noreferrer" also automatically sets window.opener is null, which helps in preventing security and performance issues in legacy browsers.
