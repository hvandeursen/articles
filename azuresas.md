# Azure SAS token
Artikel over het maken en gebruiken van een Azure SAS token.

Je kunt de inhoud van een Azure Blob storage account benaderen zonder dat je binnen die tenant bekend bent.
Hiervoor kan een Shared access token worden gemaakt. Dit is een soort van account / wachtwoord combinatie die toegang geeft tot de resources.

Uiteraard moet je met deze toegang voorzichtig zijn! Voor echte data is het niet aan te bevelen. Voor de Software blob die we bij packer gebruiken kan het over het algemeen wel.

De SAS token die we voor packer gebruiken is er een van het type Account key. Deze genereer je vanuit het Azure portal.

![image](https://github.com/hvandeursen/articles/assets/94694576/637b24ce-3c33-4a10-aa55-93dc597a9342)

Je geeft hier permissions aan en ook een tijdsbestek waarbinnen deze token geldig is.




