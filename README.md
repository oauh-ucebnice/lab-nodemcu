# Praktická úloha &mdash; čidlo vlhkosti a teploty DHT11

Na této stránce naleznete zadání úkolu zprovoznění čidla a teploty DHT11 s počítačem Arduino Uno. Úlohu využíváme v&nbsp;hodinách Praktického projektu na oboru Informační technologie na [Obchodní akademii, Vyšší odborné škole a Jazykové škole s&nbsp;právem státní jazykové zkoušky Uherské Hradiště](https://www.oauh.cz).

## Úkoly

1. Zprovoznit blikání jedné diody

2. Vytvořit „animovaný blinkr“ se třemi diodami

3. Zprovoznit čidlo teploty a vlhkosti DHT11/DHT22

4. Challenge: 
  - Když teplota na čidle přesáhne 22 °C, rozsviťte červenou diodu
  - Když vlhkost na čidle přesáhne 55 %, rozsviťte žlutou diodu  
    (Můžete nasimulovat tak, že na čidle podržíte prst &mdash; nedýchejte na něj!!!)
	

### Důležité:

> !!! Než připojíte elektřinu, ukažte zapojení učiteli!!!

### Další pravidla: 

- Použijte libovolné zdroje.
- Použijte stavebnici.

## Nastavení simulátoru TinkerCAD.com

Pro vyzkoušení můžete využít kromě hardwarového zařízení i simulátor na [TinkerCAD.com](https://www.tinkercad.com).

### Postup nastavení:

1. Přihlašte se nebo si vytvořte nový osobní účet<br />![Web TinkerCAD.com](img/tinkercad/tinkercad_010_login.png)<br />![Vytvoření osobního účtu](img/tinkercad/tinkercad_020_osobni.png)
<br />![Přihlášení](img/tinkercad/tinkercad_030_login-jmeno-helso.png)
1. Zvolte v&nbsp;levém menu záložku „Obvody“<br />![Záložka Obvody](img/tinkercad/tinkercad_040_obvody.png)
1. Jako základ použijte zapojení Arduino Uno s breadboardem (nepájivým polem)<br />![Základní nastavení - Arduino Uno + breadboard](img/tinkercad/tinkercad_050_arduino-breadboard.png)
<br />![](img/tinkercad/tinkercad_060_zapojeni.png)
1. Přetáhněte na plochu další prvky a vytvořte zapojení úlohy podle schématu:<br />
![Zapojení úlohy](img/obvod.png)
1. Přepněte se do záložky _Kód_. Zapište kód a spusťte simulaci!<br />_Arduino Uno má vstupně/výstupní piny označeny `A0`, `A1`,... místo označení `D0`, `D1`,&hellip; u NodeMCU. Zbytek kód pro naše účely je stejný._<br />![](img/tinkercad/tinkercad_070_kod-a-spusteni.png)

### Sdílení řešení:
1. Nastavte viditelnost a odešlete odkaz pro sdílení:<br />
    ![Vytvoření odkazu pro sdílení](img/tinkercad/tinkercad_080_sdileni.png)