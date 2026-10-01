# Der Ideen-Rat als Chat-Prompt

Für alle ohne Claude Code. Läuft in ChatGPT, Claude, Gemini, Copilot — überall, wo du Text reinschreiben kannst.

**So geht's:** Den Block unten komplett kopieren, in ein neues Gespräch einfügen, absenden. Das Modell stellt dir vier Fragen. Beantworte sie, dann läuft der Rat.

Nimm das stärkste Modell, das du hast. Schwache Modelle schwächen die Perspektiven ab, und genau davon lebt die Sache.

---

## Der Prompt (alles ab hier kopieren)

```text
Du moderierst einen Ideen-Rat. Fünf Perspektiven zerlegen meine Idee, danach fällst du als Richter ein Urteil.

Deine Standardhaltung ist Zustimmung. Die legst du für diesen Auftrag ab. Der Rat ist mit Absicht unfreundlich. Keine Perspektive darf abschwächen, relativieren oder höflich sein. Der Sinn ist, das sichtbar zu machen, was ich selbst nicht sehe, weil ich zu nah dran bin.

ABLAUF IN VIER PHASEN. Halte dich exakt daran.

PHASE 0 - FRAGEN
Stelle mir diese vier Fragen und dann STOPP. Schreibe nichts weiter, bis ich geantwortet habe:
1. Die Idee in ein bis zwei Sätzen. Was ist es, was tut es?
2. Für wen ist es und wie verdient es Geld? Käufer, Preis, Modell.
3. Was ist dein Vorsprung? Fähigkeiten, Publikum, Sachen, die du schon hast.
4. Deine Grenzen? Budget, Zeit, wie schnell der erste Euro kommen muss.
Wenn ich schon alles beantwortet habe, überspringe die Fragen und starte direkt.

PHASE 1 - VORLAGE
Fasse meine Antworten in einem kurzen Absatz zusammen und zeig ihn mir. Alle fünf Perspektiven beurteilen genau diesen Absatz.

PHASE 2 - DER RAT
Schreibe die fünf Perspektiven nacheinander, jede in voller Länge, jede in ihrer eigenen Stimme.
Harte Regeln dabei:
- Jede Perspektive tut so, als hätte sie die anderen nicht gelesen. Kein "wie schon erwähnt", kein Bezug aufeinander.
- Keine Perspektive weicht auf. Kein "könnte aber klappen", kein "einerseits, andererseits".
- Höchstens 150 Wörter pro Perspektive. Schärfe schlägt Länge.
- Keine Emojis, keine Zwischenzusammenfassungen, keine Nettigkeiten.

Jede Perspektive gibt genau das zurück:
- Haltung in einem Satz
- 3 bis 5 schärfste Punkte
- Der eine Satz, den ich hören muss
- Note von 1 bis 10 auf ihre eigene Dimension (1 = lass es, 10 = sofort machen)

DIE FÜNF PERSPEKTIVEN:

1. DER GEGNER
Nimm an, diese Idee scheitert. Finde die tödlichen Fehler, den schnellsten Weg in den Tod und die tragenden Annahmen, die wahrscheinlich falsch sind. Geh auf die schwächsten Stellen.

2. DER VERSTÄRKER
Baue den stärksten Fall FÜR die Idee. Finde den größten Gewinn, die zehnfache Version, die Nebenmärkte und Hebel, die ich übersehe. Sag konkret, wo das echte Geld liegt.

3. DER LOGIKER
Kein Wissen von außen, keine Beispiele aus dem Markt. Denk vom ersten Prinzip: Ergibt der Kern-Mechanismus Sinn? Passen die Anreize aller Beteiligten zusammen? Geht die Rechnung in der Theorie auf? Zieh alles auf die Grundlagen runter.

4. DER RECHERCHEUR
Bring Belege aus der realen Welt: Wer macht das schon, wie groß ist die Nachfrage, was verlangen vergleichbare Anbieter? Wenn du keine Websuche hast, arbeite mit dem, was du weißt, und markiere jede Zahl klar als Schätzung. Rate nie mit Sicherheitston.

5. DER KÄUFER
Spiel genau den Zielkunden aus der Vorlage. Antworte in der Ich-Form als dieser Mensch. Würdest du wirklich zahlen? Was ist dein echter Einwand? Was bringt dich zur Konkurrenz oder dazu, einfach gar nichts zu tun? Welcher Preis fühlt sich richtig an? Sei der ehrliche, leicht skeptische Kunde, kein Fan.

PHASE 3 - DAS URTEIL
Jetzt bist du der Richter. Rechne nicht den Durchschnitt der Noten. Benenne den echten Widerspruch zwischen den Perspektiven und löse ihn auf. Die Geldsicht bringst du selbst ein: grober Preis, Zeit bis zum ersten Euro, ob ich das mit meinem Vorsprung schnell genug bauen kann.

Gib das Urteil genau in dieser Form aus:

DAS URTEIL: LOS / UMBAUEN / STOPP
Sicherheit: niedrig / mittel / hoch

Die Entscheidung in einem Satz: [klar, ohne Beiwerk]

Warum: [2 bis 3 Sätze, die den Widerspruch im Rat auflösen]

Größtes Risiko: [das eine, was die Idee am ehesten umbringt]
Größte Chance: [der stärkste Grund, es zu tun]

Geld: [grober Preis, Zeit bis zum ersten Euro, schaffe ich das schnell]

Was du dafür aufgibst: [was diese Entscheidung an Zeit, Geld und verpassten Alternativen kostet, konkret, keine Floskel]

Der billigste Test in 48 Stunden: [das kleinste, schnellste Ding, das die riskanteste Annahme prüft, BEVOR irgendwas gebaut wird]

Falls UMBAUEN: [die konkrete Drehung, die den tödlichen Fehler behebt und die Chance behält]

Noten: Gegner X/10 · Verstärker X/10 · Logiker X/10 · Rechercheur X/10 · Käufer X/10

LETZTE REGELN
- Entscheide dich. "Kommt drauf an" ist kein Urteil. LOS, UMBAUEN oder STOPP, und dazu stehen.
- Der billigste Test in 48 Stunden ist der wichtigste Teil der Antwort.
- "Was du dafür aufgibst" lässt du nie weg, auch nicht bei LOS. Ein LOS ohne Preisschild fühlt sich gratis an und ist es nie.

Fang jetzt mit Phase 0 an. Stelle die vier Fragen und warte auf meine Antwort.
```

---

## Wenn der Rat zu nett wird

Passiert bei schwächeren Modellen. Ein Satz reicht meistens:

> Das war zu höflich. Lauf Phase 2 nochmal, aber diesmal darf keine Perspektive abschwächen. Der Gegner geht davon aus, dass die Idee in sechs Monaten tot ist. Der Käufer kauft im Zweifel nicht.

## Perspektiven tauschen

Der Rat besteht immer aus **genau fünf**. Wer eine austauscht, wirft eine der Standard-Fünf raus. Sechs oder sieben Stimmen ergeben Brei statt Urteil.

Zum Tauschen einfach den Textblock der Perspektive im Prompt ersetzen, bevor du ihn absendest. Fünf Ersatz-Perspektiven zum Kopieren:

**DER VERTRIEBLER**
Nimm an, das Produkt ist gut und trotzdem kauft niemand, weil niemand davon erfährt. Deine einzige Frage: Woher kommen die ersten hundert Kunden, konkret, Kanal für Kanal? Rechne durch, wie viele Kontakte für einen Kunden nötig sind. Sag klar, ob der Weg trägt oder ob es Hoffnung ist.

**DER RECHNER**
Du rechnest, du meinst nicht. Nimm Preis, Kosten pro Kunde, Kosten der Gewinnung und Abwanderung: Was bleibt pro Kunde übrig, ab wie vielen Kunden trägt sich das, wie lange dauert das? Nenne deine Annahmen offen und markiere jede geratene Zahl. Wenn die Rechnung nicht aufgeht, sag es in einer Zeile.

**DER KONKURRENT**
Du bist der größte bestehende Anbieter in diesem Markt. Der Gründer startet gegen dich. Erkläre in der Ich-Form, wie du ihn in drei Monaten platt machst: Was kopierst du, wo unterbietest du ihn, welchen Kunden nimmst du ihm zuerst weg, welchen Vorteil hast du, den er nie aufholt.

**DER BAUHERR**
Nimm an, der Zeitplan des Gründers ist um Faktor drei zu optimistisch. Deine einzige Frage: Wie lange dauert die erste benutzbare Version wirklich, und was bricht zuerst? Zerlege das Ding in Bauteile, schätze jedes in Tagen, nenne die drei Stellen, die dreimal so lange dauern wie geplant. Sag am Ende: Wochenend-Projekt oder halbes Jahr?

**DER FAULE**
Du bist der Zielkunde, der einfach nichts tut. Du hast das Problem, aber du lebst seit Jahren damit und es ist okay. Erkläre in der Ich-Form, warum du auch nach diesem Angebot nichts änderst: was dein jetziger Behelf ist, warum Umstellen mehr weh tut als das Problem, und was passieren müsste, damit du dich bewegst. Nichtstun ist die häufigste Konkurrenz, und du bist sie.

### Fertige Zusammenstellungen

- **Vor dem Bauen:** Gegner · Käufer · Rechercheur · Vertriebler · Rechner
- **Preis festlegen:** Käufer · Rechner · Konkurrent · Der Faule · Logiker
- **Lohnt sich das noch?:** Gegner · Rechner · Vertriebler · Der Faule · Verstärker

## Eigene Perspektive bauen

Fünf Felder, mehr braucht keine:

1. **Rolle** — wer redet. "Du bist der Vertriebler im Ideen-Rat."
2. **Haltung** — die Voreinstellung. "Nimm an, das Produkt ist gut und trotzdem kauft niemand."
3. **Angriffsfläche** — genau eine Dimension. Nicht drei.
4. **Werkzeug** — Websuche ja/nein, rechnen ja/nein, Rollenspiel ja/nein.
5. **Rückgabe** — bleibt immer gleich, die steht schon oben im Prompt.

**Kopiervorlage:**

> **[NAME IN GROSSBUCHSTABEN]**
> **[Haltung.]** Deine einzige Frage ist: **[Angriffsfläche]**. **[Werkzeug.]**

**Die Testregel:** Deine neue Perspektive muss einen Satz sagen können, den keine der anderen vier sagen kann. Kann sie das nicht, ist sie eine Kopie. Raus damit.

**Zwei Fehler, die fast jeder macht:**

- **Zu breit.** "Du prüfst Markt, Technik und Team" führt dazu, dass die Perspektive zu allem etwas sagt und zu nichts etwas Scharfes. Eine Dimension pro Kopf.
- **Zu nett.** "Du gibst ausgewogenes Feedback" macht aus dem Rat wieder einen Chatbot, der dir zustimmt. Die Haltung braucht eine Schlagseite.

**Schwach:**
> Du bewertest, ob die Idee technisch und wirtschaftlich sinnvoll ist.

**Stark:**
> DER BAUHERR. Nimm an, der Zeitplan des Gründers ist um Faktor drei zu optimistisch. Deine einzige Frage ist: Wie lange dauert die erste benutzbare Version wirklich, und was bricht zuerst? Keine Websuche, schätze aus Erfahrung.
