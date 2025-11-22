# Sprint Planning 1 – Application de Gestion d'Absences Universitaires

## 1. Objectif du Sprint 1
**Durée estimée : 2 semaines**

**Objectif principal :**  
Mettre en place le système de base d'enregistrement de présence via **QR Code**, et permettre aux étudiants de consulter leur **taux d'absentéisme**.

---

## 2. User Stories Sélectionnées pour le Sprint 1

---

## US-04 — Génération du QR Code (Étudiant)
**Priorité : HAUTE**  
**Story :** En tant qu’étudiant, je veux un QR code afin de permettre au professeur d’enregistrer ma présence.

**Justification :**  
Cette fonctionnalité constitue la base du système. Sans QR code, le mécanisme principal d’enregistrement de présence ne peut pas fonctionner.

### ✔ Critères d’acceptation
- L'étudiant peut générer son QR code personnel depuis son interface.  
- Le QR code contient :  
  - l’identifiant unique de l’étudiant  
  - l’ID de la session du cours  
- Le QR code est valide et actualisé pour chaque cours.  
- Le QR code s'affiche clairement à l'écran.  

---

## US-07 — Scanner le QR Code (Professeur)
**Priorité : HAUTE**  
**Story :** En tant que professeur, je veux un scanner afin de lire le QR code pour enregistrer la présence.

**Justification :**  
Complément indispensable du système QR Code : le professeur doit pouvoir scanner les codes des étudiants pour valider la présence.

### ✔ Critères d’acceptation
- Le professeur peut activer la fonction scanner dans son interface.  
- Le scanner lit correctement le QR code de l'étudiant.  
- La présence est enregistrée immédiatement après un scan réussi.  
- Un feedback visuel/sonore confirme l’enregistrement.  
- Le système empêche les doublons (un étudiant ne peut pas être scanné deux fois pour un même cours).  

---

## US-09 — Enregistrement Manuel de Présence (Professeur)
**Priorité : HAUTE**  
**Story :** En tant que professeur, je veux une interface afin de pouvoir enregistrer manuellement la présence des élèves.

**Justification :**  
Permet de gérer les cas où le QR code ne fonctionne pas, ou de corriger une présence déjà enregistrée.

### ✔ Critères d’acceptation
- Le professeur voit la liste complète des étudiants inscrits.  
- Il peut marquer chaque étudiant comme **présent** ou **absent**.  
- Les modifications sont sauvegardées en temps réel.  
- Le professeur peut modifier une présence déjà enregistrée.  
- L’interface indique les étudiants qui ont déjà été scannés via QR code.  

---

## US-01 — Consultation du Taux d’Absentéisme (Étudiant)
**Priorité : HAUTE**  
**Story :** En tant qu’étudiant, je veux une interface afin de suivre mon taux d’absentéisme.

**Justification :**  
Permet à l’étudiant de suivre son assiduité et de prendre conscience de sa situation académique.

### ✔ Critères d’acceptation
- L'étudiant voit son taux d’absentéisme global (en pourcentage).  
- L’étudiant voit le détail par matière.  
- L’étudiant voit l’historique complet de ses présences/absences.  
- Les statistiques affichent :  
  - Nombre de présences  
  - Nombre d’absences  
  - Taux d’absentéisme  
- Les données sont actualisées après chaque cours.  

---
