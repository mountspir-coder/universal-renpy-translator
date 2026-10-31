# Universal RenPy Translator

**Lire dans d'autres langues :** [English](README.md) | [Русский](README.ru.md) | [简体中文](README.zh.md) | [Español](README.es.md) | **Français** | [日本語](README.ja.md) | [العربية](README.ar.md)

Universal RenPy Translator est une puissante application de bureau multiplateforme conçue pour la traduction hors ligne des romans visuels Ren'Py. Elle utilise des modèles d'IA locaux via **Ollama** pour offrir des traductions de haute qualité et non censurées, sans jamais envoyer votre texte à des serveurs tiers.

Ce dépôt est destiné aux versions compilées. Le code source est fermé.

---

## ✨ Fonctionnalités

- **100% Hors ligne et illimité :** Aucune clé API requise, aucune limite de caractères. Vos textes ne quittent jamais votre ordinateur et la traduction ne sera jamais interrompue par des erreurs de serveur.
- **Traduction 18+ non censurée :** Utilise le modèle `HY-MT1.5 7B Abliterated` et un glossaire d'obscénités intégré pour préserver le ton original, l'argot et le contenu pour adultes sans adoucissement artificiel.
- **Injection d'overlay en jeu :** Injecte un sélecteur de langue flottant directement dans le jeu, permettant de basculer de manière transparente entre le texte original et le texte traduit.
- **Tout-en-un et configuration en 2 clics :** Décompresse automatiquement les archives RPA, décompile les fichiers `.rpyc` et vous permet de lancer le jeu traduit directement depuis l'application.
- **Large prise en charge de Ren'Py :** Fonctionne parfaitement avec les moteurs Ren'Py 6, 7 et 8+.
- **Détection de la langue source :** Détecte automatiquement la langue des fichiers de jeu originaux pour éviter les erreurs de traduction.
- **Contrôle de la taille de la police en jeu :** Ajuste dynamiquement la taille du texte dans le jeu pour s'adapter à n'importe quelle interface.
- **Contexte intelligent (CTX) :** Transmet les lignes de dialogue précédentes à l'IA pour maintenir la cohérence narrative et l'utilisation correcte des pronoms.
- **Traduction incrémentielle (Diff) :** Met à jour les traductions pour les nouveaux chapitres du jeu sans avoir à retraduire tout le jeu depuis le début.
- **Détection du genre des personnages :** Détecte automatiquement le genre du locuteur pour appliquer les formes grammaticales correctes (crucial pour le russe et les autres langues genrées).
- **Vérificateur QA intégré :** Scanne automatiquement le fichier traduit pour détecter les balises perdues, les crochets non équilibrés et les chaînes trop longues.
- **Éditeur CAT :** Un éditeur visuel sous forme de tableau pour modifier manuellement les traductions et corriger les problèmes de QA directement dans l'application.
- **7 langues d'interface :** Anglais, Russe, Espagnol, Français, Japonais, Chinois et Arabe.

---

## 📸 Captures d'écran

![Fenêtre principale](https://github.com/user-attachments/assets/169a495d-505f-4237-844e-37133f64a318)
*Interface principale avec le bloc de soutien et les paramètres*

![Traduction en cours](https://github.com/user-attachments/assets/2cbad0d2-4e1c-4f45-a9f9-a846721a9e87)
*Processus de traduction avec journaux en temps réel*

![Vérificateur QA](https://github.com/user-attachments/assets/3f58ad44-e38b-4648-809c-026ab6c7d039)
*Inspecteur QA intégré*

![Éditeur CAT](https://github.com/user-attachments/assets/896f6ab1-944b-42cf-a229-6397a9c942e6)
*Éditeur CAT pour les ajustements manuels de traduction*

![Bouton Overlay en jeu](https://github.com/user-attachments/assets/f943b7f8-7417-4022-9f43-c65a79f5b052)
*Bouton de sélection de la langue en jeu*

![Menu Overlay en jeu](https://github.com/user-attachments/assets/d0a4fefe-febe-4a96-ab3d-d24e17445c38)
*Menu de sélection de la langue et de la taille de police en jeu*

---

## 📥 Téléchargement et installation

1. Rendez-vous dans la section **[Releases](../../releases/latest)** sur le côté droit de cette page.
2. Téléchargez le dernier fichier `Universal-RenPy-Translator.zip`.
3. Extrayez l'archive dans n'importe quel dossier de votre PC (ne lancez pas le `.exe` directement depuis l'archive).
4. Lancez `Universal RenPy Translator.exe`.

### Prérequis
Vous devez avoir **Ollama** installé et en cours d'exécution sur votre ordinateur.
1. Téléchargez et installez Ollama depuis [ollama.com](https://ollama.com).
2. Lors du premier lancement, le programme vous invitera à télécharger le modèle d'IA requis (`huihui_ai/hy-mt1.5-abliterated:7b`).

---

## ⚠️ Important : Faux positifs des antivirus

Étant donné que cette application est compilée avec PyInstaller et **ne dispose pas de signature numérique payante**, Windows Defender et certains antivirus peuvent afficher un faux positif (par exemple, "Trojan:Win32/Wacatac" ou "Wacapew").

**Il s'agit d'un problème connu pour tous les exécutables basés sur Python.** L'application est totalement sûre et ne contient aucun code malveillant.

**Comment résoudre le problème :**
1. Autorisez le fichier dans votre antivirus (ajoutez le dossier aux exclusions).
2. Si vous utilisez Windows Defender, vous pouvez soumettre le fichier à Microsoft en tant que faux positif. Habituellement, ils le corrigent dans les 24 heures.

---

## 💖 Soutenir le projet

Universal RenPy Translator est entièrement gratuit et ouvert à tous. Si vous le trouvez utile et souhaitez soutenir le développement futur, vous pouvez le faire ici :

- **[Boosty](https://boosty.to/universal_renpy_translator)**
- **[DonationAlerts](https://www.donationalerts.com/r/urtranslator)**
- **Crypto (USDT TRC-20) :** [TTL4jWvaS21qEKur1i92Tv7G3h1LWbARTQ](https://link.trustwallet.com/send?asset=c195_tTR7NHqjeKQxGTCi8q8ZY4pL8otSzgjLj6t&address=TTL4jWvaS21qEKur1i92Tv7G3h1LWbARTQ)

Merci pour votre soutien ! ❤️

---

## 📄 Licence et crédits

- Le modèle de traduction **HY-MT1.5 7B Abliterated** est développé par Tencent Hunyuan Team sous la licence open source Hunyuan v1.0.
- Ce produit inclut des modèles développés par Tencent Hunyuan Team.
- Licence : [https://hunyuan.tencent.com/license](https://hunyuan.tencent.com/license)
- Ren'Py est une marque déposée de Tom Rothamel. Cette application n'est pas affiliée à l'équipe officielle de Ren'Py.
