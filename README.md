# Introduktion
5. Semester Praktik forløb
Info-møde: introduktion til IoT og teamet.
Jannick
Thomas
Torben

### Scrum
Virksomheden har sendt alle på scrum kursus. De ønsker at være agile.
Teamet arbejder i 3 ugers sprint.

#### Definition Of Done
Jeg har spurgt ind til definition of done(DOD). De har valgt ikke at lave en på grund af de mange forskellige opgaver der indgår i deres digitaliseringsfase, som f.eks. marketing, salg og softwareudvikling. De føler at det ville være forsvært eller meningsløst at lave en dod der skal dække en artikel til en hjemmeside f.eks. fordi den måske vil ændre sig over tid, hvis de får nye ider osv.

##### Dod revised
Efter jeg har spurgt er der kommet lidt dod, som består i at en opgave bliver stillet og en lille dod bliver beskrevet i beskrivelsen til kortet på trello boardet.
f.eks. på dod 

### Planning poker
Teamet laver ikke tidestimering, da det ikke vil skabe værdi for dem. En anden grund til dette er at teamet er for lille til at vi kan opret holde det. Thomas siger at store teams, hvor man er afhængig af hinanden, der kan det være en fordel og nemmere at holde hinanden op på det, også fordi at andre teams kan være afhængig af ens arbejde og hvornår man forventer at blive færdige.  

### Software
Softwaren vi arbejder med er en slags proof of concept, f.eks. skal vi kunne sende data fra en raspberry pi enhed med win10iot styresystem til en azure eventhub. Sådan lyder opgaven og det skal bare gå så hurtigt som muligt så vi kan komme i gang med det næste software opgave.
Platform-framework-os-sprog
Win10iot
.net core
.net framework
Python
C#

### Mødetider
Arbejdstiden er sat til kl 8.00 til kl 16.00 med gratis frokost fra kl 12.00 til kl 12.30.
Folk møder somregel omkring kl. 8.00 og går gerne hjem igen omkring kl 16:00, men til tider også før sådan ca. 15.30.

---

# Dagbog 

## Mandag 06-08-2018

Kort introduktion til Kaastrup Andersen. Fik udleveret en bærbar uden nogen form for programmer så dagen gik med at installere diverse tools 
Jeg bør lave en tools mappe med alle de værktøjer jeg skal bruge adk, sdk, VS, ftp client osv.
Første opgave var at skulle få azure event hub til at virke med C# kode. 
Der gik lidt tid før jeg fandt ud af hvad det hele gik ud på angående deres vision og teknologien de har valgt at bruge. Men det er i bund og grund en form for rabbitMQ message queing 
Arbejdet med.


## Tirsdag 07-08-2018

Flere tools blev installeret Quickstart tutorials blev benyttet. Jeg kan mærke at det er ikke svært at skrive kode, men det at skulle forstå en ny teknologi (azure eventhubs) og et nyt framework (.net core) trækker tænder ud.

 
## Onsdag 08-08-2018

Arbejdet med.
•	Afvikling af små programmer på raspberry pi3 med win10iot

## Torsdag 09-08-2018

Afslutning af sprint bliver afholdt torsdag da teamet om fredagen har andre opgaver i virksomheden, hvor der bliver dannet squads til vidensdeling mellem kollegaerne.
Jeg forventer at det vil tage en stor del af teamet tid, om fredagen.
I dag har vi afholdt møder. Scrum relateret med retrospektive og sprint planning samt kort info omkring pitching møder til silkeborg kommune omkring en mulig software løsning til håndtering af hjemmepleje ruteplanlægning og håndtering af komunens biler.
Endnu et møde omkring mine forventninger til samarbejdet. Hvad vil jeg gerne arbejde med? Er der noget jeg brander for at få fingrene i? Er det noget som jeg synes er for kedeligt og ikke gider?
Jeg er egentlig tilfreds med at få en opgave og så løse den efter bedste evne. Svær eller let gør ikke noget.
Jeg har også kigget videre på at afvikle små programmer på raspberry pi3 med win10iot.
Fredag 10-08-2018
Arbejdet med at løse en fejl uden nogen reel fejl meddelse... gik på weekend med en sejr.
Fejlen bestod i at threading ”await” call metoden generede en fejl på et missing library. 

## Mandag 13-08-2018

Har lavet dokumentation på mine opdagelser med at lave C# kode til windows 10 IoT. Dokumentation udført som README.md på github.

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
[Class diagram](https://www.draw.io/?lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Untitled%20Diagram.xml#R7Z1bb9s6EoB%2FjYHsQwrr4kseYydNAyQ9QZzunvO0YCzG5qkseikql%2FPrdyiRtmWOXTemlKJgEaDSiJJIfjPD4UV0JxovXq8EWc5veULTTthNXjvRRScMo%2B5ZCP8pyVslCcJut5LMBEu0bC2YsH%2BoFppkBUtoXksoOU8lW9aFU55ldCprMiIEf6kne%2BJp%2Fa1LMqOWYDIlqS39D0vkvJIOe921%2FAtls7l5c2DK90im32eCF5l%2BXyeMnsp%2F1eUFMc%2FS6fM5SfjLhii67ERjwbmsjhavY5qqyjXVVt33ecfVVb4FzeQhN%2FR6Oh%2FyzZSdJlAV%2BpQLOecznpH0ci0dleWj6gldOJvLRQqHARzSVyb%2FVOJPYU%2Bf%2FmUuZVK8Vdd65vQv%2FYS%2FqZRvWglIITmI1i%2B%2B4Xypn1FlVeVvZ2m1KOeFmOpUWhclETOqU%2FVXNQ0qTPmCQmYgiaApkey5%2FnSiVWm2SreuTjjQNbqjdvvN1O4vXbnBsK3aHbSgu92Prd4%2BUr%2FdI%2Bu3vPVcCPK2kWDJWSbzjSffKQEkME490h5Lu%2FSot%2BVYttIHw96%2B9HBQ5WBNelWUg%2BBrxXsmaaFLPOJEJF9IlqRUWIqRv7BFSjKlAU88k0ZHFBmSslkGx1MAAXdGo2cqJIO24FxfkAriaDpnaXJD3nihOOQSHL05G825YP%2FAY4lRJrgspNYKYLiZYqLu1MojaA5p7owOBFuiW%2FJaS3hDcqkFU56mZJmzx1UxFqAiLBtxKflCJzKF%2FszSdMxTLsq6MA2S0UlVXPq6XyttbdM3nIb9ul4E%2Fag6f1m3m4FJM99oM4f9H2jo4vUemnaSzaCIe9436NvvC5D3hVvvIynQzoikI%2BURcsvx%2FJw6RpY6nqowZsnAIZzD0RUcjYG%2FAG6IegIAWaqN4N%2BpQZXxSl836GmRUdmUPsmdCpsvyZRls5syzUW8ltzrSlEiDvc%2BpWUEMmdJQrPSRUoiSaVZSo20a4CM9kbwB3U7Vo6wBxkfw3mwPoc%2FlVxIKCqUhbBSiSio7QtVqnuYxoW4xr3VOf5Iv7Z5v6eFiS2qFrmUlUQqciZWDN6FbQEAyjZKc3ooG4%2FTwGIZ2SwjhFtKHml6x3MmGVfPF1XaLZ4tIOuFB7oEBzEBaofXGdRBaerQRJz8qzLJZw43eUN8N1VDsA1D7NutfQENXeab%2B5ab%2B3hQb37jQ5v7oB8frwaR7ZCVeS%2BLfF7pw7qxvWOZN%2B59oHf0gT%2BglR2gUO%2B%2BTb6Mvj08%2FPG1glr2LjzQ9wI9tA12AXTowyYXyAbD1sKm6AdxU%2BlcfeDkhuuwRd96hnKteEJoIukJlFBzfeQ89VzfzzUIWvSxkR0SK7IXLF%2Fy3BusW7DRgZ7YBVgzdrUB9mqZ%2B45Oux2deLubM7A0IDzDNCAOHahAgNq2Gt6XRUIro054UVbSZ2%2FZezHvmC3Z3c%2FBubpw2XhjnPJs5rk65op0dxrjGtseW3GVbEHBKS6WFdcLCLYeQOSxHoEV6RI1Z652N7aa08nNKFPuWR7BMujG7cE0obkfkziWWmQP%2B6PUHIxKBPisqhmVAAP0PRxnWFv0rLFtjKeVQ718hgzfsFzSjAoP1xXcfoueNsaN9opK4DvmXCRMrbpYmS6UGmrY8z2G79mBPtkJX7xzqvjeXV2dn%2FDHv9WKXKiI0qI%2FlVJvyY66q0GL%2FdXAnm29pXmu1j770ahWR6OiYX04qj%2BwDT5CZ91N3HuUxdtDzV95lX8CD6PC94P2s43327Rt0ihLJyZto%2FTdoPdAQ8aXUGgOekExvujlgj4Ws5MqetLN6wPJv3fCfqoKWS6X6M%2FW5fXW%2BS7QyCq35qwTXwkzoVlyQZ%2FZlD7wccqLRLfC%2BXn%2Blk1PPPzG4CMz9c3Bt4cbv6VQsAnP2BRUIOdiFXbB66Kgi9H1EVhT3zlYCx%2BRPjWuGy7aANwzXI6%2F%2FPHfu2u%2FQu5AxDu%2BTNszF9jYlwX45MLD%2FfXV1eW9Z%2BqKKTYP2BhTfH53ybIHCFT90mRXTLFJwKaY9vDRLmB6OZ1zz9QVU3QysDGouyfsK6ITqOwXIqdzz%2FQYpthUYWPhM%2B58i60Q%2BoJByJpNaW2tjYd8BORei1FTaBuuBc8PXx1CbXhgXOSg7xLiTaiZxd%2Fu5PpZX1eMsVnBxprUnbO%2BxuN6rq66qdgcYGNcQ5TrPSXJtuGWo5GesRvG8YH%2B2QnjM4vV77ZLka7N2jY6O4Z%2BnW9TFNomNK62LWP%2BA%2FaPnklHh3G7PdvQ9s6k69ch%2B9Uc8r4gPsCw3W5Xs2O%2FmulKLyfVqiy%2FQuvQrTLC%2Ff4cabIxLXOybh2fK0jKGcRxyso8l18kbEo83ffTxQaZm6Lr9yRyBA0bRcaguegB7%2F%2B6ftMOfS%2FJEV5k6r4xm%2BwNf%2FsAGtmHchcA9wG0vWhtouLVYlmtefGhcyuhs7XzYoyY2BAJZd8bOm%2B%2FL0K2muq2HjpHeOicgNa%2FXWe3UP8spxBIJ7mfwT%2FMkf%2F0TlSoljkJrvDQWRRZtuoN%2BV1SjgSKRcuNAfVbUbmBhkXLGDQX0bI9k9sJoRDd%2ByI7uR6tNthXjf91Vk0u%2BKjZDWYsam7KNiPbFH%2BzqNmsf6hFzW399kCEzJWPw865WhwOekkgk3A6Gpk1449ivWRcS4xgy%2BjMdcjBo3WP2LnwfAOWg2g0iuv7y8f2ZCe6DbhZ%2B3NUfy9uRHM39HZDVf%2FcVOPqWvkDBQ2rboSobkua28dWeVTqlbDnWr33%2F1eoX0oZKR9%2Fqj23aghK5726uq2k4KszI%2FtOwIOKYtkZjAnwETm4aYjm2YypLt5a0zfv2RCXGapL3edxt4l%2BcMa%2BErNibpySHHpW3QtGZoIsFL3wF8nkvwEqM1sDB5%2B6v0i2zgs5V2MQ6q7R5PYXyZXapai6Jzw77Q5PocaGH5g1VONrb9vyw2svq3zfy5xJOlmS0qu9CLKse14HzdDpIKiPUgyQVTfBGTahGP38hthwuv5pqGrsYv0DXNHl%2FwE%3D)

## Fredag 24-08-2018

Jeg fandt ud af at fredag er en travl dag på kontoret, her i firmaet, folk kommer hjem fra de forskellige projekter de har gang i for at lave vidensdeling i de squads de nu har. det betyder at der er mange mennesker på kontoret og de taler alle sammen, så støjniveauet stiger betydeligt, hvilket gør det svært at koncenterer sig om arbejdet. Thomas fik lavet en virkende prototype til slettestrand, og vi testede den sidst på dagen.

## Mandag 27-08-2018

Hvad lavede jeg mandag?
Jeg fik bestilt varer til Proof of Concept, som bliver vores v3 version, som at der skal arbejdes på.
Indtil nu har det meste af arbejdet været at finde ud af om hardwaren kan bruges til løsningen og for mig at lærer hvad der er ind og ud i forhold til dotnet core

## Tirsdag 28-08-2018

Jeg var til Morgensang og blev derfor lidt forsinket på praktik pladsen. Mødte ca. kl. 11.30, hvor jeg fik en lille briefing på sprint retrospektive og sprint planning. jeg fik uploadet mit seneste projekt til github og fik skrevet en smule dokumentation til koden.

## Onsdag 29-08-2018

I dag skal jeg til at lave dokumentationen færdig til C# v2. Dagen gik også med at undesøge Micro Python, og hvordan det fungere.

## Torsdag 30-08-2018

Strategidage i Slettestrand. k|a 2020 strategi, samt fest om aftenen.

## Fredag 31-08-2018

Strategidage i Slettestrand. Go gammeldags rystesammentur eller med et andet ord teambuilding. fed tur.

## Mandag 03-09-2018

Daily standup blev afholdt i dag. 
Jeg venter stadig på varer til PoC, de skulle gerne komme i dag eller i morgen. 

Vigtig perspektiv: Man skal ikke forvente at komme ud i et firma og skrive kode i 37 timer om ugen. man skal kunne udvikle og designe kode, samt være mere orienteret omkring salg og forretning

Jeg fik lavet et Sekvens Diagram i dag, som der gerne skulle hjælpe med forståelsen af domænet [SD](https://www.draw.io/?lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=SD%20(3).xml#R5VrZcqM4FP0aV%2FU8OMVibPPoJZ3MVDqTilOdnkfZyFgVGTFCxE5%2F%2FVyBwIBohziQZDp%2BSOBqg3OO7iK7Z8%2B2%2BwuOws035mHaswxv37PnPcsyXWMI%2F6TlKbW4o0Fq8DnxVKeDYUF%2BYmU0lDUmHo5KHQVjVJCwbFyxIMArUbIhztmu3G3NaHnVEPlYMyxWiOrWe%2BKJTWodO8bBfomJv8lWNg3VskSrB5%2BzOFDr9Sx7nXzS5i3K5lL9ow3y2K5gss979owzJtKr7X6GqcQ2gy0d9%2FUXrflzcxyIRgMUL4%2BIxurdL5DAO%2FTUs4YUppguOVz58qpnT67YLYLJFsRfs716A%2FGUoQYvE8rLeEuvyBpTEsDdNMScbLHAHFqoMt8cbNPdhgi8CNFKDt2BnsC2EVsKdyZcAsUCwRCe31OKwogsk1UNsHC8inlEHvEtjlIlSSuLhVxplitEGnV4FGKPmAu8L5gUXBeYwXNyQMNQrbarqFPSNjMqdweh5HLYFERiZ0akxOnncx8IggvFUT1f2WIFvoCWWxSFS8yTx7wh8MfW2duRABrkBjP%2BZHefkzuzwp0zelPubJ27Kg0F8EJGApEs50x7zrzCBuNiw3wWIFrkQ8coF0xjkAZOWd92HUY6ROM2ENK90QIHEQMRGxwjjwT%2BMcTkOxJw4hNK%2FABsSyYE20JDJBAXExkXJHIwO9hw4GWWJWWrh6ybCkbjo2hCRx%2BLMq3YK8UUHV%2BOKRIg9XK0qoFLDb2RAjjw0q86HruCeMRivsJqVAX0%2FDEa8aDTcKKT0ULIp3Q7%2BX55l5Ax0sicIUqnkKh8%2BWvx9%2FUfJ%2B2omt0D%2BPCnH2DoG2eGYWWWfySOZ4Y9yAwFIo8D3PWGGlQ8neU4jTaUNtHQfmai1F20sTPddwghL9e7U8WjWQgZtqB2U0%2BQPlYIycqZQgRx30bvecDIabG6CiCmnupcMRZCGEBb6ayDZRQ%2BEw6%2BcrTFz%2Fv6FuRqVtyzZdTIdVyjV9NpQ7BOnWC9bziKoMr8coOeKENee156T8SPxCW7I1fdpy7aBHeY3jf20EUROw1FXAA1w%2FSVuraGg7Nx4eNWVX52ol%2BvlnqWY3fl182h7tjtyeRnzDEMTXIp4zJe6hnV%2BSOQUttybHP9vrmW867luaknW28Qn4cvBUkr8cxG8dlxX49QBsgrhP4pZT0qy%2FqNTy70GNW9rHOl%2FC9OLnT%2F3WUU%2F6Wi3iP8VmAfmc3OJfQyynxmovbCbU1RzLGIuTy9YA%2Bt0cVCDE1TD0Ub7Klx0NykPui6GNDAHp3ImkZ%2FdaIWWRtrrH3cqqKShwzrauDOior38NcvRmigHZu83TFBFhrqHIA8GfsEHqAKv22cWCaBto9P1J4HsHUPkGWKHnksMTX8N5Zfok5BjKKPUoom0IPitTi0ZtnlA0KR4HHYG81Q4GEeYakEj%2FhEIJotAU%2BXrJLVV20sXFe3dbfadeL9ZPsCP0BCHcHVnCAfvKLuRbt7jO8AMGGqi3lmdLnWJBYb6bFkj%2BniW5dLzZFQ6Fpu3xj34d3GH0M7FSeW%2FEAh90fdx0KrHAvdxgds1a%2B4TnL1%2Bpn5FfjmtpIEDYUarJoCU3NWMXJrcBlUM%2BNTcBnoIfASlviQwAxqyt0OkTE1ZG44E2zFaLIdq7vu6u4cel%2FDe9d%2F63lP1uQF53MBEw1AVocO5qAmExFMdlb%2BY544DxgAU5HAv5Nt8%2F6wHZ7yM4eMqHFdDldDVLVKOIkn%2FSzpKE%2FZz5Y0%2Ftgtup9c%2F6YUVQqR2rO%2BdgiC28Mv19Ls7vDzQPv8Pw%3D%3D).

De bestilte varer ankom idag, men havde dog glemt at bestille PSU og SD kort.
Bestilte PSU og SD kort fra Proshop, de skulle gerne ankomme imorgen.

## Tirsdag 04-09-2018

Scrum møde blev afholdt i dag.
Venter på at SD kort og PSU til RPI ankommer. Tingene ankom sidst på dagen. Næste gang skal jeg ikke regne med at komme igang på selve leveringsdagen, samt opsætningen af hardwaren også kommer til at tage noget tid. RPI boardet som blev bestilt er en raspberry pi B+ hvorimod den tidligere raspberry pi var en B v1.2. Fordi det er så nyt understøtter win10IoT ikke det nye board. 

Jeg er stadig igang med at lave diagrammer over koden. Jeg har læst op på hvordan jeg skal stykke kode sammen med GrovePi,således at når rpi kommer op at kører med win10iot, så er jeg klar til at skrive noget kode. Tiden bliver derfor udnyttet bedst muligt og der vil ikke gå lang tid, med at forstå sensorer/hardware nær så meget, som i starten af projektet/praktikperioden.

## Onsdag 05-09-2018

scrum møde blev afholdt
Onsdag gik med at læse om I2C.

## Torsdag 06-09-2018

Scrum blev afholdt 

Jeg fik samlet GrovePi PoC boardet. Men pga af min computer hoppede på et andet netværk, havde jeg lige pludselig ikke adgang til Azure Portalen, dvs. i browseren kunne jeg fint logge på og se min service (eventhub/IoT-HUB), men mit program til at læse fra Hubben, kunne ikke få forbindelse, så der gik desværre en par timer med at finde ud af hvorfor det lige pludselig ikke virkede mere. Jeg havde ikke ændret i koden og access keys og paths havde heller ikke ændret sig.

Jeg fik også hul igennem til I2C modulet, men jeg skal have arbejdet på at få oversat det data jeg får ud til noget mere forståeligt.

## Fredag 07-09-2018

Jeg fortsatte med at arbejde med I2C. Jeg er desværre blevet bremset af Visual Studio community edition, pga af en opdatering til denne version. Den seneste opdatering af VS community, har betydet at jeg ikke kan benytte debuggeren til at fejlfinde i min kode. 

Alt dette afledte en god snak, med Thomas, om at man ikke altid bør kører med den seneste version af sit udvikler værktøj. Det er en god ide at kører med en buffer således at alle børnesygdomme er identificeret. pga af VS community 15.8.3 kan jeg ikke debugge, så jeg bliver nødtil at downgrade VS community til 15.7.6

## Mandag 10-09-2018

Mandagen er blevet brugt på at få visual studio til at fungere med en working toolchain debugger. jeg er nu kommet til den konklusion at jeg fint kan debugge steppe igennem koden på raspberry pi 3 boardet, men jeg kan ikke se values for forskellige properties eller typer, hvilket gør debuggeren yderst uproduktiv. Jeg kan dog lave min egen debug metode, som sender values til eventhubben hvor jeg så kan lytte på den og så få resultatet den vej igennem. fuck.

## Tirsdag 11-09-2018

Noter fra [Messe-Noter](https://github.com/bent-mortensen/Dagbog/blob/master/Messe.md)

## Onsdag 12-09-2018

Holdt et lille scrum møde i dag mellem Thomas og jeg. Jeg fik skrevet mine notater rene fra gårsdagens messe og sendt rundt til Jannik, Torben og Thomas. Jeg var med til et møde omkring maskot samme med Anton, Jannik og Thomas, her fik vi en snak omkring maskots behov for at udvikle deres forretning med smart tøj/IoT tøj. 

## Torsdag 13-09-2018

Scrum blev afholdt. 
Jeg brugte meste af dagen på at få I2C protocollen op at kører. Meget af tiden gik med at forstå microsofts I2C controller class. Meget af tiden gik også med at forstå hvad der skulle skrives til TH02 sensoren, og resten af dagen gik med at prøve at få oversat de data jeg fik ud af TH02 sensoren. det blev ikke løst denne dag......

## Fredag 14-09-2018

Scrummøde blev afholdt
Torben fandt et TH02 Python library på github, som jeg brugte udregninger fra til at converterer de data jeg fik ud. og det virker umiddelbart, og jeg siger umiddelbart da jeg ikke har nogen aktuel refrence data at kunne holde det op imod.

Jeg er begyndt at Læse op på SI1145 I2C sensor til at måle lys.

## Mandag 17-09-2018

Scrum møde blev afholdt
Jeg er begyndt at læse op på SI1145 sunlight sensoren til at måle synligt lys, ir og uv. Jeg har stadig 4 sensorer tilbage at implementere i C# kode. 

## Tirsdag 18-09-2018

Scrum blev afholdt.
Dagen gik men ikke uden frustrationer over at min enhed ikke ville blive på netværket. hvilket med førte at jeg ikke kunne teste min kode og se om det virkede. Desuden er sunlight sensoren ikke ligeså nem at arbejde med. I2C temp og humid sensoren var svær at forstå samt det var første gang jeg arbejdede med I2C protocollen. koden jeg skriver er også nede på et niveau med embedded software. man skulle tro at når man arbejder med I2C så var det nogle af de samme ting man skulle igennem for at få hul igennem samt at få noget brugbar data tilbage, det er ikke tilfældet. 

## Onsdag 19-09-2018

Scrum blev afholdt.
I2C sunlight sensor jeg stoppede med at arbjede med den sensor og hoppede over på en analog MQ2 gas sensor. Det gik umiddelbart smertefrit i forhold til I2C sensorerne. næste gang vil jeg højst sansynligt kigge en ekstra gang på typen af protocoller inden jeg giver mig i kast med sensorer.  
    
Jeg har de seneste dage haft store problemer med raspberry pi boardet da den ikke vil bliver på nettet. [link](https://github.com/bent-mortensen/Dagbog/blob/master/wifi.md)

## Torsdag 20-09-2018

ingen scrum møde
Retrospektive
sprintplanning

## Fredag 21-09-2018

Månedsdag i kaastrup|andersen. Jeg fik lavet en del dokumentation på mit arbejde og fik implementeret piezo sensoren så der var lidt ekstra kød på, til når demo'en skal vises frem på novenco mødet.

## Mandag 24-09-2018

Thomas og Jannik er taget til KBH lufthavn for at holde møde omkring et muligt samarbejde vedr. IoT. Jeg vil så småt på begynde min praktik rapport udført i google docs.

## Tirsdag 25-09-2018

Image arbejde.
Jeg har dokumenteret mine skridt på github.

## Onsdag 26-09-2018

Image arbejde.

## Torsdag 27-09-2018

Image arbejde.

## Fredag 28-09-2018

Image arbejde. 
Jeg fandt ud af at mit program endeligt blev lagt på OEM udgaven af win10iot.


Fik løbende opdateringer, fra IT-manden Kim, hele ugen igennem. Det kan desværre ikke lade sig gøre at få en fast ip til enheden, gennem det nuværende netværk. Alternativet vil være en 3G/4G mobil router til at skabe et netværk kun til enheden og den arbejdsstation man bruger.  
k|a har tre netværk, guest, mobile og clients. clients har 100 ip'er og guest og mobile deler de sidste 100 ip'er, det vil sige at når huset er fuldt, eller parkeringspladsen er fyldt op, så bliver guest netværket meget ustabilt og raspberry pi enheden faldet hurtigt af. Hvilket gør det, at arbejde med enheden besværligt og en unødvendig langtrukken affære. Det er måske scrummasters opgave at rette op på sådan en fejl, men jeg burde have lavet mere opmærksomhed omkring mine frustrationer vedrørende fejlen. 
Jeg gad godt vide hvor grænsen ligger for, hvornår sådan en fejl bliver til en scrummaster opgave, på den ene side kunne jeg godt arbejde på enheden, omend det skete langsomt, på den anden side, hvis det havde gået ud over leveringstidpunkter, havde det nok været en anden sag.


## Mandag 01-10-2018

Uploadet alt mit arbejde, på at lave en OEM udgave af win 10 iot, med det software jeg har lavet til raspberry pi, for at kunne aflæse sensorer og sende til skyen. 

Side notat: Vi har 2 SD kort på kontoret, købt til raspberry pi. Chefen fik den ene, da han skulle bruge en til privaten. Det er ikke en kritik, bare en observation, at ens ressourcer kan forsvinde.

## Tirsdag 02-10-2018

Undersøgt to user-stories Thomas kom med mandag. Det var ikke ideén at de skulle implimenteres, men at jeg skulle undersøge mulighederne for en mulig løsning til de to user-stories 

## Onsdag 03-10-2018

Skrevet på min problemstilling og problemformulering samt lidt til praktik-rapporten

## Torsdag 04-10-2018

Skrevet på min problemstilling og problemformulering samt lidt til praktik-rapporten

## Fredag 05-10-2018

Skrevet på min problemstilling og problemformulering samt lidt til praktik-rapporten

## Mandag 08-10-2018

Kommer sikkert til at skrive på min rapport

## Tirsdag 09-10-2018

Kommer sikkert til at skrive på min rapport

## Onsdag 10-10-2018

Aflever praktik rapport

## Torsdag 11-10-2018



## Fredag 12-10-2018

Praktik slut 

## efterårsferie start den 13-10-2018
