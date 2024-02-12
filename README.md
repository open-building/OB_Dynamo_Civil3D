# Dynamo_Civil3D
<B>Dynamo Scripts for Civil3D</B><BR/><BR/>
Questa cartella contiene una libreria di script Dynamo per Civil3D a disposizione di tutti gli OpenBuilders e si arricchirà ogni qualvolta emergeranno nuove necessità di automazione dei processi progettuali. Potrete scaricare da qui lo script che vi serve e caricarlo in locale per utilizzarlo, segue una breve descizione di ciascuno script corredata dai parametri editabili nel player, la versione Civil e Dynamo e i packages necessari per un corretto funzionamento.

<H2>FeatureLine_Length</H2>
<B>Versione Civil3D:</B> 2022<BR/>
<B>Versione Dynamo:</B> 2.12<BR/>
<B>Packages:</B> Civil3D Toolkit<BR/>
<B>Parametri:</B> Seleziona FeatureLine<BR/><BR/>
Lo script automatizza la compilazione del parametro NR_LUNGHEZZA_TRATTA del PSET Fisico_Geometrico prelevando la misura dalla FeatureLine selezionata. Sviluppato per una applicazione specifica è comunque possibile prevedere a richiesta implementazioni più generaliste per determinare una denominazione variabile del campo di destinazione.<BR/>

<H2>FeatureLine_to_PipeRuns</H2><BR/>
<B>Versione Civil3D:</B> 2022<BR/>
<B>Versione Dynamo:</B> 2.12<BR/>
<B>Packages:</B> Camber, Civil3D Toolkit<BR/>
<B>Parametri:</B> Seleziona FeatureLine<BR/><BR/>
Lo script automatizza la denominazione e la valorizzazione di proprietà identificative all'interno delle diverse componenti di una PipeRun prelevando informazioni dalla FeatureLine selezionata. Sviluppato per una applicazione specifica è comunque possibile prevedere a richiesta implementazioni più generaliste per determinare una valorizzazione flessibile dei campo di destinazione.<BR/>

<H2>Pipes_Length</H2><BR/>
<B>Versione Civil3D:</B> 2022<BR/>
<B>Versione Dynamo:</B> 2.12<BR/>
<B>Packages:</B> Camber, Civil3D Toolkit<BR/>
<B>Parametri:</B> -<BR/><BR/>
Lo script automatizza la compilazione del paramentro NR_LUNGHEZZA del PSET Fisico_Geometrico prelevando la misura dai Pressure Pipes. Sviluppato per una applicazione specifica è comunque possibile prevedere a richiesta implementazioni più generaliste per determinare una denominazione variabile del campo di destinazione.<BR/>

<H2>Polyline_to_Elevated_FeatureLine</H2><BR/>
<B>Versione Civil3D:</B> 2022<BR/>
<B>Versione Dynamo:</B> 2.12<BR/>
<B>Packages:</B> Clockwork, Civil3D Toolkit<BR/>
<B>Parametri:</B> Select Polyline, Select Sections, Select Excel, Define Sheetname, Define Column<BR/><BR/>
Lo script consente di automatizzare la costruzione di una FeatureLine spaziale generata attraverso il tracciato di una polilinea che interseca una serie di sezioni note. Dynamo aggiungerà Elevation Points in corrispondenza delle diverse sezioni selezionate a cui aggiungerà le coordinate Z prelevate da un foglio Excel esterno. Lo script è disponibile anche in due versioni parziali, la prima delle quali lavorerà sulla sola costruzione piana della FL, la seconda eleverà i punti sulla FL selezionata.<BR/>

<H2>Polyline_to_Surface_FeatureLine</H2><BR/>
<B>Versione Civil3D:</B> 2022<BR/>
<B>Versione Dynamo:</B> 2.12<BR/>
<B>Packages:</B> Camber, Civil3D Toolkit<BR/>
<B>Parametri:</B> Select Polylines, Select Surface, Set Layer, Set Name<BR/><BR/>
Lo script automatizza la creazione di una o più FeatureLine da gruppo di polilinee applicandole in elevazione su una Superficie terreno. E' possibile determinare il Layer di destinazione ed il nome degli elementi generati.<BR/>

<H2>Text_to_Excel</H2><BR/>
<B>Versione Civil3D:</B> 2022<BR/>
<B>Versione Dynamo:</B> 2.12<BR/>
<B>Packages:</B> Camber, Civil3D Toolkit<BR/>
<B>Parametri:</B> Select TextBlocks, Filename, Sheetname<BR/><BR/>
Lo script consente di automatizzare la costruzione di un file Excel esterno compilando le celle con il valori dei blocchi di testo indipendenti selezionati sul DWG sorgente. Dynamo riconoscerà gli allineamenti orizzontali dei testi generando una sequenza di righe e posizionando le colonne in progressione corretta attraverso la coordinata X dei singoli blocchi di testo.<BR/>

<H2>Text_to_Property</H2><BR/>
<B>Versione Civil3D:</B> 2022<BR/>
<B>Versione Dynamo:</B> 2.12<BR/>
<B>Packages:</B> Civil3D Toolkit<BR/>
<B>Parametri:</B> Seleziona Testo, Seleziona NR Inizio e Fine Tratta, Seleziona FeatureLine, Seleziona WBS<BR/><BR/>
Lo script consente di automatizzare la compilazione di Property Sets specifici su una FeatureLine selezionata prelevando le informazioni da una serie di blocchi di testo sorgente indipendenti. Sviluppato per una applicazione specifica è comunque possibile prevedere a richiesta implementazioni più generaliste per determinare una valorizzazione flessibile dei campo di destinazione.<BR/>
