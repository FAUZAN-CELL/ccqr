# qr
## QR Code Scanner for Login Hotspot MikroTik

### Cara pakai

1. Tambahkan button di login.html
```html
<button onclick="window.location='https://fauzan-cell.github.io/qr';">QR Code</button>
```
2. Tambahkan script berikut di MikroTik via Terminal.
```
/ip hotspot walled-garden ip

add action=accept comment="QR Code Scanner | FAUZAN-CELL" disabled=no dst-host=fauzan-cell.github.io
```

### Powered by FAUZAN-CELL
