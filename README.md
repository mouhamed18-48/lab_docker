Pour tester cette application , il faut en premiere lieu se deplacer dans le repertoire et executer le commande docker-compose up -d pour lancer les conteneurs. 

Ensuite vous pouvez tester deux endpoints : une requete get pour recuperer les patients et une requete post pour enregistrer un patient.

La requete est la suivante : http://localhost:3000/patients/


Pour le requete poste vous pouvez tester avec ce format  JSON :

{
      "first_name": "Alice",
      "last_name": "Smith",
      "email": "alice.smith@example.com",
      "phone": "+1234567890",
      "adress": "456 Elm St, Cityville, Country",
      "diagnosis": "Common Cold",
      "image_url": "https://example.com/images/alice_smith.jpg",
      "created_at": "2024-11-01T10:15:30Z"
    }
