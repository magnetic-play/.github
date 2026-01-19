## Hello les BG 👋

Bienvenue chez les geeks Magnetic !

### Packages NPM privés

Pour les utiliser :

1. Créer un token GitHub  
   - Aller sur [Settings / Developper / Tokens](https://github.com/settings/tokens)
   - Générer un token classique avec droits de download des packages (`read:packages`)

2. Ajouter à `~/.npmrc` (cf. [doc](https://docs.github.com/fr/packages/working-with-a-github-packages-registry/working-with-the-npm-registry))

   ```
   @magnetic-play:registry=https://npm.pkg.github.com
   //npm.pkg.github.com/:_authToken={TOKEN}
    ```

Ça permet de résoudre les `pnpm install @magnetic-play/XXX`

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
