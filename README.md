# qr
## Pemindai kode QR untuk Masuk Hotspot MikroTik

### Cara pakai

1. Tambahkan button di login.html
```html
<button onclick="window.location='https://fauzan-cell.github.io/qr';">Kode QR</button>
```
2. Tambahkan script berikut di MikroTik via Terminal.
```
/ip hotspot walled-garden ip

add action=accept comment="Pemindai kode QR" disabled=no dst-host=fauzan-cell.github.io
```

### Powered by FAUZAN-CELL
