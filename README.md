# VERIFICA TPSI: AWS, HTML5, deploy

Benvenuti alla verifica scritta di TPSI. Buon lavoro!

## Panoramica del compito
Il compito è diviso in tre fasi:
1. avvio di una macchina EC2 su AWS
1. modifica di una pagina web in locale
1. deploy della pagina web sull'istanza EC2

Ci sono due file che differiscono unicamente per il wireframe che dovrà essere implementato nella seconda parte del compito:
- FILA A: https://wireframe.cc/pro/pp/9ec31bf6e287392
- FILA B: https://wireframe.cc/pro/pp/4b8694764287397


## Operazioni preliminari
Accesso ad AWS:
- accedete alla [pagina di login](https://www.awseducate.com/signin/SiteLogin) di AWS Educate
- quando create una nuova istanza, **create una nuova chiave** con il nome **cognome-verifica**; questa chiave dovete metterla sotto revisione su github in modo che io possa accedere alla vostra istanza!
- per le operazioni di configurazione potete usare gli appunti a [questo](https://github.com/wbigger/tpsi-5y/) indirizzo

Sviluppo web locale:
- accedete con il vostro account personale a GitHub (**non sbagliate password!**)
- fate il fork di questo progetto, ma **attenzione**: se vi viene chiesto, fate il fork sul vostro account personale e non sull'organizzazione del progetto di classe
- copiate l'URL del **vostro** progetto
- aprite Visual Studio Code
- fate il clone del progetto
- premete sul pulsante "Go Live" nella barra blu in basso
- a questo punto avete la pagina di riferimento aperta sul vostro browser e potete cominciare lo sviluppo

## Note
Attenzione: alla fine della verifica, **non** fermate o terminate l'istanza da voi generata perché mi servirà per la correzione!

Testate il vostro progetto il più spesso possibile per controllare che non sia corretto.

**È possibile** consultare w3school o altri siti di esempio.

Al contrario, **non è possibile** comunicare o copiare dai compagni di classe.

Almeno 5 minuti prima della fine verifica, fate il commit e push di tutte le modifiche in locale. Consigliamo comunque di fare commit e push molto spesso durante la verifica (anche ogni 10 minuti), per evitare di perdere punti.

## Calcolo del punteggio
Tutte le seguenti voci valgono **1 punto**.
Voto massimo: 10.
Per avere il massimo del voto bisogna avere il massimo del punteggio.


### Punti generali
- [ ] corretta indentazione di tutti i file
- [ ] codice che compila senza errori nella console del browser

### Parte prima: AWS
- [x] creare una istanza per uso generale, che abbia almeno 2GB di RAM e senza particolari requisiti per la CPU, lo storage e le prestazioni di rete
- [x] configurare l'istanza in modo da accettare chiamate HTTP, HTTPS e MYSQL
- [x] connettersi all'istanza e configurare il web server nginx
- [x] la pagina di default del web server è correttamente visulizzata nel browser del proprio computer di sviluppo

### Parte seconda: sviluppo web in locale
- [x] modifica del titolo della pagina in "Innovative Lab - Marconi Civitavecchia"
- [x] menu a sinistra con voci corrette
- [x] intestazione della pagina corretta
- [x] creazione di una card con il titolo corretto
- [x] slidebar/bottoni all'interno della card
- [x] creazione corretta di tutte e cinque le card
- [x] crezione di due screenshots, uno per desktop e uno per smartphone, e caricaramento su git
- [x] corretta capitalizzazione di tutti i testi


### Parte terza: deploy
- [x] download del progetto web sull'istanza
- [x] corretto deploy del sito nell'istanza
- [x] pagina visualizzabile da browser con dns pubblico


