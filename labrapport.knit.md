---
title: "Labrapport"
format: html
bibliography: molekylærlab.bib
csl: apa.csl
editor_options: 
  chunk_output_type: console
---




# Introduksjon

Analyser av genuttrykk gjennom fluorisens-basert sanntids kvantitativ polymerase kjedereaksjon (qPCR) er fast praksis i mange medisinske treningsstudier [@kuangOverviewTechnicalConsiderations2018]. qPCR benyttes til å måle uttrykket av et målgen i prøver fra blant annet blod og muskelvev. Et vanlig bruksområde innenfor treningsfysiologi er for eksempel å måle treningsinduserte endringer i genutrykk for ulike muskelfibertyper. Selv om denne typen analyse er svært utbredt, finnes det mange ulike protokoller og måter å gjennomføre analysen på. Reproduserbarheten og reliabiliteten til dataen avhenger i stor grad av hvordan eksperimentene gjennomføres og tolkes. For å sikre så reliable tester som mulig, er det viktig med en detaljert og nøye protokoll [@kuangOverviewTechnicalConsiderations2018].

Prinsippet bak en qPCR-analyse er å følge PCR i sanntid. For å gjennomføre PCR må vi først ekstrahere RNA fra en biologisk celleprøve. Deretter blir RNAet gjort om til cDNA i en prosesses kalt reversert transkripsjon. Med PCR blir dette cDNAet deretter amplifisert opp til milliarder av kopier [@kuangOverviewTechnicalConsiderations2018]. Hver syklus i en PCR er består av tre steg for å kopiere opp det aktuelle DNAet. I første steg (denaturering) blir DNAet utsatt for høy temperatur for å dele DNAet fra dobbeltrådet til enkelttrådet. I det andre steget (annealing) blir temperaturen senket og primere fester seg til templat-trådene. I det siste steget (elongering) øker temperaturen igjen og DNA-polymeraser fester seg til primerne og syntetiserer et nytt dobbelttrådet DNA, likt det vi startet med [@kuangOverviewTechnicalConsiderations2018]. Deretter vil denne syklusen repetere seg, slik at DNAet dobles ekspontensielt for hver syklus. I en qPCR som benytter SYBR green-metoden blir det aktuelle DNAet bundet til fluorosens under hver syklus slik at man kan følge PCR-prosessen i sanntid, ved å ta et bilde som detekterer fluorescensen etter hver syklus [@kuangOverviewTechnicalConsiderations2018]. Mengden cDNA og fluorescens dobles etter hver syklus, og signalet av fluorescens øker dermed eksponentielt. Hvor raskt signalet av fluorescens når en satt grense kalt syklisk terskel (CT), bedømmer hvor sort uttrykk av et gen vi har. Jo færre sykluser som må gjennomføres for å nå CT, jo større uttrykk av målgenet hadde vi i celleprøven vår [@livakAnalysisRelativeGene2001a].

# Metode

I forkant av forsøket hadde labansvarlig forberedt cDNA. qPCR-analyse ble gjort ved bruk av cDNA og en Master mix. Master mixen besto av 5μl Cybr-green, 1μl primer mix (MCH1, MHC2a, MCH2x eller MCHb2m) og 2μl H~2~O. På en plate med brønner ble det tilført 8μl Master mix i brønnene sammen med 2μl cDNA. I tillegg til dette lagde vi en fortynningsserie for å teste primerne. Fortynningene vi brukte var 1/1, 1/10, 1/100, 1/1000, 1/10000, 1/100000 og 1/1000000. I 1/1 prøven var det 2μl cDNA og 8μl cmyc. Fortynningsserien tok utgangspunkt i denne prøven og ble fortynnet med H~2~O. Platen ble så dekket med plast og sentrifiugert på 1200rpm i 1 minutt. PCR-prøvene ble analysert ved sanntids PCR (Applied Biosystems 7500 fast Real-TimePCR Systems, Life Technologies AS) og ved bruk av Quant Studio programvare (Applied Biosystems, Waltham, MA USA). PCR-prosessen besto av tre deler, en "Hold stage" en "PCR stage" og en "Melt curve stage". Det første steget gikk ut på at temperaturen økte med 1,99**°**C/s opp til 50**°**C hvor temperaturen forble konstant i 2 min. Videre Økte temperaturen med 1,99**°**C/s opp til 95**°**C hvor temperaturen forble konstant i 2 min. Deretter startet selve PCR-prosessen som besto av 40 sykluser. Én syklus besto av 1 sek på 95**°**C før temperaturen sank med 1,77**°**C/s ned til 60**°**C hvor temperaturen ble holdt konstant i 30 sek. Etter hver syklus ble det tatt bilde av brønnenes fluorescens. Avslutningsvis økte temperaturen med 1,99**°**C/s opp til 95**°**C hvor temperaturen holdes konstant i 15 sek. Deretter synker temperaturen med 1,77**°**C/s ned til 60**°**C hvor temperaturen holdes konstant i 1 min. Temperaturen økte deretter med 0,15**°**C/s opp til 95**°**C hvor temperaturen ble holdt konstant i 15 sek. Etter PCR-prosessen var ferdig kunne vi hente ut resultatene i form av CT-verdier.

\newpage

# Resultat


::: {.cell}

:::

::: {.cell tbl-cap='Tabell 1 viser at mengden av de ulike muskelfibertypene har endret seg fra uke 0 til uke 2. Muskelfibertype 1 (MCH1) har sunket fra 35-27%, muskelfibertype 2a (MHC2a) har økt fra 0,6-72% og muskelfibertype 2x (MHX2x) har sunket fra 63-4%.'}
::: {.cell-output-display}
```{=html}
<div id="xmuawuppsx" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#xmuawuppsx table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#xmuawuppsx thead, #xmuawuppsx tbody, #xmuawuppsx tfoot, #xmuawuppsx tr, #xmuawuppsx td, #xmuawuppsx th {
  border-style: none;
}

#xmuawuppsx p {
  margin: 0;
  padding: 0;
}

#xmuawuppsx .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#xmuawuppsx .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#xmuawuppsx .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#xmuawuppsx .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#xmuawuppsx .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#xmuawuppsx .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#xmuawuppsx .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#xmuawuppsx .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#xmuawuppsx .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#xmuawuppsx .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#xmuawuppsx .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#xmuawuppsx .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#xmuawuppsx .gt_spanner_row {
  border-bottom-style: hidden;
}

#xmuawuppsx .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#xmuawuppsx .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}

#xmuawuppsx .gt_from_md > :first-child {
  margin-top: 0;
}

#xmuawuppsx .gt_from_md > :last-child {
  margin-bottom: 0;
}

#xmuawuppsx .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#xmuawuppsx .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}

#xmuawuppsx .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#xmuawuppsx .gt_row_group_first td {
  border-top-width: 2px;
}

#xmuawuppsx .gt_row_group_first th {
  border-top-width: 2px;
}

#xmuawuppsx .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#xmuawuppsx .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#xmuawuppsx .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#xmuawuppsx .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#xmuawuppsx .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#xmuawuppsx .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#xmuawuppsx .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}

#xmuawuppsx .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#xmuawuppsx .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#xmuawuppsx .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#xmuawuppsx .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#xmuawuppsx .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#xmuawuppsx .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#xmuawuppsx .gt_left {
  text-align: left;
}

#xmuawuppsx .gt_center {
  text-align: center;
}

#xmuawuppsx .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#xmuawuppsx .gt_font_normal {
  font-weight: normal;
}

#xmuawuppsx .gt_font_bold {
  font-weight: bold;
}

#xmuawuppsx .gt_font_italic {
  font-style: italic;
}

#xmuawuppsx .gt_super {
  font-size: 65%;
}

#xmuawuppsx .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#xmuawuppsx .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#xmuawuppsx .gt_indent_1 {
  text-indent: 5px;
}

#xmuawuppsx .gt_indent_2 {
  text-indent: 10px;
}

#xmuawuppsx .gt_indent_3 {
  text-indent: 15px;
}

#xmuawuppsx .gt_indent_4 {
  text-indent: 20px;
}

#xmuawuppsx .gt_indent_5 {
  text-indent: 25px;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_heading">
      <td colspan="3" class="gt_heading gt_title gt_font_normal gt_bottom_border" style>Tabell 1: Endring i muskeltype sammensetning Uke 0 og Uke 2</td>
    </tr>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="Fibertype">Fibertype</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="Uke 0">Uke 0</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="Uke 2">Uke 2</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="...18" class="gt_row gt_left">MHC1</td>
<td headers="...19" class="gt_row gt_right">35.43</td>
<td headers="...20" class="gt_row gt_right">27.33</td></tr>
    <tr><td headers="...18" class="gt_row gt_left">MHC-2a</td>
<td headers="...19" class="gt_row gt_right">0.61</td>
<td headers="...20" class="gt_row gt_right">72.21</td></tr>
    <tr><td headers="...18" class="gt_row gt_left">MHC-2x</td>
<td headers="...19" class="gt_row gt_right">63.96</td>
<td headers="...20" class="gt_row gt_right">4.61</td></tr>
  </tbody>
  
  <tfoot class="gt_footnotes">
    <tr>
      <td class="gt_footnote" colspan="3"> Tallene er i prosent</td>
    </tr>
  </tfoot>
</table>
</div>
```
:::
:::

::: {.cell tbl-cap='Tabell 2 viser at antall sykluser for å nå syklisk terksel (CT) har endret seg fra uke 0 til uke 2. Antall sykluser har sunket for muskelfibertype 1 (MCH1) fra 22-17 sykluser. For muskelfibertype 2a (MHC2a) har antall sykluser sunket 27-15 sykluser, og for muskelfibertype 2x (MCH2x) har antall sykluser til CT økt fra 21-23 sykluser.'}
::: {.cell-output-display}
```{=html}
<div id="mgtflsjlwq" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#mgtflsjlwq table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#mgtflsjlwq thead, #mgtflsjlwq tbody, #mgtflsjlwq tfoot, #mgtflsjlwq tr, #mgtflsjlwq td, #mgtflsjlwq th {
  border-style: none;
}

#mgtflsjlwq p {
  margin: 0;
  padding: 0;
}

#mgtflsjlwq .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#mgtflsjlwq .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#mgtflsjlwq .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#mgtflsjlwq .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#mgtflsjlwq .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#mgtflsjlwq .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#mgtflsjlwq .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#mgtflsjlwq .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#mgtflsjlwq .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#mgtflsjlwq .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#mgtflsjlwq .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#mgtflsjlwq .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#mgtflsjlwq .gt_spanner_row {
  border-bottom-style: hidden;
}

#mgtflsjlwq .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#mgtflsjlwq .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}

#mgtflsjlwq .gt_from_md > :first-child {
  margin-top: 0;
}

#mgtflsjlwq .gt_from_md > :last-child {
  margin-bottom: 0;
}

#mgtflsjlwq .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#mgtflsjlwq .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}

#mgtflsjlwq .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#mgtflsjlwq .gt_row_group_first td {
  border-top-width: 2px;
}

#mgtflsjlwq .gt_row_group_first th {
  border-top-width: 2px;
}

#mgtflsjlwq .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#mgtflsjlwq .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#mgtflsjlwq .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#mgtflsjlwq .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#mgtflsjlwq .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#mgtflsjlwq .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#mgtflsjlwq .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}

#mgtflsjlwq .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#mgtflsjlwq .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#mgtflsjlwq .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#mgtflsjlwq .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#mgtflsjlwq .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#mgtflsjlwq .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#mgtflsjlwq .gt_left {
  text-align: left;
}

#mgtflsjlwq .gt_center {
  text-align: center;
}

#mgtflsjlwq .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#mgtflsjlwq .gt_font_normal {
  font-weight: normal;
}

#mgtflsjlwq .gt_font_bold {
  font-weight: bold;
}

#mgtflsjlwq .gt_font_italic {
  font-style: italic;
}

#mgtflsjlwq .gt_super {
  font-size: 65%;
}

#mgtflsjlwq .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#mgtflsjlwq .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#mgtflsjlwq .gt_indent_1 {
  text-indent: 5px;
}

#mgtflsjlwq .gt_indent_2 {
  text-indent: 10px;
}

#mgtflsjlwq .gt_indent_3 {
  text-indent: 15px;
}

#mgtflsjlwq .gt_indent_4 {
  text-indent: 20px;
}

#mgtflsjlwq .gt_indent_5 {
  text-indent: 25px;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_heading">
      <td colspan="3" class="gt_heading gt_title gt_font_normal gt_bottom_border" style>Tabell 2: Vurdering av CT verdi</td>
    </tr>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="Fibertype">Fibertype</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="Uke 0">Uke 0</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="Uke 2">Uke 2</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="...27" class="gt_row gt_left">MHC1</td>
<td headers="...28" class="gt_row gt_right">22.04</td>
<td headers="...29" class="gt_row gt_right">17.29</td></tr>
    <tr><td headers="...27" class="gt_row gt_left">MHC-2a</td>
<td headers="...28" class="gt_row gt_right">27.91</td>
<td headers="...29" class="gt_row gt_right">15.89</td></tr>
    <tr><td headers="...27" class="gt_row gt_left">MHC-2x</td>
<td headers="...28" class="gt_row gt_right">21.19</td>
<td headers="...29" class="gt_row gt_right">23.19</td></tr>
  </tbody>
  
  <tfoot class="gt_footnotes">
    <tr>
      <td class="gt_footnote" colspan="3"> Tallene er antall sykluser før syklisk terskel er nådd</td>
    </tr>
  </tfoot>
</table>
</div>
```
:::
:::


### Effektivitet av Fortynningsserie 1/10 -- 1/100 -- 1/1000


::: {.cell}

:::

::: {.cell}
::: {.cell-output-display}
![](labrapport_files/figure-html/unnamed-chunk-6-1.png){width=672}
:::
:::

::: {.cell}
::: {.cell-output-display}
![](labrapport_files/figure-html/unnamed-chunk-7-1.png){width=672}
:::
:::

::: {.cell}
::: {.cell-output-display}
```{=html}
<div id="wolycjbqrq" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#wolycjbqrq table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#wolycjbqrq thead, #wolycjbqrq tbody, #wolycjbqrq tfoot, #wolycjbqrq tr, #wolycjbqrq td, #wolycjbqrq th {
  border-style: none;
}

#wolycjbqrq p {
  margin: 0;
  padding: 0;
}

#wolycjbqrq .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#wolycjbqrq .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#wolycjbqrq .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#wolycjbqrq .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#wolycjbqrq .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#wolycjbqrq .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#wolycjbqrq .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#wolycjbqrq .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#wolycjbqrq .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#wolycjbqrq .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#wolycjbqrq .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#wolycjbqrq .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#wolycjbqrq .gt_spanner_row {
  border-bottom-style: hidden;
}

#wolycjbqrq .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#wolycjbqrq .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}

#wolycjbqrq .gt_from_md > :first-child {
  margin-top: 0;
}

#wolycjbqrq .gt_from_md > :last-child {
  margin-bottom: 0;
}

#wolycjbqrq .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#wolycjbqrq .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}

#wolycjbqrq .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#wolycjbqrq .gt_row_group_first td {
  border-top-width: 2px;
}

#wolycjbqrq .gt_row_group_first th {
  border-top-width: 2px;
}

#wolycjbqrq .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#wolycjbqrq .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#wolycjbqrq .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#wolycjbqrq .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#wolycjbqrq .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#wolycjbqrq .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#wolycjbqrq .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}

#wolycjbqrq .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#wolycjbqrq .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#wolycjbqrq .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#wolycjbqrq .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#wolycjbqrq .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#wolycjbqrq .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#wolycjbqrq .gt_left {
  text-align: left;
}

#wolycjbqrq .gt_center {
  text-align: center;
}

#wolycjbqrq .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#wolycjbqrq .gt_font_normal {
  font-weight: normal;
}

#wolycjbqrq .gt_font_bold {
  font-weight: bold;
}

#wolycjbqrq .gt_font_italic {
  font-style: italic;
}

#wolycjbqrq .gt_super {
  font-size: 65%;
}

#wolycjbqrq .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#wolycjbqrq .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#wolycjbqrq .gt_indent_1 {
  text-indent: 5px;
}

#wolycjbqrq .gt_indent_2 {
  text-indent: 10px;
}

#wolycjbqrq .gt_indent_3 {
  text-indent: 15px;
}

#wolycjbqrq .gt_indent_4 {
  text-indent: 20px;
}

#wolycjbqrq .gt_indent_5 {
  text-indent: 25px;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_heading">
      <td colspan="5" class="gt_heading gt_title gt_font_normal gt_bottom_border" style>Tabell 3: Tall fra reaksjon Uke 0</td>
    </tr>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="Fortynningsserie">Fortynningsserie</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="Snitt CT">Snitt CT</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="Log">Log</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="Slope">Slope</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="Primer eff">Primer eff</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="Fortynningsserie" class="gt_row gt_right">1/1</td>
<td headers="Snitt CT" class="gt_row gt_right">27.45970</td>
<td headers="Log" class="gt_row gt_right">0</td>
<td headers="Slope" class="gt_row gt_right">-3.524092</td>
<td headers="Primer eff" class="gt_row gt_right">92.2034</td></tr>
    <tr><td headers="Fortynningsserie" class="gt_row gt_right">1/10</td>
<td headers="Snitt CT" class="gt_row gt_right">30.07881</td>
<td headers="Log" class="gt_row gt_right">-1</td>
<td headers="Slope" class="gt_row gt_right">NA</td>
<td headers="Primer eff" class="gt_row gt_right">NA</td></tr>
    <tr><td headers="Fortynningsserie" class="gt_row gt_right">1/100</td>
<td headers="Snitt CT" class="gt_row gt_right">34.50788</td>
<td headers="Log" class="gt_row gt_right">-2</td>
<td headers="Slope" class="gt_row gt_right">NA</td>
<td headers="Primer eff" class="gt_row gt_right">NA</td></tr>
    <tr><td headers="Fortynningsserie" class="gt_row gt_right">1/1000</td>
<td headers="Snitt CT" class="gt_row gt_right">NA</td>
<td headers="Log" class="gt_row gt_right">-3</td>
<td headers="Slope" class="gt_row gt_right">NA</td>
<td headers="Primer eff" class="gt_row gt_right">NA</td></tr>
    <tr><td headers="Fortynningsserie" class="gt_row gt_right">1/100000</td>
<td headers="Snitt CT" class="gt_row gt_right">NA</td>
<td headers="Log" class="gt_row gt_right">-4</td>
<td headers="Slope" class="gt_row gt_right">NA</td>
<td headers="Primer eff" class="gt_row gt_right">NA</td></tr>
    <tr><td headers="Fortynningsserie" class="gt_row gt_right">1/100000</td>
<td headers="Snitt CT" class="gt_row gt_right">NA</td>
<td headers="Log" class="gt_row gt_right">-5</td>
<td headers="Slope" class="gt_row gt_right">NA</td>
<td headers="Primer eff" class="gt_row gt_right">NA</td></tr>
  </tbody>
  
  <tfoot class="gt_footnotes">
    <tr>
      <td class="gt_footnote" colspan="5"> </td>
    </tr>
  </tfoot>
</table>
</div>
```
:::
:::

::: {.cell}
::: {.cell-output-display}
```{=html}
<div id="rhqrypepst" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#rhqrypepst table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#rhqrypepst thead, #rhqrypepst tbody, #rhqrypepst tfoot, #rhqrypepst tr, #rhqrypepst td, #rhqrypepst th {
  border-style: none;
}

#rhqrypepst p {
  margin: 0;
  padding: 0;
}

#rhqrypepst .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#rhqrypepst .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#rhqrypepst .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#rhqrypepst .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#rhqrypepst .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#rhqrypepst .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#rhqrypepst .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#rhqrypepst .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#rhqrypepst .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#rhqrypepst .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#rhqrypepst .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#rhqrypepst .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#rhqrypepst .gt_spanner_row {
  border-bottom-style: hidden;
}

#rhqrypepst .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#rhqrypepst .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}

#rhqrypepst .gt_from_md > :first-child {
  margin-top: 0;
}

#rhqrypepst .gt_from_md > :last-child {
  margin-bottom: 0;
}

#rhqrypepst .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#rhqrypepst .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}

#rhqrypepst .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#rhqrypepst .gt_row_group_first td {
  border-top-width: 2px;
}

#rhqrypepst .gt_row_group_first th {
  border-top-width: 2px;
}

#rhqrypepst .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#rhqrypepst .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#rhqrypepst .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#rhqrypepst .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#rhqrypepst .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#rhqrypepst .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#rhqrypepst .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}

#rhqrypepst .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#rhqrypepst .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#rhqrypepst .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#rhqrypepst .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#rhqrypepst .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#rhqrypepst .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#rhqrypepst .gt_left {
  text-align: left;
}

#rhqrypepst .gt_center {
  text-align: center;
}

#rhqrypepst .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#rhqrypepst .gt_font_normal {
  font-weight: normal;
}

#rhqrypepst .gt_font_bold {
  font-weight: bold;
}

#rhqrypepst .gt_font_italic {
  font-style: italic;
}

#rhqrypepst .gt_super {
  font-size: 65%;
}

#rhqrypepst .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#rhqrypepst .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#rhqrypepst .gt_indent_1 {
  text-indent: 5px;
}

#rhqrypepst .gt_indent_2 {
  text-indent: 10px;
}

#rhqrypepst .gt_indent_3 {
  text-indent: 15px;
}

#rhqrypepst .gt_indent_4 {
  text-indent: 20px;
}

#rhqrypepst .gt_indent_5 {
  text-indent: 25px;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_heading">
      <td colspan="5" class="gt_heading gt_title gt_font_normal gt_bottom_border" style>Tabell 4: Tall fra reaksjon Uke 2</td>
    </tr>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="Fortynningsserie">Fortynningsserie</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="Snitt CT">Snitt CT</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="Log">Log</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="Slope/stigningstall">Slope/stigningstall</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="Primer efficiency (%)">Primer efficiency (%)</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="Fortynningsserie" class="gt_row gt_right">1/1</td>
<td headers="Snitt CT" class="gt_row gt_right">28.69725</td>
<td headers="Log" class="gt_row gt_right">0</td>
<td headers="Slope/stigningstall" class="gt_row gt_right">-0.3741574</td>
<td headers="Primer efficiency (%)" class="gt_row gt_right">46962.15</td></tr>
    <tr><td headers="Fortynningsserie" class="gt_row gt_right">1/10</td>
<td headers="Snitt CT" class="gt_row gt_right">30.60317</td>
<td headers="Log" class="gt_row gt_right">-1</td>
<td headers="Slope/stigningstall" class="gt_row gt_right">NA</td>
<td headers="Primer efficiency (%)" class="gt_row gt_right">NA</td></tr>
    <tr><td headers="Fortynningsserie" class="gt_row gt_right">1/100</td>
<td headers="Snitt CT" class="gt_row gt_right">29.44557</td>
<td headers="Log" class="gt_row gt_right">-2</td>
<td headers="Slope/stigningstall" class="gt_row gt_right">NA</td>
<td headers="Primer efficiency (%)" class="gt_row gt_right">NA</td></tr>
    <tr><td headers="Fortynningsserie" class="gt_row gt_right">1/1000</td>
<td headers="Snitt CT" class="gt_row gt_right">NA</td>
<td headers="Log" class="gt_row gt_right">-3</td>
<td headers="Slope/stigningstall" class="gt_row gt_right">NA</td>
<td headers="Primer efficiency (%)" class="gt_row gt_right">NA</td></tr>
    <tr><td headers="Fortynningsserie" class="gt_row gt_right">1/100000</td>
<td headers="Snitt CT" class="gt_row gt_right">NA</td>
<td headers="Log" class="gt_row gt_right">-4</td>
<td headers="Slope/stigningstall" class="gt_row gt_right">NA</td>
<td headers="Primer efficiency (%)" class="gt_row gt_right">NA</td></tr>
    <tr><td headers="Fortynningsserie" class="gt_row gt_right">1/100000</td>
<td headers="Snitt CT" class="gt_row gt_right">NA</td>
<td headers="Log" class="gt_row gt_right">-5</td>
<td headers="Slope/stigningstall" class="gt_row gt_right">NA</td>
<td headers="Primer efficiency (%)" class="gt_row gt_right">NA</td></tr>
  </tbody>
  
  <tfoot class="gt_footnotes">
    <tr>
      <td class="gt_footnote" colspan="5"> </td>
    </tr>
  </tfoot>
</table>
</div>
```
:::
:::


Anbefalt primer effektivitet er mellom 93 % og 105 % (Kuang 2018). Dette viser at på tabell 2 er det en feil i fortynningsrekken. Muligens pipeteringsfeil da elab journal viste usikkerhet rundt hva som var pipettert i ett av kamrene.

# Diskusjon

# Konklusjon

\newpage

# Referanser

