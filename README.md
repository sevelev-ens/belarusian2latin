# belarusian2latin

*Беларуская версія ніжэй* 

First, to our knowledge, Belarusian Cyrillic to Latin converter that
 - systematically cares to render Belarusian phonology correctly. It concerns, e.g.,
   - the regressive palatalization issue (i.e. /s<sup>j</sup>n<sup>j</sup>ɛɣ/ is rendered “śnieh“ and not “snieh”). Overpalatalized dentals constituting a characteristic feature of Belarusan (so-called “dziekańnie”, “ciekańnie”), it is primordial to render them correctly **systematically**; 
   - the laxist graphic convention of the official Cyrillic system as to the letter «г»: may denote /ɣ<sup>(j)</sup>/ or /g<sup>(j)</sup>/ with no evident pattern: “гісторыя”/“гузік”);
   - the laxist graphic convention of the official Cyrillic system as to the letter «і»: may denote /і/ or /jі/ with no evident pattern trigerring two different palatalization patterns: “ім”/“інтэгральны” → “з ім”/“з інтэгральнага” /і→ы/ /jі→<sup>(j)</sup>i/;
   - the laxist graphic convention of the official Cyrillic system as to the letter «e»: in borrowed words, it may confer or not palatalization to the previous consonant with no evident pattern: “веласіпед”/“Аве Марыя” /v/ and /v<sup>(j)</sup>/;
- complies with the official Belarus's [prescription](https://be.wikipedia.org/wiki/%D0%86%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%86%D1%8B%D1%8F_%D0%BF%D0%B0_%D1%82%D1%80%D0%B0%D0%BD%D1%81%D0%BB%D1%96%D1%82%D0%B0%D1%80%D0%B0%D1%86%D1%8B%D1%96) to use the alphabet «abcćčdefhijklĺmnńoprsśštuŭvyzžź» and the [UN standard](https://unstats.un.org/unsd/geoinfo/UNGEGN/docs/9th-uncsgn-docs/crp/9th_UNCSGN_e-conf-98-crp-21.pdf)  based thereupon;
 - complies with the [official Belarus's Orthographic rules](https://be.wikipedia.org/wiki/%D0%9F%D1%80%D0%B0%D0%B2%D1%96%D0%BB%D1%8B_%D0%B1%D0%B5%D0%BB%D0%B0%D1%80%D1%83%D1%81%D0%BA%D0%B0%D0%B9_%D0%B0%D1%80%D1%84%D0%B0%D0%B3%D1%80%D0%B0%D1%84%D1%96%D1%96_%D1%96_%D0%BF%D1%83%D0%BD%D0%BA%D1%82%D1%83%D0%B0%D1%86%D1%8B%D1%96_(2008)).

We thoroughly follow the Belarusian phonology description as given at:

> Фанетыка беларускай літатурнай мовы / І. Р. Бурлыка, Л. Ц. Выгонная, Г. В. Лосік, А. І. Падлужны; Рэд. А. І. Падлужны. — Мн.:Навука і тэхніка, 1989. — 335 с ISBN 5-343-00292-7

We are aware of the following toy converters: [Sloŭnik.org](http://slounik.org/lat), [Baltoslav](http://baltoslav.eu/lat/), [Draŭliany Zedlik](http://www.zedlik.com/pragramy/kir2lac-online/). As of Aug  02, 2019, all of them fail to render correctly the phonemes (try: “снег, здзяйсняецца” (not) to obtain “śnieh, ździajśniajecca”).

The transcription generator by the [Speech Analysis and Recognition Lab](https://www.corpus.by/TranscriptionGenerator/?lang=be) Belarusan Academy of Sciences only deals with tagged text and produces phonetic [···], not phonematic /···/ transcriptions.  The transcription generator [Philology.by](https://tools.philology.by/latbe) by [Alyaxey Yaskevich](https://yaskevich.com/) also pursues another objective.

