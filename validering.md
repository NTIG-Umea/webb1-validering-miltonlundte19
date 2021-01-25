<!--alla ändringar i deta dokument är tids årnad och för att veta vart det är gå till komiten som texten blev tilagd.-->
fiksade till teken (å,ä,ö) (kopierade över från github)
fiksade länkningen i början av cåden genom att seta # framför id. som gör så att den lenkar i dokumentet i stele fer att gå till en ett anat fill. 
fixade en länk längre ner i dokumentet genom att seta "> i slutet av <a> elementet och hede > i slutet av ( <!- - slut main -- ) så att restan av dokumentet inte skule bli grönt.
när jag "spesade" p elementerna såg jag att det äe visa som saknar en eller båda sider na av elle menntet.
en länk lengre ner saknade slut blok som gjorde att myket av teksten hamnade i sama länk.
länken till lansstyrelsen naturreservat sida om Döda fallet fungerade inte nog för att man kunde bara ta bort det som stod efter > och den men länken blir retare setet som jag gjorde eftersom att nu har den faktiska länken som det blir i slutet. 
byte namn på ena av bilderna så att det blir letare att länka till bilden också försökte jag fiksa background-image men har inte lykats (komer till baka till deta.)
skapade en GitHub Pages och sedan anvende jag en html validator (https://validator.nu/) och börjar fixa fel som den spotar utt som jag inte ser.
leäkarna i navet hade inget <li> element som deom ska ha efter som dom är i en lista/<ul> element.
texten åvanför bilden hade två olika element ( började med ett <h3> och slutade på en <h2>) fixade genom att byta till en <h3> element.
endrade "namne" på sidan så att det kommer att stå Döda fallet istele för dokument.
hede till <meta charset="UTF-8"> så att den vet att det är utf-8.
lade till lang="sv" på första <html> så att när man ladadr in sidan så förstår den att det är skriven på svenska.
tog bort ett li slut element som inte anvends längre.
jag fixade till bilden på läget till böda falet genom att typ ta cåden från wikipedia och endra om den lite eftersom att jag vile ha den röda priken också. 
så jag hitade elementen för bilden på wikipenia, kopy paistade den på platsen som bilden var normalt, tog bort kåd som inte behövs/anvens för något, endrade urlen till bilderna så att det inte till wikis bilder utan bilderna i mapen och så hede jag in en ny bild för röda priken (Reddot.png). 
städade upp kåden runt bilden med validator.
H1 elementet i början av kan inte ha atrebuten center så jag tog bort den.
fixade tidsinheter vid (1720-1799) genom att seta dit två time eftersom att det verkar som att time är bara för ett datom.

2021-01-18
Endrade upplösningen och storleken på bakrundsbillden så att man kan lada in den på semre nätverk.
fisade ett stavfell på <paddin-top:> som ska stå <padding-top:> (saknar ett g)
fixade fel som hanlade med css kåden som att man ska ha en "enhet" bakom sifrorna som <rem> så att den vet vilken storleks skalning den ska anvenda också endrade jag en < till , för att få den att fingera
fiksade en css bit för att gjöra en bitenstrek för h2 ellementen också satte jag en margin-rite på en av dem så att streket inte skule vara bakom bilden
fiksade bakrunds bilden genom att endra derektivet från att den inte skule söka i <stylesheets> genom att setta ../ i början av sökvägen för bilden så att den söker från början mapen/hella "mapen". 
fiksade också så att det blir en anan ferg vid fottern men jag utökade den att ha refrensen med sej också. men main hade en pading så jag endrade main ellementet så den hade två div och så skapade jag en ny clas för att få till baka padingen på resten av teksten. sate en pading-boten på fotern så att det ska vara lite mer rum till slutet av dokumentet.

2021-01-25
fiksade style på topen av texten genom att ta bort marginen på topen av <h1> ellementet och sate dit en på sidan så att den ska laina upp med resten av texten också sate jag en pading på topen av elimente.
