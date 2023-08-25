# Input type="number" - inputmode = "numeric"

Không sử dụng input type="number" cho các field số quan trọng như số thẻ tín dụng, mã bưu điện

Tại sao:

- Hiển thị spinner không mong muốn trên desktop
- Số trong input có thể bị thay đổi khi scroll chuột lên xuống.

```javascript
<label>
  Card number:
  <input inputmode="numeric" pattern="[0-9*]">
</label>
```
