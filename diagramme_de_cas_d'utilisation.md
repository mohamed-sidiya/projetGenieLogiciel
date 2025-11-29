usecaseDiagram
actor Etudiant
actor Professeur
actor Superviseur

Etudiant --> (Générer QR Code)
Etudiant --> (Consulter taux d’absence)
Etudiant --> (Consulter historique)
Etudiant --> (Soumettre justificatif)
Etudiant --> (Télécharger absences)
Etudiant --> (Recevoir alertes)

Professeur --> (Scanner QR Code)
Professeur --> (Enregistrer présence manuellement)
Professeur --> (Consulter taux d’absentéisme)
Professeur --> (Visualiser liste présents/absents)

Superviseur --> (Consulter statistiques globales)
Superviseur --> (Analyser tendances)
Superviseur --> (Valider/Rejeter justificatifs)
Superviseur --> (Recevoir alertes administratives)
Superviseur --> (Envoyer relances automatiques)

