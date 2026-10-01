# /roast: Der Ideen-Rat

Claude stimmt dir standardmäßig zu. Dieser Skill macht das Gegenteil: Fünf Perspektiven zerlegen deine Idee, danach fällt ein Richter ein Urteil. LOS, UMBAUEN oder STOPP, dazu der billigste Test, mit dem du in 48 Stunden prüfst, ob du recht hast.

Ich nutze ihn, bevor ich Zeit und Geld in etwas Neues stecke.

## Was drin ist

| Ordner | Sprache | Befehl |
|---|---|---|
| `roast-de/` | Deutsch, mit Baukasten für eigene Perspektiven | `/roast-de` |
| `roast/` | Englisch | `/roast` |
| `roast-de/chat-prompt.md` | Deutsch, für alle ohne Claude Code | einfach kopieren |

## Installieren (Claude Code)

Im Terminal einmal ausführen:

```bash
git clone https://github.com/Pascal-code-code/roast-skill.git /tmp/roast-skill
mkdir -p ~/.claude/skills
cp -r /tmp/roast-skill/roast /tmp/roast-skill/roast-de ~/.claude/skills/
```

Danach Claude Code neu starten und `/roast-de deine Idee` tippen. Claude stellt dir vier Fragen, dann läuft der Rat.

## Ohne Claude Code (ChatGPT, Claude.ai, Gemini)

Öffne [`roast-de/chat-prompt.md`](roast-de/chat-prompt.md), kopier den Prompt-Block komplett und füg ihn in ein neues Gespräch ein. Nimm das stärkste Modell, das du hast. Schwache Modelle werden zu nett, und dann bringt der Rat nichts.

## Die fünf Perspektiven

1. **Gegner:** nimmt an, dass die Idee scheitert, und sucht den Grund.
2. **Verstärker:** baut den stärksten Fall dafür.
3. **Logiker:** prüft ohne Websuche, ob die Rechnung im Kern aufgeht.
4. **Rechercheur:** sucht Belege, Konkurrenz und Preise im Netz.
5. **Käufer:** spielt deinen Zielkunden und sagt, ob er zahlen würde.

Im deutschen Skill kannst du Perspektiven tauschen (Vertriebler, Rechner, Konkurrent, Bauherr, Der Faule) oder eigene bauen.

Fragen oder Ideen für neue Perspektiven? Mach gern ein Issue auf.
