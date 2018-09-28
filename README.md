# **Inleiding**

Dit convenant omvat de afsprakenset die deelfietsbedrijven onderling en met wederverkopers van deelfietsen of tussenpersonen afspreken om zo interoperabiliteit van deelfietsen in Nederland te realiseren.

Dit convenant is opgesteld door de 12 deelfietsbedrijven (de Initiatiefnemers) die op 30 januari 2018 de Intentieverklaring &quot;Overal een deelfiets&quot; hebben ondertekend. Het convenant is openbaar en elke relevante partij kan zich er aan conformeren.

**Overwegingen**

- Deelfietsen kunnen een grote bijdrage leveren aan stedelijke mobiliteit wat uit oogpunt van gemak, duurzaamheid en efficiënt omgaan met schaarse ruimte wenselijk is.
- Deelfietsen worden veel aantrekkelijker voor mensen als ze eenvoudig (zonder steeds opnieuw te registreren) te gebruiken zijn, ook als fietsen door verschillende leveranciers aangeboden worden
- De Gemeenten Amsterdam, Rotterdam, Utrecht, Den Haag en Eindhoven stellen interoperabiliteit van deelfietsen als voorwaarde voor het toelaten van de deelfiets binnen de gemeente.
- Dit convenant, zodra fase 3 gerealiseerd is, invulling geeft aan de voorwaarden die gemeenten stellen aan interoperabiliteit van deelfietsen

**Fasering**

De Initiatiefnemers willen interoperabiliteit in fasen realiseren, en hebben de volgende fasering benoemd en afgesproken, waarbij de uitwerking van deze versie van het convenant uitsluitend fase 1 betreft; de fasen:

1. Hetzichtbaar maken van het aanbod van deelfietsen (zoals fase 1 in intentie verklaring)
2. Aan zichtbaarheid een deeplink toevoegen zodat een fiets te huren is via de (bike) operator app. (fase 2)
3. In-app integratie zodat verschillende fietsen met één account te huren zijn (al dan niet via een maas-partij_). Fase 3 omvat de gehele intentieverklaring._

**Scope fase 1**

![alt text](https://raw.githubusercontent.com/openbikeshare/convenant/master/scope_fase1.png)

# Definities

| **Term** | **Definitie** |
| --- | --- |
| Partij | Bedrijf dat de rol vervult van Operator, Integrator of Provider en welke dit convenant naleeft. |
| Operator | De Partij met de rol Deelfietsen aan Eindgebruikers beschikbaar te stellen, deze fietsen te onderhouden en binnen de gemeentelijke vergunningsvoorwaarden beschikbaar te houden. |
| Integrator | De Partij met de rol een specifieke functie te vervullen voor Operator of Provider of beide |
| Provider | De Partij met de rol de Eindgebruiker een passend vervoersaanbod te bieden, waar de deelfiets onderdeel van uitmaakt (kan uitmaken). |
| Aanbod (van deelfietsen) | Beschikbare Deelfietsen, van één Operators, op een voor Eindgebruiker handige locatie in een specifieke mobiliteitsvraag van Eindgebruiker |
| Eindgebruiker | De persoon met een mobiliteitsvraag die gebruik maakt van een Deelfiets (of dit overweegt) |
| Deelfietsen | Fiets in eigendom van een Operator die onder voorwaarden (zoals een huurbedrag) beschikbaar en bruikbaar is voor Eindgebruikers |
| Locatie | Gebied waarbinnen het Aanbod van deelfietsen wordt opgevraagd en gebruikt door de Provider. Locatie kan een GPS locatie zijn met een straal daaromheen, maar ook een stad of een andere duiding van een gebied.  |



# Afspraken

Operator, Provider en Integrator spreken het volgende met elkaar af:

## Sectie A. Aanbod (Fase 1)

Artikel 1. Operator maakt zijn Aanbod van deelfietsen middels een gestandaardiseerde API bekend aan Provider. Provider kan hiermee de beste MaaS-reis voor de klant aanbieden. Voor het Aanbod van Operator gelden de volgende afspraken:

1. Het Aanbod is gebaseerd op de feitelijke beschikbaarheid van Deelfietsen van de Operator, waarbij Operator ernaar streeft:
    1. dat de beschikbaarheid maximaal 5 minuten geleden is vastgesteld;
    2. dat de beschikbaarheid voor 95% of beter betrouwbaar is;
    3. en dat de Deelfietsen in maximaal 5% van de gevallen een defect na vertrek blijkt te hebben.
2. Het Aanbod betreft beschikbaarheid van Deelfietsen op een (of op de gevraagde) Locatie.
3. Het Aanbod hoeft niet alle fietsen te tonen; fietsen die binnen een straal van 10 meter rondom een fiets staan, hoeven niet getoond (mag wel);

Artikel 2. Operator heeft een inspanningsverplichting om te zorgen voor voldoende zekerheid dat hetgeen is aangeboden in het Aanbod, ook volgens de afspraken in Artikel 1 worden waargemaakt.

Artikel 3. Provider mag het door Operator beschikbaar gestelde Aanbod alleen gebruiken voor het samenstellen van de beste MaaS-reis voor de klant.

Artikel 4. Provider heeft een inspanningsverplichting om te zorgen voor betrouwbare klanten, die zorgvuldig omgaan met gehuurde deelfietsen.

Artikel 5. Provider stelt periodiek en op verzoek data beschikbaar aan Operators over cumulatieve klantvraag op locaties (aantal geïnteresseerde klanten en hun bestemmingen). Op deze manier kunnen Operators bepalen hoe het aanbod verbeterd kan worden.
## Sectie B. Data-uitwisseling

Artikel 1. Partijen wisselen voor fase 1 en 2 gegevens uit via het GBFS+ protocol, zoals dat in de bijlage bij dit convenant is opgenomen en is gepubliceerd op [https://github.com/openbikeshare/gbfsplus](https://github.com/openbikeshare/gbfsplus), dan wel een latere versie van dit protocol; partijen committeren zich tot

1. Het implementeren nieuwe versies van het protocol;
2. Het ondersteunen oudere versies van het protocol na vaststelling van nieuwere protocollen.

Artikel 2. 
Elke Partij zorgt dat ze te allen tijde handelen in overeenstemming met alle relevante wet- en regelgeving (met inbegrip van de Algemene verordening Gegevensbescherming AVG). Elke partij zal dan ook (onder meer) een adequate privacy statement bieden die nauwkeurig en specifiek omschrijft hoe persoonsgegevens verwerkt worden.

Artikel 3.
Bij gebruik van een API en bij het uitwisselen van gegevens spreken Partijen af:
1. De gegevens zijn alleen voor eigen gebruik. De toegang tot gegevens mag niet aan andere partijen worden  doorgegeven.
2. Partijen zullen geen handelingen verrichten met de bedoeling om enig virus of defect (zoals Trojan horses, malware of enige andere kwaadaardige instrument) op de systemen of bij de Eindgebruiker te introduceren.
3. Partijen zullen jegens derden steeds handelen in overeenstemming met wettelijke vereisten, de openbare orde en de goede zeden.
4. Partijen zullen elkaars API, servers en netwerken niet overbelasten, onnodig belasten, verstoren of op enige andere wijze onheus gebruiken.
5. Partijen zullen niet proberen op enige wijze de broncode achter een API of koppelvlak te achterhalen, of om op basis van een API enige software kopieën te ontwikkelen (geen reverse-engineering).
6. Partijen zullen de vertrouwelijke informatie die gedeeld wordt (zoals: gebruiksgegevens voor software ontwikkelaars, gegevens van Eindgebruikers) vertrouwelijk behandelen en in een veilige omgeving bewaren. Partijen accepteren de ketenaansprakelijkheid jegens onderaannemers.

## Sectie C. Commerciële afspraken

Artikel 1. Provider verkrijgt met dit Convenant het recht en de plicht om bij het tonen van Aanbod het Merk (bestaande uit de naam én het logo) van de Operator te tonen.
1. Operator verstrekt aan Provider voor dit expliciete doel een niet overdraagbaar, niet exclusief en door Operator te allen tijde opzegbare licentie om dat Merk te gebruiken.
2. Provider toont merken van Operators non-discriminatoir, dus zonder onderscheid naar merk, ook niet mogelijke eigen merken van Provider.

## Sectie D.Ondertekening

Partijen verklaren zich aan bovenstaande afspraken te houden en daarmee interoperabiliteit van de deelfiets in Nederland te bevorderen. Aldus overeengekomen en ondertekend

Te:                             
Op:       

| Bim Bim Bikes | Handtekening |
| --- | --- |
| Flickbike |   |
| Datatour / Haagsche Stadsfiets |   |
| Mobike |   |
| Cykl |   |
| Emotion Sustainable Mobility |   |
| Donkey Republic |   |
| Urbee |   |
| Next Bike |   |
| De Witte Stad |   |
| GoBike |   |
|   |   |
