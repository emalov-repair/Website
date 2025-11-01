# Emalov Repair - GitHub Pages

Profesionalna landing page za Emalov Repair - servis za popravku računara i mobilnih telefona u Frankfurtu.

## 🚀 Deployment na GitHub Pages

### Korak 1: Kreiraj GitHub Repository

1. Idi na [GitHub](https://github.com) i uloguj se
2. Klikni na "New Repository" (zeleno dugme gore desno)
3. Imenuj repository (npr. `emalov-repair`)
4. Ostavi ga **PUBLIC** (mora biti public za besplatan GitHub Pages)
5. Klikni "Create repository"

### Korak 2: Upload Fajlova

**Opcija A: Preko Web Interface (najlakše)**

1. U svom novom repository-ju, klikni "uploading an existing file"
2. Prevuci sve fajlove iz `/github-pages/` foldera:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`
3. Klikni "Commit changes"

**Opcija B: Preko Git (ako znaš Git)**

```bash
# U folderu github-pages
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TVOJE-USERNAME/emalov-repair.git
git push -u origin main
```

### Korak 3: Aktiviraj GitHub Pages

1. U repository-ju, idi na **Settings** (zupčanik)
2. U lijevom meniju klikni **Pages**
3. Pod "Source", izaberi **main** branch
4. Klikni **Save**
5. Sačekaj 1-2 minuta

### Korak 4: Pristup Sajtu

Tvoj sajt će biti dostupan na:
```
https://TVOJE-USERNAME.github.io/emalov-repair/
```

## 📱 Custom Domena (Opcionalno)

Ako želiš da koristiš `emalov.repair` domenu:

1. Kupi domenu (npr. na Namecheap, GoDaddy)
2. U DNS postavkama dodaj:
   - Type: `A` Record
   - Host: `@`
   - Value: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   
   I također:
   - Type: `CNAME` Record
   - Host: `www`
   - Value: `TVOJE-USERNAME.github.io`

3. U GitHub repository Settings > Pages, dodaj custom domain: `emalov.repair`
4. Čekaj 24-48h za DNS propagaciju

## ✨ Features

- ✅ **100% Besplatno** - GitHub Pages je potpuno besplatan
- ✅ **HTTPS** - Automatski SSL sertifikat
- ✅ **Brzo** - Optimizovana statička stranica
- ✅ **Responzivno** - Radi na svim uređajima
- ✅ **SEO** - Meta tagovi za pretraživače

## 📝 Izmjene Sadržaja

Sve izmjene radiš direktno u `index.html` fajlu:

1. Otvori `index.html` u text editoru
2. Promijeni tekst, brojeve telefona, email, itd.
3. Sačuvaj fajl
4. Upload nazad na GitHub (preko web interface ili Git)
5. Stranica se automatski ažurira za 1-2 minuta

## 🎨 Izmjene Dizajna

Sve CSS stilove možeš mijenjati u `styles.css`:

```css
:root {
  --primary: #2563eb;  /* Glavna boja */
  --green: #22c55e;    /* Boja dugmeta */
}
```

## 🔧 Tehnologije

- HTML5
- CSS3
- Vanilla JavaScript
- [Lucide Icons](https://lucide.dev)

## 💰 Troškovi

- GitHub Pages: **€0/mjesečno**
- Custom domena (opcionalno): **~€10/godišnje**

Ukupno: **Praktično besplatno!** 🎉

## 📞 Kontakt

Emanuel Lovnicki
- WhatsApp: +49 152 28775693
- Email: info@emalov.repair
- Lokacija: Frankfurt am Main, Deutschland
