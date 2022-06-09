# Praktická úloha &mdash; programování NodeMCU 1.0

Na této stránce naleznete zapojení a postup nastavení pro práci s&nbsp;vývojovou deskou NodeMCU 1.0 v&nbsp;hodinách Programování 1 na oboru Informační technologie na [Obchodní akademii, Vyšší odborné škole a Jazykové škole s&nbsp;právem státní jazykové zkoušky Uherské Hradiště](https://www.oauh.cz).

## Schéma zapojení úlohy:
![Zapojení úlohy](img/obvod.png)

![Elektrotechnické schéma zapojení](img/schema.png)

## Nastavení simulátoru TinkerCAD.com

Pro vyzkoušení doma můžete využít simulátor na [TinkerCAD.com](https://www.tinkercad.com).

Postup nastavení:

1. Přihlašte se nebo si vytvořte nový osobní účet<br />![Web TinkerCAD.com](img/tinkercad/tinkercad_010_login.png)<br />![Vytvoření osobního účtu](img/tinkercad/tinkercad_020_osobni.png)
<br />![Přihlášení](img/tinkercad/tinkercad_030_login-jmeno-helso.png)
1. Zvolte v&nbsp;levém menu záložku „Obvody“<br />![Záložka Obvody](img/tinkercad/tinkercad_040_obvody.png)
1. Jako základ použijte zapojení Arduino Uno s breadboardem (nepájivým polem)<br />![Základní nastavení - Arduino Uno + breadboard](img/tinkercad/tinkercad_050_arduino-breadboard.png)
<br />![](img/tinkercad/tinkercad_060_zapojeni.png)
1. Přetáhněte na plochu další prvky a vytvořte zapojení úlohy podle schématu:<br />
![Zapojení úlohy](img/obvod.png)
1. Přepněte se do záložky _Kód_. Zapište kód a spusťte simulaci!<br />_Arduino Uno má vstupně/výstupní piny označeny `A0`, `A1`,... místo označení `D0`, `D1`,&hellip; u NodeMCU. Zbytek kód pro naše účely je stejný._<br />![](img/tinkercad/tinkercad_070_kod-a-spusteni.png)