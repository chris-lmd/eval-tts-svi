# Évaluation TTS pour SVI

Notebook Google Colab pour évaluer la qualité des voix françaises **Kokoro TTS** et **Piper TTS** sur des phrases types de SVI téléphonique.

## Utilisation

1. Ouvrir le notebook dans Google Colab :

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chris-lmd/eval-tts-svi/blob/main/eval_tts_svi.ipynb)

2. Exécuter toutes les cellules (Runtime → Run all)
3. Écouter les échantillons générés directement dans le notebook
4. Télécharger les WAV si besoin

## Phrases évaluées

Les phrases types d'un SVI (accueil, relance, confirmation, transfert, au revoir) sont dans `phrases.txt`.

## Moteurs comparés

| Moteur | Params | GPU requis | Licence |
|--------|--------|-----------|---------|
| **Kokoro** | 82M | Oui (Colab GPU gratuit suffit) | Apache 2.0 |
| **Piper** | ~15M | Non (CPU) | MIT |