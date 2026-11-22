# Documenso aux couleurs d'Alphard Law

Branche `alphard` : Documenso v2.22.0 (AGPL-3.0), modifié pour l'instance de signature du cabinet Alphard Law (sign.alphard.law). Ces sources sont publiées en application de la licence AGPL-3.0.

Modifications, toutes visuelles :

- `packages/ui/styles/theme.css` : couleurs de la charte (corail et marine), angles réduits ;
- `apps/remix/app/components/general/branding-logo.tsx`, `branding-logo-icon.tsx` : logo et icône du cabinet ;
- `apps/remix/app/utils/meta.ts` : titres d'onglet et description ;
- `apps/remix/public/` : icônes (favicon) et manifeste.

Aucune modification du fonctionnement, de la sécurité ou des données. Construction : `docker build -f docker/Dockerfile .`
