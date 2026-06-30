# Cumidava Website (Draft)

Site static de prezentare pentru brandul de bere **Cumidava**.

## Publicare cu GitHub Pages

1. Creezi repository-ul pe GitHub: `um01932/cumidava`.
2. Pui aceste fișiere pe branch-ul `main`.
3. În GitHub, mergi la **Settings -> Pages**.
4. La **Build and deployment**, selectezi:
   - **Source**: Deploy from a branch
   - **Branch**: `main` / `/ (root)`
5. Salvezi. În 1-3 minute site-ul devine activ.

## Domeniu custom (cumidava.com)

Fișierul `CNAME` este deja pregătit.

În providerul DNS (ROMARG), configurezi:

- Record `A` pentru `@` către:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`
- Record `CNAME` pentru `www` către:
  - `um01932.github.io`

Apoi, în GitHub Pages, la **Custom domain**, setezi `cumidava.com`.

## Notă

Poți adăuga poze în folderul `assets/` și actualiza secțiunile din `index.html`.
