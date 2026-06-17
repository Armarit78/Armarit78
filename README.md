<div align="center">

# Guillaume Poret

### IA, vision par ordinateur, robotique & systèmes embarqués

<p>
  <a href="mailto:guillaume.poret@student-cs.fr">
    <img src="https://img.shields.io/badge/Email-Contact-0A66C2?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/A_REMPLACER">
    <img src="https://img.shields.io/badge/LinkedIn-Profil-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="CV_2026-06-10_Guillaume_PORET_FR.pdf">
    <img src="https://img.shields.io/badge/CV-PDF-FF6B35?style=for-the-badge&logo=readme&logoColor=white" alt="CV PDF" />
  </a>
</p>

<img
  src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=22&duration=3200&pause=900&color=00A6A6&center=true&vCenter=true&width=850&lines=Engineering+student+%40+IPSA+%2B+CentraleSup%C3%A9lec;AI+%7C+Computer+Vision+%7C+Robotics+%7C+Embedded+Systems;Looking+for+a+full-time+role+from+November+2026"
  alt="Typing SVG"
/>

</div>

---

## Bonjour

Je suis étudiant ingénieur en dernière année à l'IPSA, filière systèmes embarqués et télécommunications, en double diplôme Intelligence Artificielle à CentraleSupélec.

Je cherche un CDI à partir de novembre 2026 sur des sujets à l'intersection de l'IA, de la vision par ordinateur, de la robotique, des systèmes embarqués et des systèmes intelligents.

Ce que j'aime construire : des systèmes concrets, testables, documentés, avec une vraie logique d'architecture derrière le prototype.

---

## Ce que je sais faire

<table>
  <tr>
    <td width="50%">
      <h3>IA & data</h3>
      <p>
        Deep learning, computer vision, segmentation 3D, détection, tracking, reinforcement learning, LLMs, RAG, agents LangGraph, routage d'intentions, évaluation de modèles.
      </p>
    </td>
    <td width="50%">
      <h3>Robotique & embarqué</h3>
      <p>
        ROS2, DDS / XRCE-DDS, micro-ROS, systèmes embarqués, ARM Cortex-M, communication robotique, intégration et contraintes temps réel.
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>Software engineering</h3>
      <p>
        Python, C, C++, SQL, FastAPI, React, Vite, Docker, Git, Linux, tests, API, architecture backend, persistance et intégration frontend/backend.
      </p>
    </td>
    <td width="50%">
      <h3>Cloud & opérations</h3>
      <p>
        AIOps, DevSecOps, observabilité, fiabilité cloud, automatisation des opérations IT, pratiques de sécurité et industrialisation.
      </p>
    </td>
  </tr>
</table>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS2" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=0A0A0A" alt="React" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
</p>

---

## Projets à explorer

### KyberIA - assistant financier intelligent full-stack

Application combinant backend FastAPI, frontend React/Vite, agent LangGraph, Mistral, Supabase/Postgres et outils financiers. Le projet couvre l'authentification, la persistance de chats, le routage intelligent des intentions, la résolution d'entités financières et un parcours de construction de portefeuille.

`Python` `FastAPI` `React` `LangGraph` `Mistral` `Supabase` `yfinance` `pytest`

**Pourquoi il est intéressant :** architecture produit complète, logique agentique, séparation claire entre conversation, outils métier et moteur de portefeuille.

---

### Suivi maritime temps réel - YOLO, KCF, Kalman & ReID

Prototype de vision par ordinateur pour détecter et suivre des objets maritimes sur images, vidéos ou flux caméra. Le pipeline combine entraînement YOLOv8 / YOLO11, export ONNX, inférence optimisée et tracking hybride avec KCF, prédiction Kalman et ré-identification par histogramme.

`Python` `YOLO` `ONNXRuntime` `OpenCV` `Kalman` `Tracking` `Computer Vision`

**Résultat notable :** sur une séquence de test documentée, 61 corrections YOLO, aucune perte de tracking et 424 images traitées uniquement par le tracker.

---

### UNet3D Liver & Tumor Segmentation

Pipeline complet de segmentation médicale 3D du foie et des tumeurs avec MONAI et PyTorch. Le projet inclut vérification dataset, split reproductible, amélioration progressive de modèles UNet3D, inférence sliding window, TTA, post-processing anatomique et augmentation 3D de tumeurs synthétiques.

`PyTorch` `MONAI` `CUDA` `Medical Imaging` `3D Segmentation` `Data Augmentation`

**Résultat notable :** la version finale améliore le Tumor Dice de 0.3785 à 0.4754 et réduit fortement les faux positifs anatomiquement incohérents.

---

### HERMES - Agentic Multimodal RAG

Pipeline RAG multimodal sur ViDoRe combinant retrieval texte, retrieval visuel avec ColPali, fusion hybride et agent LangGraph. Le projet inclut l'indexation, le tuning du paramètre de fusion, l'évaluation nDCG@5 et une interface CLI agentique.

`RAG` `Multimodal Retrieval` `ColPali` `Qdrant` `LangGraph` `Evaluation`

**Pourquoi il est intéressant :** il relie recherche d'information, vision-language retrieval, évaluation et orchestration agentique.

---

### ROS2 Micro XRCE-DDS Communication

Projet d'intégration micro-ROS / ROS2 utilisant Micro XRCE-DDS pour faire communiquer des systèmes embarqués contraints avec l'écosystème ROS2. Le système s'appuie sur une architecture client-agent, un transport UDP et des messages ROS complexes comme PointCloud2.

`ROS2` `micro-ROS` `XRCE-DDS` `UDP` `Embedded Systems` `Robotics`

**Pourquoi il est intéressant :** il traite une vraie problématique d'intégration robotique : communication légère, multi-machine et compatible avec ROS2.

---

## Autres projets Important

| Projet | Sujet | Stack / notions |
|---|---|---|
| SlayTheSpire RL | Agent PPO pour apprendre le combat dans Slay the Spire | RL, PPO, reward shaping, action masking |
| CaptionCrafter | API et CLI pour analyse image, OCR, génération de légendes et filtres | FastAPI, Streamlit, OpenCV, Tesseract, Mistral |
| GoPicasso | Robot peintre interprétant des SVG et corrigeant sa trajectoire | Python, parsing SVG, graphes, asservissement, GoPiGo |
| Viola-Jones Face Detection | Détection de visage temps réel avec cascade Haar | OpenCV, dataset positif/négatif, évaluation |
| Image denoising & inpainting | Restauration d'images par optimisation | Euler-Lagrange, gradient conjugué, BFGS/DFP, ROF |


## GitHub

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Armarit78&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Armarit78&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />

</div>

---

## Me contacter

Je suis ouvert aux échanges pour un CDI à partir de novembre 2026, principalement sur des postes liés à :

- intelligence artificielle appliquée ;
- computer vision et systèmes intelligents ;
- robotique et systèmes embarqués ;
- backend IA, agents, RAG et industrialisation de prototypes.

📩 **Email :** [guillaume.poret@student-cs.fr](mailto:guillaume.poret@student-cs.fr)  
🔗 **LinkedIn :** [à compléter](https://www.linkedin.com/in/A_REMPLACER)

---

## Hypothèses et éléments à compléter

- Le nom d'utilisateur GitHub utilisé pour les statistiques est `Armarit78`, déduit du README de CaptionCrafter.
- Le lien LinkedIn exact n'était pas présent dans les documents fournis.
- Les liens directs vers les dépôts ne sont pas ajoutés pour éviter d'inventer des URLs. Ils peuvent être ajoutés dans les titres des projets une fois les dépôts publics confirmés.
