# Dagbog

## husk at merge word dokument!!

## Tirsdag 14-08-2018

Jeg brugte dagen på at lave class diagram i draw.io samt at bygge kode strukturen op i C# ud fra det Python kode k|a selv har udviklet.
Jeg glemte at sikre mit arbejde på github i dag, dumt.

## Onsdag 15-08-2018

Teamet, minus mig selv, skulle til møde på silkeborg kummune, daily scrum blev ikke afholdt.
Første ting jeg gjorde i dag var at sikre mit arbejde, smart.
Jeg fortsætter med at oversætte python koden og bygger videre på strukturen efter bedst evne.  
Jeg har i dag oprettet min dagbog på github. Jeg skal huske at have overført resten af min dagbog fra word over til min github dagbog.

## Torsdag 16-08-2018

Daily scrum afholdt
I dag har jeg arbejdet med at få en background service til at kører. jeg fik win10iot enheden til at sende telemetry til azure eventhub.
jeg fik også enheden til at lave en webrequest til internettet. win10iot(.net core) er ikke det samme som .net framework selvom det bliver markedsført lidt i den retning. Startede på at initiate board med sensorer sidst på dagen. 

## Fredag 17-08-2018

Daily scrum bliver ikke afholdt grundet firmaets Squads(vidensdeling på tværs af firmaet)
Jeg har i dag arbejdet med at få en knap til at virke på raspberry pi 3, hvilket er lidt svært at få viklet hovedet omkring, da der ikke er nogen gode kode eksempler på nettet.
Jeg fortsætter mandag.

## Mandag 20-08-2018

Daily scrum blev ikke afholdt en havde ferie og en anden var ude af huset, så vi var kun to fra teamet til at holde scrum ergo blev det ikke holdt.
Min knap virker, om end på en måde jeg selv har implementeret, med en timer og en continuerlig aflæsning af knappens status, da knappen på raspberry pi kan have en high low status, men skifter mellem high og low når den ikke er aktiveret.
Jeg er gået igang med at læse om at implementere gps modulet på raspberry pi.

## Tirsdag 21-08-2018

Ingen daily scrum.
GPS i dag. Vi er kommet til den konklusion at GPS modulet er skaddet siden det ikke kan få et fix. En hel dag brugt på at arbejde med kode der givetvis virker, men som ikke kan læse data fra enheden. Jeg begynder at arbejde med afstandsmåleren. det var virkeligt demotiverende at arbejde med. Jeg sluttede dagen af med at researche en ny kommunikation protocol til raspberry pi NarrowBand(NB).

## Onsdag 22-08-2018

Ingen daily scrum.
Starter dagen med fortsat at researche narrowband. I min research fandt jeg et grovepi shield til plug & play sensorer. Jeg var til et møde, der havde til formål at diskutere og komme med forslag til, hvad foranalyse betyder og skal indeholde i "ready to go" iot. 
Møde DRTL ”udfoldningen” af Analysefasen.

## Torsdag 23-08-2018

I dag Torsdag har jeg arbejdet på at skrive python koden om til C#. det indebærer for mig at have de forskellige sensorer oppe at kører og en god logik bagved. jeg har arbejdet på at få lavet ordentlige classer og metoder, samt at lave en god dokumentation med kommentar i koden. 
Jeg fik til opgave at lave en indkøbsliste til "Proof of Concept" barnet der blev affødt af mødet onsdag. Den indeholdte hardware relateret til raspberry pi og et arduino board til connectivity.

## Fredag 24-08-2018

Jeg fandt ud af at fredag er en travl dag på kontoret, her i firmaet, folk kommer hjem fra de forskellige projekter de har gang i for at lave vidensdeling i de squads de nu har. det betyder at der er mange mennesker på kontoret og de taler alle sammen, så støjniveauet stiger betydeligt, hvilket gør det svært at koncenterer sig om arbejdet. Thomas fik lavet en virkende prototype til slettestrand, og vi testede den sidst på dagen.

## Mandag 28-08-2018

