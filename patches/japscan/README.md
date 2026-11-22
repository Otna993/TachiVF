# Japscan

Base Keiyoushi synchronisée, patch appliqué avant compilation.
`0001-native-reader.patch` : URL des images décodées directement, sans capture WebView ni lots de pages.
Le lecteur Keiyoushi passe par la WebView pour produire les images. Avec le patch, le captcha reste à résoudre manuellement dans la WebView quand le site le demande.
La synchronisation vérifie le patch avant d’envoyer les changements sur `main`. Version Keiyoushi + 3.
