# 🚀 GUIA RÁPIDO - 5 MINUTOS

## 📱 1. HOSPEDAR O APP (30 segundos)

### Netlify (MAIS FÁCIL):
1. Acesse: https://netlify.com
2. Arraste a pasta `escala-app-completo`
3. **PRONTO!** ✅

URL gerada: `https://seu-app.netlify.app`

---

## 🎨 2. CRIAR ÍCONES (2 minutos)

### Opção A - Automático:
1. Acesse: https://icon.kitchen
2. Upload emoji 📅 ou imagem
3. Baixe ícones 192x192 e 512x512
4. Renomeie para `icon-192.png` e `icon-512.png`
5. Faça upload no Netlify

### Opção B - Canva:
1. Crie imagens 192x192 e 512x512
2. Fundo azul (#3b82f6) + emoji 📅
3. Salve como PNG

---

## ⚙️ 3. CONFIGURAR GOOGLE SHEETS (Opcional)

1. Abra seu Google Sheets
2. **Extensões** > **Apps Script**
3. Cole código de `google-apps-script.js`
4. **Implantar** > **Nova implantação**
5. Tipo: **Aplicativo da Web**
6. Copie URL

7. No arquivo `app.js` (linha ~192):
```javascript
const API_URL = "COLE_URL_AQUI";
```

8. Faça novo upload no Netlify

---

## 📱 4. INSTALAR NO CELULAR

### Android:
1. Abra URL no Chrome
2. Menu ⋮ > **Instalar app**
3. ✅ Pronto!

### iPhone:
1. Abra URL no Safari
2. Compartilhar 📤 > **Adicionar à Tela de Início**
3. ✅ Pronto!

---

## ✅ CHECKLIST

- [ ] App hospedado no Netlify
- [ ] Ícones criados e enviados
- [ ] Google Sheets configurado (opcional)
- [ ] Testado instalação no celular
- [ ] Funciona offline

---

## 🎉 PRONTO!

Seu sistema agora é um **APP PROFISSIONAL**!

**Tempo total: 5 minutos** ⏱️
