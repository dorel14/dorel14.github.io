# David Orel 👋 — `dorel14`
 
> Je fais le pont entre le terrain métier (ERP, négoce, distribution) et le code qui automatise ce que personne n'a le temps de faire à la main.
 
Consultant ERP le jour — sur un rôle transverse entre technique et support (gestion commerciale, négoce de matériaux, grande distribution) — développeur autodidacte le soir. Le fil rouge de tout ce que je construis : des systèmes qui ne se parlent pas, et que je fais quand même communiquer.
 
---
 
## Ce que je fais concrètement
 
Sur le terrain, je suis le point de passage entre le métier et la technique : audit fonctionnel des ERP, support N2/N3, conduite de projet, conduite du changement. Le problème récurrent : chaque outil (ERP, téléphonie, bureautique, messagerie interne) vit dans sa bulle. Alors je code des passerelles.
 
### Côté outillage & perf (mes projets les plus récents)
 
- **[libembedding-ng](https://github.com/dorel14/libembedding-ng)** — Un fork étendu de [libembedding](https://github.com/pacifio/libembedding) : embeddings et reranking locaux en C/C++ et Python, avec un runtime unifié ONNX + GGUF (llama.cpp). J'y ai ajouté le support Windows (DLL native), l'empaquetage PyPI, le chargement de modèles locaux et un auto-tuner. Résultat annoncé : 5 à 8x plus rapide que fastembed, avec 3,5x moins de mémoire.
- **[whoosh-ng](https://github.com/dorel14/whoosh-ng)** — Une modernisation complète du moteur de recherche full-text Python Whoosh : Python 3.11+, typage strict, système de plugins, recherche vectorielle, intégration FastAPI, sources de données SQL/REST/GraphQL/CSV, et détection automatique de langue.
### Côté automatisation métier
 
- **[3CX-Cdr-Server](https://github.com/dorel14/3CX-Cdr-Server)** — Les journaux d'appels (CDR) de la téléphonie VoIP 3CX ne sortent pas facilement de leur silo. Ce serveur léger les intercepte, les stocke et les rend exploitables pour de l'analyse.
- **[taskiq-flow](https://github.com/dorel14/taskiq-flow)** — Du pipelining de tâches pour [Taskiq](https://github.com/taskiq-python/taskiq), pensé pour orchestrer proprement des workflows asynchrones distribués en Python.
Et en coulisses : des macros VBA/VBScript qui branchent Excel ou Access sur des webhooks Slack ou Teams — parce qu'un tableur qui prévient l'équipe tout seul, ça change une journée de travail.
 
### Contribution open source
 
- **[AVNC](https://github.com/gujjwal00/avnc)** (client VNC pour Android) — Proposition d'une gestion des profils serveur pilotée EMM/MDM : provisioning de profils via les restrictions applicatives Android, synchronisation dédiée (`ManagedServerSync`), et interface adaptée pour signaler et verrouiller l'édition des profils managés.
---
 
## Ma boîte à outils
 
| Dev & Data | Systèmes & Métier |
|---|---|
| Python (FastAPI, SQLAlchemy, NiceGUI) | ERP & Gestion Commerciale |
| C / C++ (CMake) | Docker |
| JavaScript | Téléphonie IP (3CX) |
| SQL (PostgreSQL, SQL Server, Oracle, SQLite) | Taskiq / Celery (files d'attente, tâches de fond) |
| VBA / VBScript | |
 
---
 
## Comment je fais produire le code
 
25 ans d'expérience entre métier et technique m'ont appris une chose : la valeur n'est pas dans le fait de taper les lignes de code, elle est dans la capacité à cadrer le bon problème, à juger si une architecture tient la route, et à repérer ce qui ne va pas dans un résultat. En 2026, ça se traduit concrètement par un mode de travail assisté par des agents IA : je pousse les spécifications et les orientations métier, je valide l'architecture globale (et je réoriente si besoin), je relis la documentation produite — et je remets moi-même les mains dans le code quand il est mal fait ou incompréhensible. L'agent accélère l'exécution ; le jugement reste le mien.
 
---
 
## Pourquoi je fais ça
 
Je ne code pas pour le code : je code parce qu'après des années à voir des équipes perdre du temps sur des tâches que deux systèmes pourraient se répartir automatiquement, j'ai fini par apprendre à construire moi-même la passerelle plutôt que d'attendre qu'elle existe. C'est un profil hybride, ni pur métier ni pur tech — mais c'est justement ce qui permet de voir où ça coince des deux côtés.
 
---
 
## Me contacter
 
- 💼 LinkedIn — [David Orel](https://www.linkedin.com/in/david-orel/)
- 🐙 GitHub — [@dorel14](https://github.com/dorel14)
- 📍 Vire, Normandie, France
