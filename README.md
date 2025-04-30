# 📚 Agent de Lecture PDF (FR)

Un assistant IA en français qui lit des documents PDF et répond à vos questions à partir de leur contenu.  
Ce projet utilise le modèle **CamemBERT** finement ajusté sur des données QA francophones (FQuAD / PIAF).

---

## 🚀 Fonctionnalités

- 💬 Posez une question en français sur le contenu d'un fichier PDF.
- 📄 Analyse automatique du texte contenu dans le document.
- 🤖 Réponses générées à l’aide du modèle `etalab-ia/camembert-base-squadFR-fquad-piaf`.
- 📊 Score de confiance affiché pour chaque réponse.
- 📜 Affichage des **extraits complets** ayant servi à produire les réponses.
- ⬇️ Export automatique des extraits dans un **fichier .txt téléchargeable**, nommé dynamiquement.

## 🧠 Exemple d'utilisation

Chargez un fichier PDF en français.
- Posez une question comme :
- "Quel est l'impact du plastique sur l’environnement ?"
- L'application retourne :
-La meilleure réponse
- Le score de confiance
- Les extraits complets utilisés
- Un fichier .txt téléchargeable avec les extraits

## 📦 Modèle utilisé

Nom : etalab-ia/camembert-base-squadFR-fquad-piaf
Base : CamemBERT
Sources d'entraînement : SQuAD v1, FQuAD, PIAF (QA francophones)

