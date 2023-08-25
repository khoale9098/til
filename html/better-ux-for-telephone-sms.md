# UX cho telephone/sms number

Call:

```javascript
<a href="tel:+84-337-111-110">+84-337-111-110</a>
// Có thể viết +84337111110, nhưng "-", ".", "("and")" sẽ tốt hơn cho readable format
```

SMS:

```javascript
<a href="sms:+84-337-111-110">+84-337-111-110</a>
```

SMS With Pre-filled Text(Android):

```javascript
<a href="sms:+84-337-111-110?body=CODE2022">+84-337-111-110</a>
```

SMS With Pre-filled Text(IOS):

```javascript
<a href="sms:+84-337-111-110&body=CODE2022">+84-337-111-110</a>
```
