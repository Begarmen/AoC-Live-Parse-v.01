# Ashes of Creation — Riverlands (fan recreation)

Ricreazione giocabile e non ufficiale della zona iniziale **Riverlands** di *Ashes of Creation*, in un unico file `index.html` (three.js + WebGL).
Tutti i modelli, le texture, le icone e i suoni sono generati proceduralmente nel codice: nessun asset originale del gioco è incluso.

## Come si avvia
Apri `index.html` con un doppio clic in Chrome, Edge o Firefox. Serve internet perché three.js e i font vengono caricati da CDN.
Il personaggio viene salvato nel browser (localStorage): al riavvio compare il pulsante **Continue**.

## Cosa c'è
- **Mappa** ricostruita sulla mappa community della Riverlands: fiumi, lago di Joeva, costa a sud, strade, confini di regione, zone con i livelli (Goblinos 1-6, Spiders 6-9, Highwaymen 10-15, Minotaurs, Halls, Church, Estates, Bears, Steelbloom, Oaken, Carphin, Shardlings, Sephillon…).
- **Insediamenti**: Lionhold (campo avanzato Kaelar), Samia's Hope, Winstead, Miraleth, Joeva, con NPC, guardie, mercanti e stalliere.
- **Ranger** con 12 abilità (Piercing Shot, Barbs, Scatter Shot, Snipe, Hunter's Mark, Vine Field, Rapid Fire, Thundering Shot, Disengage, Bear Trap, Call of the Wild, Raining Death), auto-attacco, punti abilità (`K`), pozioni, razioni, ritorno a Lionhold.
- **HUD** in stile Ashes: ritratto con barre vita/mana/stamina, minimappa con bussola e orario, tracker missioni, doppia barra abilità (`1-6 R T F G C V` e `Shift+…`), chat con schede General/Social/Combat/Trade/LFG, barra XP, bersaglio, nameplate, testo di combattimento.
- **17 missioni** (tra cui *Sweat of Your Brow*, che dà la cavalcatura, *Changing Tides*, *Goblin Hunt* e *Riverlands' Bounty*), raccolta di legno/rame/fiori, bottino, venditori, elite e boss (Gnashgut) con attacchi ad area telegrafati, ciclo giorno/notte, nuoto e cavalcatura.

## Comandi
| Tasto | Azione |
|---|---|
| `W A S D` | Muoversi · trascina il mouse per ruotare la camera · rotella per lo zoom |
| `Tab` / click | Selezionare un bersaglio |
| `1-6 R T F G C V` | Abilità del Ranger |
| `Shift+1…5` | Pozione vita, pozione mana, razione, ritorno a Lionhold, tracciamento |
| `Spazio` · `Shift` · `Q` | Salto · scatto · schivata |
| `E` | Parlare / raccogliere / saccheggiare |
| `Alt` o `X` | Cavalcatura · `Z` estrai/rinfodera l'arco |
| `M B K L H` | Mappa · borsa · abilità · diario · comandi |
| `Invio` · `Esc` | Chat · menu (grafica Low/Medium/High, audio, sensibilità) |

Progetto amatoriale senza scopo di lucro, non affiliato con Intrepid Studios.
