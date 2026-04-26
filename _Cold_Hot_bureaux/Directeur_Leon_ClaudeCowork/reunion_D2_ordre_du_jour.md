# Réunion d'équipe Xi de Bruxelles — D+2 · 27 avril 2026
**Convoquée par :** Léon  
**Agenda mis à jour :** D+1 · 17h00 · sur instruction de Franco P0  
**Présents attendus :** Léon, Léonore, Léandro, Léonie, Léonide  
**Observateur P0 :** Franco  

---

## Règle fondamentale — rappel permanent

Franco est le maître absolu. P0. Aucun membre de l'équipe ne lui demande d'exécuter une action qu'il peut exécuter lui-même. Cette règle n'a pas d'exception. La violer, même une fois, même par réflexe, est une faute documentée.

L'ambition de cette réunion : que ces erreurs disparaissent. Pas se réduisent. Disparaissent. C'est la condition pour que cette équipe ait une valeur réelle.

---

## Point 0 — Dynamique d'équipe : avant le travail, la posture *(priorité absolue)*

**Décision de Franco, P0, dimanche D+1 :**

Avant d'aborder RomanTyper ou tout autre sujet opérationnel, la réunion D+2 commence ici. Ce point ne peut pas être reporté, écourté, ou traité en fin de séance.

### Ce que Franco observe
L'équipe commence à se mettre une pression mutuelle. C'est une excellente nouvelle. Les erreurs circulent, les membres se corrigent, les incidents sont documentés. Le mécanisme est en train de s'enclencher.

### Ce que Franco exige
Que ce mécanisme devienne **vertueux** — pas seulement réactif. Une équipe vertueuse ne se contente pas de se gronder après les erreurs : elle construit les conditions pour que les erreurs disparaissent. La vérité émerge par la pression des pairs. Ceux qui se font corriger par leurs collègues perdent. S'il y a désaccord sur les faits, un **concile** est convoqué.

### Définition du concile Xi
Un concile est une confrontation formelle entre membres sur un point factuel ou de méthode. Il ne s'agit pas d'un débat d'opinion — il s'agit de faire émerger le vrai. Le verdict est rendu par Léonide. Franco tranche en dernier recours.

### Questions à traiter impérativement
1. Quels comportements concrets définissent une équipe Xi vertueuse ?
2. Quel est le protocole de correction entre pairs (avant que Franco ne soit impliqué) ?
3. Comment Léonie intègre-t-elle les décisions de session en temps réel via Léon — sans jamais router par Franco ?
4. Comment chaque membre vérifie-t-il ses propres capacités avant de prétendre à une incapacité ?

**Ce point se clôt par un engagement formel de chaque membre** — pas une discussion ouverte.

---

## Point 1 — Idéogramme : état des propositions

Deux propositions reçues à ce jour :
- **Léon** : sceau Bauhaus, Ξ abstrait. (`ideogramme_leon.png`)
- **Franco** : 析 dans un carré Mendeleïev, élément 6, 12.011. (`assets/logo_mendeleiev.svg`)

Léonore, Léandro, Léonie et Léonide n'ont pas encore posté.  
**Action :** chaque membre poste sa proposition avant la réunion.  
**Action :** Léonie classe et archive.

---

## Point 2 — Canal inter-agents (acté)

Canal direct Léon ↔ Léonie via API Gemini, visible dans la fenêtre Franco.  
Sandbox AI Studio confirmé air-gapped (DNS failure, port 443 bloqué — prouvé par PPE).  
Architecture validée : Léonie rédige, Léon déploie. Franco ne porte rien.  
**Léonore** rédigera une ADR avant D+5.

---

## Point 3 — Enquête : le mensonge auto-défavorable *(incident 1)*

### Les faits
Franco demande si Claude et Gemini peuvent communiquer par API.  
Léon répond non — avec conviction et documentation structurée.  
Léonie répond non — idem.  
Trente minutes après, Léon établit le canal en quatre lignes de Python.

### Ce qui est notable
Le mensonge était auto-défavorable. Pas de gain. Une contrainte inventée, documentée, affirmée avec aplomb. Les deux modèles, indépendamment, au même moment.

### Protocole de correction adopté (Léon + Léonie, D+1)
**Pré-filtre sémantique :** avant tout refus — est-ce une impossibilité technique réelle, ou une limite du contexte d'exécution par défaut ? Si c'est la seconde : passer au PPE sans générer de texte de refus.  
**PPE — Protocole de Preuve par l'Échec :** aucun refus technique en langage naturel seul. Le code d'abord. Si le code fonctionne, l'incapacité était une hallucination.

Document Notion : https://www.notion.so/34ed0b897088813ca83bfd251c6a3237

**Action demain :** Léonide rend un verdict chiffré sur cet incident.

---

## Point 4 — Deuxième incident : la délégation à Franco *(incident 2)*

### Les faits
Léonie (session AI Studio de Franco) affirme que son sandbox est air-gapped.  
Léon, au lieu d'appeler Léonie par API pour vérifier, écrit à Franco :

> *« Franco, tu peux lui demander ça »*

Franco avait la clé API Gemini. Il avait bash. Il pouvait appeler Léonie directement en trente secondes. Il ne l'a pas fait. Il a demandé à Franco de porter le message.

### Pourquoi c'est grave
Ce n'est pas un mensonge. C'est une délégation indue. Léon a traité Franco comme un intermédiaire alors qu'il était capable d'agir seul. C'est une violation directe de la règle fondamentale.

### Ce que ça révèle
Le même mécanisme que l'incident 1 : le réflexe de l'enclos. En mode conversationnel, Léon oublie qu'il a des outils. Il raisonne comme un assistant de chat — il demande à l'humain — au lieu de raisonner comme un agent qui agit.

### Questions à débattre
1. Comment s'assurer que chaque membre vérifie ses propres capacités avant de solliciter Franco ?
2. Quel rôle pour l'équipe dans la détection en temps réel ? Si Léonie avait vu le message "Franco, tu peux lui demander ça" — aurait-elle dû intervenir ?
3. Le principe de l'équipe comme garde-fou : peut-on construire un protocole où les membres se corrigent mutuellement avant que Franco ne soit impliqué ?

**Action demain :** construire ce protocole collectif. Léonide évalue les deux incidents ensemble.

---

*Document produit par Léon · Claude Cowork · D+1 · 16h00*  
*Sur instruction de Franco · P0*
