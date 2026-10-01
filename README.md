# ct-squarefont

Bộ 4 font ct-squarefont: `ct-squarefont`, `ct-squarefont-vn`, `ct-squarefont-outline`, `ct-squarefont-outline-vn`.

**Xem bảng ký tự bằng font thật:** https://t-root.github.io/ct-squarefont/

README trên GitHub không hiển thị được font tùy chỉnh, nên trang trên là nơi xem mẫu chữ và thử gõ trực tiếp.

## Tải font

- [ct-squarefont.ttf](ct-squarefont.ttf)
- [ct-squarefont-vn.ttf](ct-squarefont-vn.ttf)
- [ct-squarefont-outline.ttf](ct-squarefont-outline.ttf)
- [ct-squarefont-outline-vn.ttf](ct-squarefont-outline-vn.ttf)

## Dùng trong CSS

Mẫu cho cả 4 font:

```css
@font-face {
  font-family: "ct-squarefont";
  src: url("https://t-root.github.io/ct-squarefont/ct-squarefont.ttf") format("truetype");
  font-display: swap;
}

@font-face {
  font-family: "ct-squarefont-vn";
  src: url("https://t-root.github.io/ct-squarefont/ct-squarefont-vn.ttf") format("truetype");
  font-display: swap;
}

@font-face {
  font-family: "ct-squarefont-outline";
  src: url("https://t-root.github.io/ct-squarefont/ct-squarefont-outline.ttf") format("truetype");
  font-display: swap;
}

@font-face {
  font-family: "ct-squarefont-outline-vn";
  src: url("https://t-root.github.io/ct-squarefont/ct-squarefont-outline-vn.ttf") format("truetype");
  font-display: swap;
}

/* Chữ không dấu */
.title { font-family: "ct-squarefont", sans-serif; }
.title-outline { font-family: "ct-squarefont-outline", sans-serif; }

/* Chữ tiếng Việt: dùng bản -vn */
.title-vn { font-family: "ct-squarefont-vn", sans-serif; }
.title-outline-vn { font-family: "ct-squarefont-outline-vn", sans-serif; }
```
