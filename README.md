# IUS domácí úloha

Úvod do softwarového inženýrství domácí úloha - ER diagram.

## Varianta zadání: SLA

Vytvořte ER diagram, který bude základem informačního systému pro sledování poskytovaných IT služeb (IS ITS) v IT firmě. Firma poskytuje IT služby svým zákazníkům, kterými jsou výhradně právnické osoby, o nichž potřebuje znát IČO (považujte ho za jednoznačně identifikující), obchodní název, sídlo, právní formu, předmět podnikání a bankovní účet, ze kterého platí za poskytnuté služby. Každá IT služba má svůj unikátní kód, název a popis. Pokud jsou obdobné služby poskytovány více zákazníkům, liší se minimálně svým kódem. V IT ITS mohou být uvedeny i služby, které ještě žádný zákazník nevyužívá. IT služby jsou zákazníkům poskytovány vždy na základě smlouvy (SLA -- Service Level Agreement), které je přiděleno jedinečné číslo a je o ní v IS ITS uvedeno datum uzavření, účinnost (od, do), na které IT služby se smlouva vztahuje, jaká je pro danou službu doba provozu, jaká je její dostupnost a kolik za garanci těchto parametrů zákazník měsíčně zaplatí. SLA dále pro každou službu definuje penále, které za nedodržení dostupnosti v daném měsíci připadne zákazníkovi. Částka penále se odvíjí od míry nedodržení dostupnosti, která bude definována jako interval dostupnosti v procentech. Pro automatizované vyhodnocení dostupnosti je třeba, aby v IS ITS byly zaznamenány výpadky služeb. Výpadky jsou v rámci jedné IT služby postupně očíslovány, je zaznamenán čas začátku a čas konce výpadku (čas zde chápeme v obecném smyslu, tedy včetně data) a případně poznámka k výpadku. Výpadek několika služeb současně bude zaznamenán jako několik výpadků. Informace o potenciálním zákazníkovi lze do IS ITS zadat dříve, než je s ním uzavřena první SLA.

## Komentář učitele

plati, pripade jsou redundantni

sluzba - vypadek ma byt 1: 0..n

dostupnost a penale se maji vztahovat k poskytovani sluzby

je vhodne rozlisit sluzbu a poskytovani sluzby