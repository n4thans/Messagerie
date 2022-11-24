# Messagerie

Messagerie instantanée où les utilisateurs peuvent communiquer par messages privés. Ces messages seront enregistrés en DB pour pouvoir reprendre une conversation. 
--> Backend capable de gérer l'authentification et les messages en DB  
--> Un client qui ira récupérer une authentification depuis le backend, proposera une liste des utilisateurs et enverra les messages 
--> Un serveur Websocket qui sera juste chargé de passer les messages aux utilisateurs concernés.
