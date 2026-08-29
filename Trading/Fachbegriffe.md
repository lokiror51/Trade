# Grundbegriffe

**Long** - der Preis steigt
**Short** - der Preis fällt
**Entry** - Einstiegspunkt in einen Trade
**Exit** - Ausstiegspunkt aus einem Trade

-------------------------------------------------------------------

# Risiko-Management

**Stop Loss (SL)** - vorher festgelegter Preis, bei dem der Trade automatisch geschlossen wird, wenn er in Gegenrichtung läuft
**Take Profit (TP)** - das vorher festgelegte Gewinnziel
**Risk** - das Risiko, das man bei einem Trade eingeht

**R / R-Multiple** - R steht für die ursprüngliche Risikoeinheit
*Beispiel:*
*Man riskiert 50€.*
*1R = 50€*
*2R = 100€*
*3R = 150€*
*-1R = -50€*
*Bei 150€ Gewinn: +3R*

**Risk-Reward-Ratio (RRR)** - Verhältnis zwischen Risiko und möglichem Gewinn.
*Beispiel:*
*Man riskiert 100€ und will 300€gewinnen*
*Risk : Reward = 1 : 3*
*Man riskiert also 1R, um 3R zu gewinnen*

# Ein wichtiger Grundsatz:
## Beim Trading sollte man nicht zuerst denken:
> „Wie kann ich möglichst viel Gewinn machen?“
## Sondern:
> „Wie viel bin ich bereit zu verlieren, wenn meine Idee falsch ist?“
## Das ist der Kern von Risk Management. Ohne gutes Risk Management kann selbst eine profitable Strategie langfristig zum Problem werden.

--------------------------

# Positionsgröße und Hebel

**Position Size** - Wie groß der Trade tatsächlich ist
*Beispiel:*
*Ein Konto mit 1000€.*
*Man möchte max. 1% riskieren*
*1% von 1000€ = 10€
*Die Positionsgröße wird dann so gewählt, dass das Stop Loss max. etwa 10% Verlust verursacht.*

**Leverage / Hebel** - mit Hebel kann man eine größere Position kontrollieren, als das eigene Kapital eigentlich erlauben würde.
*Beispiel:*
*10x Hebel*
*1000€ Kapital -> theoretisch 10000€ Positionswert.*
***Wichtig:***
***Hebel macht nicht automatisch einen Trade besser. Er erhöht vor allem Geschwindigkeit, mit der Gewinne und Verluste entstehen können.***

**Margin** - Das Kapital, das als Sicherheit für eine gehebelte Position hinterlegt wird.

---------------

# Analyse und Chartbegriffe

**Timeframe** - der Zeitraum einer Kerze
*Typische Timeframes:*
- *1m*
- *5m*
- *15m*
- *1h*
- *4h*
- *1D*
***Wichtig: ein Markt kann auf verschiedenen Timeframes völlig unterschiedlich aussehen***

**Trend** - die grundsätzliche Richtung eines Marktes
***Uptrend: Höhere Hochs** + höhere Tiefs*
***Downtrend:** tiefere Hochs + tiefere Tiefs*
***Range:** Preis bewegt sich überwiegend seitwärts*

**Support** - ein Preisbereich, an dem Käufer in der Vergangenheit häufig aktiv wurden
*"Hier könnte der Preis Unterstützung finden"*

**Resistance** - ein Preisbereich, an dem Verkäufer häufig aktiv wurden
*"Hier könnte der Preis auf Widerstand stoßen"*

--------------

# Order-Begriffe

**Market Order** - Du kaufst/verkaufst sofort zum aktuellen verfügbaren Preis
**Limit Order** - Du legst einen Preis fest, zu dem zu kaufen/verkaufen möchtest
**Stop Order** - eine Order wird erst aktiviert, wenn ein bestimmter Preis erreicht wird
**Trading Session** - Zeitraum, in dem ein Markt normal gehandelt werden kann.
**Off trading session** = Der Markt befindet sich gerade außerhalb dieser Zeit.

**Spread** - Der Unterschied zwischen:
Bid = Preis, zu dem man verkaufen kann
Ask = Preis, zu dem man kaufen kann
*Die Differenz nennt man **Spread***
*Je kleiner der Spread, desto günstiger ist der Einstieg normalerweise.*

**Slippage** - man erwartet beispielsweise einen Einstieg bei 100 €, bekommt aber tatsächlich 100,20 €.
*Das kann bei besonders hoher Volatilität oder geringer Liquidität auftreten.*

----------------

# Backtesting & Trading-Journal

**Backtesting** - Eine Trading-Strategie wird auf historischen Kursdaten getestet
*Beispiel:*
*Man hat eine Strategie:*
> "Wenn Bedingung A + B + C auftreten -> Long"

*Man geht historische Charts durch und überprüft:*
- Wie oft wäre die Strategie erfolgreich gewesen?
- Wie oft hätte sie verloren?
- Wie hoch wäre der durchschnittliche Gewinn?
- Wie groß wäre der maximale Drawdown?

**Forward Testing** - Man testet eine Strategie mit aktuellen zukünftigen Kursbewegungen, ohne echtes Geld oder zunächst mit Demo.

**Trading Journal** - man dokumentiert seine Trades.
*Zum Beispiel:*

| Punkt    | Beispiel             |
| -------- | -------------------- |
| Trade    | Long                 |
| Entry    | 100 €                |
| SL       | 95 €                 |
| TP       | 115 €                |
| Risiko   | 1R                   |
| Ergebnis | +3R                  |
| Grund    | Setup erfüllt        |
| Fehler   | zu spät eingestiegen |
*Ein gutes Journal hilft es zu erkennen:*
> *„Warum verliere ich Geld?“*
> *„Welche Setups funktionieren bei mir?“*

-----------

# Statistik der Strategie

**Expectancy** - eine der interessanteren Kennzahlen. Versucht zu beantworten:
> "Wie viel erwarte ich langfristig pro Trade?"

*Expectancy  = (Winrate * durchschnittlicher Gewinn) - (Lossrate * durchschnittlicher Verlust)*

*Beispiel:*
*50 % Gewinner*
*+2R durchschnittlicher Gewinn*
*50 % Verlierer*
*−1R durchschnittlicher Verlust*

*→ langfristige Erwartung:*
*+0,5R pro Trade*

**Drawdown** - der Rückgang des Kontos von einem vorherigen Hoch
*Beispiel:*

*10000€*
*-> 12000€*
*-> 9000€*

*Vom Hoch bei 12000€ auf 9600€:*
*-20% Drawdown*

-------
# Chart-Trading

**Liquidity** - Bereiche, an denen viele Order bzw. Stops liegen können
**Liquidity Sweep** - Der Preis nimmt Liquidität aus einem Bereich, z.B. indem er kurz über ein vorheriges Hoch läuft und anschließend zurückdreht.
**Breakout** - Der Preis durchbricht einen wichtigen Bereich.
**Fakeout** - Ein scheinbarer Breakout, der anschließend wieder zurück in den vorherigen Bereich läuft.
**Pullback** - Der Preis bewegt sich nach einem Impuls kurzfristig zurück.
**Retest** - Der Preis kehrt nach einem Breakout noch einmal zum durchbrochenen Bereich zurück.
**Momentum** - Stärke bzw. Geschwindigkeit einer Preisbewegung.
**Volatility** - Wie stark der Preis schwankt.
**Volume** - Wie viel gehandelt wurde.

**Market Structure** - Die Struktur des Marktes anhand von Hochs und Tiefs.

*Zum Beispiel:*

*HH → HL → HH → HL*

*= Higher High + Higher Low → typischer Aufwärtstrend.*


