# Piupiu: Politique de confidentialité / Privacy Policy

*Dernière mise à jour / Last updated: 9 octobre 2026 / October 9, 2026 (v1.5)*

[Français](#français) · [English](#english)

---

## Français

Piupiu est une application Android gratuite qui affiche des informations sur les produits alimentaires et cosmétiques (nutrition, additifs, perturbateurs endocriniens, allergènes) et leurs prix, à partir de bases de données ouvertes. Elle est développée par Stéphane Martin-Richter, développeur indépendant (contact : stephanemartinrichter@gmail.com).

**En résumé : pas de compte, pas de publicité, pas de mesure d'audience, pas de pistage. Le développeur ne possède aucun serveur et ne reçoit aucune de vos données.**

### Données stockées sur votre téléphone
Votre panier en cours et l'historique des courses que vous validez (date, codes-barres, noms des produits, scores, additifs à risque, prix que vous saisissez, quantités) sont enregistrés uniquement dans le stockage privé de l'application sur votre téléphone. Les statistiques de l'onglet Historique et le bilan mensuel sont calculés sur le téléphone. Si vous enregistrez un bilan en PDF, le fichier est créé sur le téléphone, à l'endroit que vous choisissez, et n'est envoyé nulle part. Vous pouvez supprimer une course de l'historique à tout moment ; tout est effacé si vous videz les données de l'application ou la désinstallez. Si la sauvegarde Android est activée sur votre téléphone, ces données peuvent être incluses dans votre sauvegarde Google chiffrée, comme pour les autres applications.

### Données envoyées à des services tiers
Pour fonctionner, l'application interroge directement les services suivants via des connexions chiffrées (HTTPS). Comme pour toute connexion Internet, ces services voient l'adresse IP de votre téléphone.

| Service | Ce qui est envoyé | Quand |
|---|---|---|
| **Open Food Facts** (association à but non lucratif, France) | Le code-barres du produit | Quand vous scannez ou saisissez un produit |
| **Open Beauty Facts** (projet d'Open Food Facts) | Le code-barres du produit | Quand Open Food Facts ne connaît pas le produit (cosmétiques) |
| **Open Prices** (projet d'Open Food Facts) | Les codes-barres, la devise de votre pays | Quand vous scannez un produit, pour le prix moyen |
| **Open Prices** | Les codes-barres de votre panier et votre **position approximative, arrondie à environ 1 km** | Uniquement quand vous appuyez sur « Terminer » et avez autorisé la localisation |

Politique de confidentialité d'Open Food Facts (qui couvre aussi Open Beauty Facts) : https://world.openfoodfacts.org/privacy

### Services Google Play
- **Lecteur de codes-barres** : la caméra est gérée par le service de scan de Google Play (Google code scanner). Les images sont analysées sur votre téléphone ; Piupiu ne reçoit que le numéro du code-barres et n'a pas accès à la caméra. Google peut collecter des données techniques et de diagnostic : https://developers.google.com/ml-kit/terms
- **Lecture des photos** : si vous photographiez la liste d'ingrédients d'un cosmétique ou une étiquette de prix, la photo est prise par l'application appareil photo de votre téléphone et lue **sur le téléphone** par la reconnaissance de texte de Google Play (ML Kit). Elle n'est envoyée nulle part : Piupiu la garde dans son espace privé, sans l'ajouter à votre galerie, et la remplace par la photo suivante.
- **Localisation** : la position approximative est obtenue via les services de localisation de Google Play.

Politique de confidentialité de Google : https://policies.google.com/privacy

### Autorisations
- **Internet** : pour interroger Open Food Facts et Open Prices.
- **Position approximative** (facultative) : demandée uniquement quand vous appuyez sur « Terminer », pour trouver les magasins moins chers à proximité. Elle n'est jamais utilisée en arrière-plan ni conservée. Si vous refusez, l'application fonctionne normalement, sans comparaison de magasins.

L'application ne demande **pas** l'accès à la caméra (les photos passent par votre application appareil photo), à vos contacts, à vos fichiers ni à votre identité.

### Enfants
Piupiu s'adresse au grand public et ne collecte sciemment aucune donnée personnelle d'enfants.

### Vos droits
Le développeur ne détient aucune donnée vous concernant : il n'y a donc rien à consulter ni à supprimer de son côté. Pour les données traitées par Open Food Facts ou Google, adressez-vous à eux via les liens ci-dessus. Vous pouvez aussi déposer une réclamation auprès de la CNIL : https://www.cnil.fr/fr/plaintes

### Modifications
Toute modification de cette politique sera publiée sur cette page avec une nouvelle date de mise à jour.

### Contact
stephanemartinrichter@gmail.com

---

## English

Piupiu is a free Android app that shows information about food and beauty products (nutrition, additives, endocrine disruptors, allergens) and their prices, from open databases. It is developed by Stéphane Martin-Richter, an independent developer (contact: stephanemartinrichter@gmail.com).

**In short: no account, no ads, no analytics, no tracking. The developer runs no server and receives none of your data.**

### Data stored on your phone
Your current basket and the history of the shopping you validate (date, barcodes, product names, scores, high-risk additives, prices you enter, quantities) are saved only in the app's private storage on your phone. The statistics in the History tab and the monthly recap are computed on the phone. If you save a recap as a PDF, the file is created on the phone, where you choose, and is not sent anywhere. You can delete any shopping from the history at any time; everything is erased if you clear the app's data or uninstall it. If Android backup is turned on, this data may be included in your encrypted Google backup, as with other apps.

### Data sent to third-party services
To work, the app talks directly to the following services over encrypted connections (HTTPS). As with any internet connection, these services see your phone's IP address.

| Service | What is sent | When |
|---|---|---|
| **Open Food Facts** (non-profit association, France) | The product's barcode | When you scan or type a product |
| **Open Beauty Facts** (an Open Food Facts project) | The product's barcode | When Open Food Facts doesn't know the product (cosmetics) |
| **Open Prices** (an Open Food Facts project) | Barcodes, your country's currency | When you scan a product, for its average price |
| **Open Prices** | Your basket's barcodes and your **approximate location, rounded to about 1 km** | Only when you tap "Finish" and have allowed location |

Open Food Facts privacy policy (also covering Open Beauty Facts): https://world.openfoodfacts.org/privacy

### Google Play services
- **Barcode scanner**: the camera is handled by Google Play's scanning service (Google code scanner). Images are analysed on your phone; Piupiu only receives the barcode number and has no camera access. Google may collect technical and diagnostic data: https://developers.google.com/ml-kit/terms
- **Reading photos**: if you photograph a cosmetic's ingredient list or a price tag, the photo is taken by your phone's camera app and read **on the phone** by Google Play's text recognition (ML Kit). It is not sent anywhere: Piupiu keeps it in its private storage, without adding it to your gallery, and replaces it with the next one.
- **Location**: the approximate location comes from Google Play location services.

Google privacy policy: https://policies.google.com/privacy

### Permissions
- **Internet**: to query Open Food Facts and Open Prices.
- **Approximate location** (optional): requested only when you tap "Finish", to find cheaper stores nearby. It is never used in the background or stored. If you decline, the app works normally without the store comparison.

The app does **not** request access to your camera (photos go through your camera app), contacts, files or identity.

### Children
Piupiu is intended for a general audience and does not knowingly collect personal data from children.

### Your rights
The developer holds no data about you, so there is nothing to access or delete on their side. For data processed by Open Food Facts or Google, contact them through the links above. You can also lodge a complaint with the French data protection authority (CNIL): https://www.cnil.fr/fr/plaintes

### Changes
Any change to this policy will be published on this page with a new "last updated" date.

### Contact
stephanemartinrichter@gmail.com
