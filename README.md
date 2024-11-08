# Datahaxx - Stories
I denna uppgift ska ni tillsammans skapa 16 olika berättelser där ni får skriva varsin mening var i varje berättelse. Ni kommer slå ihop era arbeten via Git. 


## Uppgift - sammanfattning

Ni kommer tilldelas en siffra och under arbetet kommer ni bara att skriva era meningar där er siffra tillkallas. Så personen som har nummer 4 kommer att börja med att skriva i dokumentet som heter "4". I detta dokument finns redan en existerande mening som ni kommer att fortsätta på. När ni skrivit färdigt er mening ska ni spara och pusha ert arbete till GitHub. Sedan fortsätter ni på nästa berättelse, så nummer 4 öppnar dokument 3 och fortsätter på vad person 3 skrivit. 

## Uppgiftsupplägg

1. Ladda ner repositoriet genom att öppna GitBash. Orientera er först till en önskvärd plats där ni vill ha repositoriet på er dator (exempelvis "Mina Dokument). Klona sedan repositoriet via kommandot: ```git clone [webadress här]```
2. Öppna ert dokument (vilket bestäms av siffran ni tilldelats). 
3. Skriv **en** mening som följer öppningsmeningen. 
4. Spara arbetet. öppna sedan Git och kontrollera vad det är som ändrats i ert repositorium genom att köra kommandot: ```git status```. Filerna som förändrats borde visas i rött. Därefter börjar processen att ladda upp ert arbete till GitHub.
Lägg först till era ändringar genom att skriva ```git add .``` (punkten betyder att alla ändrade filer läggs till).
Sedan kan ni göra en så kallad commit. Ni måste också ha med ett meddelande. Koden ser ut såhär: ```git commit -m "[ert meddelande här]"```. Om ni inte har med ett meddelande bör ni få ett error.
Sista steget är att pusha era ändringar till GitHub. Kommandot ser ut såhär: ```git push```. Förhoppningsvis går pushen igenom, men skulle den inte göra det kan det betyda att någon annan uppdaterat repositoriet före er och i så fall behöver ni ladda hem uppdateringarna via kommandot: ```git pull```
5. När ni pushat era ändringar så fortsätter ni på nästa dokument. Då tar person 4 och skriver i dokument 3. Om person 3 inte uppdaterat sitt dokument ännu så får ni vänta på att de gör det. Så håll er uppdaterade genom att köra kommandot ```git pull``` med jämna mellanrum.
6. Upprepa dessa steg tills ni skrivit en mening i alla dokument. När ni kommit till den punkten är det dags att skriva ett avslut till den berättelse ni först började skriva på. Så person 4 börjar med att skriva i dokument 4, sedan 3, sedan 2, sedan 1, sedan 16, sedan 15 osv. tills man kommit tillbaka till dokument 4.