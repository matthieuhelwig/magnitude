
   * Quand tu fais des modifications dans `content/`, exécute :

cd /d "P:\08-SHARE\Magnitude

- Puis

     ```bash
     npx quartz sync
     git add .
     git commit -m "Ajout ou modification de notes"
     git push origin main
     ```
   * Cela déclenchera un nouveau déploiement automatique sur Cloudflare.

3. **🌍 (Optionnel) Ajoute un baseUrl dans `quartz.config.ts`**
   Exemple :

   ```ts
   export const siteConfig = {
     baseUrl: "https://magnitude.<ton-sous-domaine>.pages.dev"
   }
   ```

4. **💡 Personnalise le style et les layouts si tu veux aller plus loin**
   Tu peux éditer les fichiers dans `quartz/layouts` pour adapter ton thème ou ajouter un logo.

