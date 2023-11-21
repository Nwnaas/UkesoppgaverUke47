# UkesoppgaverUke47

👨‍🎨 Oppgave 1: Java

# Temperatur

Det skal lages et klient-tjener-program som svarer med  gjennomsnittstemperaturen for Oslo for en gitt måned. Det skal kunne skrives inn en måned på nettsiden, denne skal så overføres til server når en knapp trykkes.  På server skal det ligge et array med tolv temperaturer (én for hver måned). Den tilsvarende temperaturen skal så overføres tilbake til get-kallet i klienten og vises på nettsiden.

En HTML-fil (index.html) skal inneholde all klientkode og det skal opprettes en controller på server med en get-metode.

Bruk følgende kode for å opprette arrayet på server:

private final Integer[] tempArray = new Integer[]{-3,-2,2,7,12,16,18,17,12,7,3,-2};
Bruk videre en switch for å "oversette" månedsnavn til array-indeks.

🧜‍♀️ Oppgave 2: Morsom oppgave

Del 1:

Lag et program som implementerer matematikkleken FizzBuzz.
Presentasjon av resultatet er uviktig, og et konsoll-vindu er tilstrekkelig.


Del 2:

Nye krav har tilkommet, og det er varslet at flere nye endringer kommer i fremtiden.
Foreløpig er nye krav: Kjør "FizzBuzz" som vanlig fra 1-100.
Deretter skal det kjøres fra 100 til 1 med nye regler som erstatter Fizz og Buzz.
"Jazz" for tall som er delelig med 9, og "Fuzz" for tall som er delelig med 4.
