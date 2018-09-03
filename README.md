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

Jeg fik lavet et Sekvens Diagram i dag, som der gerne skulle hjælpe med forståelsen af domænet [SD](https://www.draw.io/?lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=SD#R7Vpdc%2BI2FP01ntk%2BwPgDg3kEkt1tJ9lmQqfdPgosbA3CcmU5kP31vcKysS0veIghtLs8JPLVl33O0bmSwXBmm90njuLwkfmYGrbp7wznzrBta2wO4Z%2BMvGaRsWVngYATXzU6BObkG1ZBU0VT4uOk0lAwRgWJq8EliyK8FJUY4pxtq81WjFZnjVGAtcB8iage%2FYv4Isyinmse4p8xCcJ8ZstUNQu0XAecpZGaz7Cd1f6TVW9QPpZqn4TIZ9tSyLk3nBlnTGSlzW6GqcQ2hy3r9%2FE7tcV9cxyJVh0GWY8XRFP17J%2BQwFv0athDCkNMFxxKgSwZzuSBPSMYbE6CFdupJxCvOWrwMLEsphv6QFaYkgiupjHmZIMF5lBDVfjpEJtuQyLwPEZL2XULeoJYKDYUriwoAsUCQRdeXFOK4oQs9rOaEOF4mfKEvOBnnGRKklGWCjnTrFCIDKqHxVzg3XcRswoeQN%2BYwX1yQMNUHZyhoi6XtrrcHnRSqCEsacTJg0hpMyiGPvADBUVRM125bEp0ASvPKIkXmO%2Fv8onAH0cnb0siqJDry%2FyV%2FfFjUmd5VeoGo6ty5%2Bjc1WkogRczEon9dO7UcO9qbDAuQhawCNEyH60wKvlME0gDt4KR5TRhpEPkdYGQbkZzHCUMRGxyjHwSBccQk89NwMMnlAQRxBZMCLaBikQgLiYyLUjkYHSI4cjPIwvKluu8mcpFXoEm9mupAloFWFQ5bYMvxxQJkHo1WTXApbo%2BSQEceOmNzWZi8iESlvIlVr1qoBe30YoHnYYzTUbLID9t59oZY6RxOUOUTmGb8uG3%2Be9ffjlrQTUsHsCCv36FQM%2Fsm6adR%2F6WMPZNZ5AHSjyW8NUWWQt037ieBlbV6GzbbbWetIGG5omBMsPoYmGObyODHJd78fwFHu0yyLADtVv6%2FujGM8j4WnovLKagxb5U%2FrD0nc4DYzFkAbSRXh0tkvhENvjI0QaftvoO5FozZ6tpT%2Bg1yNVyu9Cr26RX%2FxEnCRwxPzyhV8qQ351J74j4unfk8WisrjOHtmDbl12fa9BVWbvNmJdAzTF9o6xtZ9D3Sp9xXeT9M229fs4r9nrd27o11H3dmUy%2BpRxD1%2F1OyvycLvT91P0LcNBYc2xt%2FX93Wu57ns0tfav1Ptl5eBQj7XxntcrOeaJ60%2FnOfrPOf6r66q8t9BT1LrLOpr3J1xa6fV8yibdNyNfJvlXYh1a7lxInD1HaQN1l24YjMcci5fLVBVt3RheLMVRNfZSE2Ff9oPr06eDyRwEN7NGZrGn01wfqkDVPY%2B0%2Fc6Zw3WueKW7Er48jNNBemlzvJUGeGpoMQL4X%2BwEcQIN%2FdOYpqe4A2kDdOYCjO0C%2BU%2FTJS4Wp4T%2Bp%2FAJ1CvoUPZRRNIEWFK%2FEoTbfXa4RSgRPY2M0Q5GPeYKlEnwSEIFoPgXc3X6W%2FHjVxcRNx7bLzfZl736yfo7XsKFOoHRHUACuqLvo5W7jTwCYMNXE6puXnGuSilA6lmwxnT9ecqo7JBS69rhnej14Nu82tFMzsf2PEwo%2FunwudKq50LPa5sL691strB4uDz%2BdyCzm8PsU5%2F5f).

De bestilte varer ankom idag, men havde dog glemt at bestille PSU og SD kort.
Bestilte PSU og SD kort fra Proshop, de skulle gerne ankomme imorgen.

## Tirsdag 04-09-2018
