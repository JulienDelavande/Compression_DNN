<a target="_blank" href="https://colab.research.google.com/github/JulienDelavande/Compression_DNN/blob/main/Compression_de_r%C3%A9seaux_de_neurones_profonds.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

# Compression de Réseaux de Neurones Profonds

Ce repository contient un notebook rédigé dans le cadre du module de Deep Learning de la dernière année à l'ISAE-Supaero. Il a été conçu pour servir de référence et d'exemple aux autres élèves de la filière, expliquant et démontrant plusieurs techniques de compression des réseaux de neurones profonds.

## Table des matières

0. [Introduction](#introduction)
1. [Test et entraînement du modèle](#1-test-et-entrainement-du-modèle)
2. [Élagage (Pruning)](#2-élagage-pruning)
3. [Quantification par partage de poids](#3-quantification-par-partage-de-poids)
4. [Codage Huffman](#4-codage-huffman)
5. [Nouvelles perspectives de compression](#5-nouvelles-perspectives-de-compression)
6. [Conclusion](#6-conclusion)

## 0. Introduction

Dans cette section, nous présentons le contexte et les objectifs de la compression des réseaux de neurones profonds.

## 1. Test et entraînement du modèle

Cette section couvre le processus de test et d'entraînement initial du modèle de réseau de neurones avant d'appliquer les techniques de compression.

## 2. Élagage (Pruning)

L'élagage (pruning) est une technique de compression qui consiste à supprimer les poids les moins significatifs du réseau de neurones pour réduire sa taille tout en maintenant des performances acceptables.

## 3. Quantification par partage de poids

La quantification par partage de poids vise à réduire la taille du modèle en limitant le nombre de valeurs distinctes que les poids peuvent prendre, en les regroupant par plages de valeurs proches.

## 4. Codage Huffman

Le codage Huffman est une technique de compression sans perte qui peut être appliquée aux poids des réseaux de neurones pour réduire encore leur taille.

## 5. Nouvelles perspectives de compression

Dans cette section, nous explorons les techniques avancées et émergentes pour la compression des réseaux de neurones profonds, telles que la distillation des connaissances, l'utilisation de GAN, la quantification dynamique, le codage tensoriel et les réseaux sparsifiés dynamiques.

## 6. Conclusion

Nous récapitulons les principales techniques de compression abordées et discutons de leur impact et de leur applicabilité dans divers scénarios.

## Comment utiliser ce notebook

1. **Cloner le repository :**
   ```bash
   git clone https://github.com/votre-utilisateur/compression-de-reseaux-de-neurones-profonds.git
   cd compression-de-reseaux-de-neurones-profonds
   ```

2. **Installer les dépendances :**
   Assurez-vous d'avoir Python et pip installés, puis exécutez :
   ```bash
   pip install -r requirements.txt
   ```

3. **Exécuter le notebook :**
   Lancez Jupyter Notebook ou Jupyter Lab :
   ```bash
   jupyter notebook
   ```
   Ouvrez `compression_de_reseaux_de_neurones_profonds.ipynb` pour explorer les différentes techniques de compression.

**Alternativement, vous pouvez exécuter le notebook dans Google Colab**


## Contributions

Les contributions sont les bienvenues ! Si vous avez des suggestions, des améliorations ou des corrections, n'hésitez pas à soumettre une pull request.

## License

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.
