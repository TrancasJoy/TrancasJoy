Coloque suas imagens (fotos do trabalho) dentro desta pasta. Nomes recomendados:

- `assets/images/logo.png` — logotipo principal (uso no header)
- `assets/images/favicon.png` — favicon (32x32 PNG)
- `assets/images/style-1.jpg`, `style-2.jpg`, `style-3.jpg`, `style-4.jpg` — imagens dos estilos
- `assets/images/gallery-1.jpg` ... `gallery-4.jpg` — imagens da galeria

Atualize os paths em `index.html` se quiser usar nomes diferentes. Se você enviar as imagens eu posso renomear/otimizar e commitar para você.

Se você quiser renomear a imagem que adicionou para `logo.png` e criar um favicon no macOS rapidamente, rode:

```bash
# renomear (substitua o nome conforme o arquivo que você carregou)
mv assets/658998874_18079584008123967_4486846582028114592_n.jpg assets/images/logo.png

# criar favicon 32x32
mkdir -p assets/images
sips -Z 32 assets/images/logo.png --out assets/images/favicon.png
```

Depois faça commit e push para atualizar o site.
