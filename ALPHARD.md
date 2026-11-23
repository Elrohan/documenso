# Documenso aux couleurs d'Alphard Law

Branche `alphard` : Documenso v2.22.0 (AGPL-3.0), modifié pour l'instance de signature du cabinet Alphard Law (sign.alphard.law). Ces sources sont publiées en application de la licence AGPL-3.0.

Modifications, toutes visuelles ou de libellé :

- `packages/ui/styles/theme.css` : couleurs de la charte (corail et marine), angles réduits ;
- `apps/remix/app/components/general/branding-logo.tsx`, `branding-logo-icon.tsx` : logo et icône du cabinet ;
- `apps/remix/app/utils/meta.ts` : titres d'onglet et description ;
- `apps/remix/public/` : icônes (favicon) et manifeste ;
- `packages/lib/translations/{fr,en}/web.po` : titre d'onglet de la page de signature.
- `apps/remix/app/routes/_recipient+/sign.$token+/complete.tsx` : bouton « Partager » retiré de la page de confirmation du signataire.
- Nom du service « Alphard Sign » (23 novembre 2026) : dans `packages/lib/translations/{fr,en}/web.po`, « Documenso » remplacé par « Alphard Sign » dans les textes affichés (identifiants de message inchangés) ; pied des mails sans l'adresse de Documenso, Inc. (`packages/email/template-components/template-footer.tsx`) ; invitation « Check out Documenso » retirée de la page d'un document annulé (`sign.$token+/_index.tsx`) ; textes de remplacement des images et logo des mails (`static/logo.png`) aux couleurs du cabinet.
- `apps/remix/app/routes/_recipient+/_layout.tsx` : lien « Code source » vers cette branche au bas des pages du destinataire (AGPL-3.0, article 13).

Aucune modification du fonctionnement, de la sécurité ou des données. Construction : `docker build -f docker/Dockerfile .`
