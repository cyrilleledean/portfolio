# Site documentation side-projects (Hugo - Thème Doks)

## Création du site
```
git clone https://github.com/h-enk/doks.git portfolio
cd portfolio
npm run dev
```

## Délier du repo source

```powershell
# Création repo https://github.com/cyrilleledean/portfolio
git remote remove origin
git remote add origin https://github.com/cyrilleledean/portfolio.git
git branch -M main
git add .
git commit -m "Initial commit - site basé sur Doks"
git push -u origin main
```

## Doks

[Documentation](https://getdoks.org/).

## Déploiement GitHub pages

- Modifier config/_default/config.toml

```
baseurl = "https://github.com/cyrilleledean/portfolio/"
```

- Ajouter le fichier .github/workflows/deploy.yml
