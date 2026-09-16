# GAPS — staða heimilda um Íslensku vefverðlaunin

Sjálfvirkt búið til út frá `data/awards.json` (`generated: 2026-09-16`). Allar tölur hér eru **taldar úr þeirri skrá**, ekki skrifaðar í höndunum.

> **Lestu fyrst:** þessi umferð notaði **tvær** heimildir — Markdown-skjölin í `vefverdlaun/` og gamla vefinn svef.is.
> Geymslan inniheldur **þriðju heimildina sem var ekki lesin**: 141 fréttaskjal í `frettir/`, þar á meðal
> topp-fimm-lista í hverjum flokki fyrir árin 2007–2016. Þegar sagt er hér að gögn vanti þýðir það
> **„fannst ekki í þeim tveimur heimildum sem voru notaðar“** — ekki „er ekki til í Skjalasafninu“. Sjá kafla 4.

## 1. Þekjutafla 2000–2025

| Ár | Heimildir | Sigurvegarar | Viðurkenningar | Tilnefningar | Framleiðendur | Dómnefnd | Dagsetning | Staður |
|---|---|---|---|---|---|---|---|---|
| 2000 | skjalasafn + svef.is | 8 | ✗ | 28 | ✗ | 7 | 2000-10-26 | ✗ |
| 2001 | **engin** | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ |
| 2002 | skjalasafn + svef.is | 5 | ✗ | 20 | ✗ | 5 | 2002-10-23 | Súlnasalur, Hótel Saga |
| 2003 | skjalasafn + svef.is | 5 | ✗ | 20 | ✗ | 6 | 2003-10-29 | ✗ |
| 2004 | skjalasafn + svef.is | 5 | ✗ | 20 | ✗ | 5 | 2004-10-29 | Sólon |
| 2005 | skjalasafn + svef.is | 5 | ✗ | 20 | ✗ | 7 | 2005-11-29 | IÐNÓ |
| 2006 | skjalasafn + svef.is | 6 | ✗ | 20 | ✗ | 7 | ✗ | Iðnó |
| 2007 | skjalasafn + svef.is | 8 | ✗ | 20 | ✗ | ✗ | ✗ | Hótel Saga |
| 2008 | skjalasafn + svef.is | 8 | ✗ | ✗ | ✗ | ✗ | ✗ | Listasafn Reykjavíkur |
| 2009 | skjalasafn + svef.is | 10 | ✗ | ✗ | ✗ | ✗ | ✗ | Hugmyndahús háskólanna |
| 2010 | skjalasafn + svef.is | 11 | ✗ | ✗ | ✗ | 7 | ✗ | Tjarnarbíó |
| 2011 | skjalasafn + svef.is | 11 | ✗ | ✗ | ✗ | 11 | ✗ | Tjarnarbíó |
| 2012 | skjalasafn + svef.is | 12 | ✗ | ✗ | ✗ | ✗ | 2013-02-08 | Harpa, Eldborg |
| 2013 | skjalasafn + svef.is | 14 | ✗ | ✗ | ✗ | 7 | ✗ | Gamla Bíó |
| 2014 | skjalasafn + svef.is | 15 | ✗ | ✗ | ✗ | ✗ | ✗ | Gamla Bíó |
| 2015 | skjalasafn + svef.is | 15 | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ |
| 2016 | skjalasafn + svef.is | 14 | 10 | ✗ | ✗ | ✗ | 2017-01-27 | Harpa, Silfurberg |
| 2017 | svef.is | 14 | 4 | ✗ | ✗ | ✗ | ✗ | ✗ |
| 2018 | svef.is | 13 | ✗ | 45 | 44 | ✗ | ✗ | ✗ |
| 2019 | svef.is | 14 | 3 | 47 | 47 | ✗ | ✗ | ✗ |
| 2020 | svef.is | 15 | 1 | 52 | 52 | ✗ | ✗ | ✗ |
| 2021 | svef.is | ✗ | ✗ | 64 | ✗ | ✗ | ✗ | ✗ |
| 2022 | svef.is | 15 | 1 | 65 | ✗ | ✗ | 2023-03-31 | Gamla bíó |
| 2023 | svef.is | 13 | 1 | 40 | 40 | ✗ | ✗ | Listasafn Reykjavíkur, Hafnarhúsið |
| 2024 | svef.is | ✗ | ✗ | 71 | 71 | ✗ | 2025-03-21 | Gróska |
| 2025 | svef.is | 18 | 1 | 16 | 34 | ✗ | 2026-03-26 | Harpa, Silfurberg |

**Samtals:** 823 færslur — 254 sigurvegarafærslur · 548 tilnefningar · 21 viðurkenningar. Framleiðendur skráðir fyrir 288 færslur. Dómnefnd þekkt fyrir 9 af 26 árum.

Hver færsla hefur fast auðkenni í reitnum `id` (`<ár>-<flokkur>-<heiti>`, umritað í ASCII) og hvert ár hefur `id` á forminu `islensku-vefverdlaunin-<ár>`; auðkennin eru þau sömu í hvert sinn sem skráin er endurgerð. Nákvæm lýsing á reglunni er í `sourceNotes` í `data/awards.json`.

## 2. Sjálfsprófun á fjölda flokka

Sumar heimildarsíður segja sjálfar hversu margir flokkarnir voru („Verðlaunin verða veitt í 15 flokkum“). Þáttunin les þá tölu og ber saman við fjölda flokka sem hún nær að lesa af sömu síðu. Ósamræmi þýðir að flokkur hafi tapast (t.d. af því að fyrirsögn hans er merkt upp sem stílaður `<span>` en ekki `<h3>`).

| Ár | Heimild | Segir í heimild | Þáttað | Stemmir |
|---|---|---|---|---|
| 2018 | `svef.is:/verdlaun/tilnefningar-og-verdlaunahafar-2018/` | — (engin tala í texta) | 15 | — |
| 2019 | `svef.is:/verdlaun/tilnefningar-2019/` | — (engin tala í texta) | 17 | — |
| 2020 | `svef.is:/verdlaun/tilnefningar-2020/` | — (engin tala í texta) | 16 | — |
| 2021 | `svef.is:/winners/tilnefningar-2021/` | — (engin tala í texta) | 13 | — |
| 2022 | `svef.is:/winners/tilnefningar-2022/` | 13 | 13 | ✓ |
| 2023 | `svef.is:/verdlaun/tilnefningar-og-verdlaunahafar2023/` | — (engin tala í texta) | 14 | — |
| 2024 | `svef.is:/winners/tilnefningar-2024/` | 15 | 15 | ✓ |
| 2025 | `svef.is:/verdlaun/verdlaunahafar-2025/` | — (engin tala í texta) | 19 | — |

Ósamræmi sem stendur eftir: **engin**.

## 3. Athugasemdir eftir árum

- **2000** — Dagsetning úr skjalasafni: "afhent í fyrsta skipti þann 26. október árið 2000". Staður ekki tilgreindur.
- **2001** — Engin heimild fannst í þeim tveimur heimildum sem þessi umferð notaði — hvorki skjal í vefverdlaun/ né síða á svef.is. README Skjalasafns spyr sjálft: "Hver er sagan á bakvið árið 2001?"
- **2003** — Staður ekki tilgreindur í heimild.
- **2006** — Heimild segir "18. janúar næstkomandi kl. 17:00" án ártals; athöfnin var því líklega í janúar 2007 en ártalið er ekki staðfest í heimild.
- **2007** — Heimild segir "Verðlaunaathöfnin fór fram 1. febrúar ... kl. 17" án ártals. Dómnefnd 2007 er ekki skráð og verður líklega aldrei: fréttin frettir/2008-01-17_domnefnd-islensku-vefverdlaunanna-2007.md segir berum orðum að nöfnum dómnefndarmanna hafi vísvitandi verið haldið leyndum ("Nöfnum dómnefndarmanna verður haldið leyndu fram yfir keppnina svo að þeir geti starfað í næði"). Þetta gat er því raunverulegt en ekki afleiðing af ónýttum heimildum.
- **2008** — Dagsetning ekki tilgreind ("Fyrr í kvöld"). Skjalasafnsskjalið inniheldur umsagnir dómnefndar fyrir flesta flokka en snið þess er of ósamræmt til að þátta sjálfvirkt; þær umsagnir vantar því í "blurb" hér og bíða handvirkrar yfirferðar.
- **2009** — Dagsetning ekki tilgreind. Skjalasafnsskjalið inniheldur umsagnir dómnefndar fyrir flesta flokka en snið þess er of ósamræmt til að þátta sjálfvirkt; þær umsagnir vantar því í "blurb" hér og bíða handvirkrar yfirferðar.
- **2010** — Dagsetning ekki tilgreind ("í gær"). Skjalasafnsskjalið inniheldur umsagnir dómnefndar fyrir flesta flokka en snið þess er of ósamræmt til að þátta sjálfvirkt; þær umsagnir vantar því í "blurb" hér og bíða handvirkrar yfirferðar.
- **2011** — Dagsetning ekki tilgreind ("í kvöld"). Skjalasafnsskjalið inniheldur umsagnir dómnefndar fyrir flesta flokka en snið þess er of ósamræmt til að þátta sjálfvirkt; þær umsagnir vantar því í "blurb" hér og bíða handvirkrar yfirferðar.
- **2012** — Skjalið er tilkynning fyrir hátíðina ("verða afhend ... 8. febrúar 2013"), ekki frásögn eftir á. Skjalasafnsskjalið fyrir 2012 er aðeins tilkynning fyrir hátíðina og inniheldur engin úrslit (sbr. Todo í README). Sigurvegarar koma eingöngu frá svef.is.
- **2013** — Dagsetning ekki tilgreind ("í kvöld"). Skjalasafnsskjalið inniheldur umsagnir dómnefndar fyrir flesta flokka en snið þess er of ósamræmt til að þátta sjálfvirkt; þær umsagnir vantar því í "blurb" hér og bíða handvirkrar yfirferðar.
- **2014** — Dagsetning ekki tilgreind ("fyrr í dag"). Skjalasafnsskjalið inniheldur umsagnir dómnefndar fyrir flesta flokka en snið þess er of ósamræmt til að þátta sjálfvirkt; þær umsagnir vantar því í "blurb" hér og bíða handvirkrar yfirferðar.
- **2015** — Hvorki dagsetning né staður tilgreind ("afhent í gær"). Skjalasafnsskjalið inniheldur ósamræmdan kafla "Tilnefningar og sigurvegarar 2015" með tilnefningum og framleiðendum í lausu máli. Hann var ekki þáttaður sjálfvirkt og tilnefningar 2015 eru því skráðar sem óþekktar. ACF-reiturinn winner_url er "#" (staðgengilsgildi) fyrir VÍS og Tix.is; það er staðlað í null hér, sbr. sourceNotes.
- **2016** — Viðurkenningarnar tíu koma eingöngu úr Skjalasafnsskjalinu og flokkaheiti þeirra eru staðlaðar merkingar sem þessi þáttun bjó til úr lausu máli — orðrétt orðalag heimildarinnar er í reitnum "categoryVerbatim" og þessar færslur eru confidence: medium. Slóðin fyrir "Sinfoníuhljómsveit Íslands" er "sinfonia.is" án samskiptamáta; hún er orðrétt úr biluðum markdown-hlekk í heimildinni og er eina afstæða slóðin í skránni — hana þarf að staðla (https://sinfonia.is/) áður en hún er notuð með new URL().
- **2017** — Tilnefningalisti fannst ekki; aðeins sigurvegarar og viðurkenningar (tvær aðskildar færslur á svef.is).
- **2019** — Heimildin tekur fram að vefur sem tilnefndur var í flokknum "Fyrirtækjavefur ársins (stór fyrirtæki)" hafi síðar verið fjarlægður: "Vefur sem tilnefndur var í þessum flokki var síðar fjarlægður eftir að í ljós kom að hann uppfyllti ekki skilyrði um fjölda starfsmanna." Sá vefur er ekki nefndur á nafn og er því ekki í skránni. Heimildin segir einnig: "Vegna dræmrar þátttöku voru ekki veitt verðlaun fyrir efnis- og fréttaveitu ársins."
- **2021** — Tilnefningasíðan segir að sigurvegarar verði tilkynntir "11. mars kl. 1930 í beinni útsendingu á Vísi" án ártals og án staðar. Aðeins tilnefningalisti fannst á svef.is; engin síða með sigurvegurum ársins 2021 er til í valmynd eða sitemap. Sigurvegarar vantar alveg.
- **2022** — Tilnefningar af /winners/tilnefningar-2022/, sigurvegarar af /winners/verdlaunavefir-2022/. Sjálfsprófun: síðan segir "Verðlaunin verða veitt í 13 flokkum" og þáttunin skilar 13 flokkum.
- **2023** — svef.is ACF-reiturinn "winning_year" fyrir verðlaunavefi 2023 segir "31 des 2024" en færslan heitir "Verðlaunavefir 2023"; árið er tekið af titli/slóð. Þarf staðfestingu. Heimild segir "15. mars" án ártals.
- **2024** — Aðeins tilnefningalisti fannst á svef.is; engin síða með sigurvegurum ársins 2024 fannst. Sigurvegarar vantar alveg. Sjálfsprófun: síðan segir "Verðlaunin verða veitt í 15 flokkum" og þáttunin skilar nú 15 flokkum — flokkurinn "Stafræn lausn ársins" er merktur upp sem stílaður <span> en ekki <h3> í heimildinni og féll því áður saman við "Innri vefur ársins". Textinn segir "Sjötíu vefir eða stafrænar lausnir eru tilnefnd" en taldir liðir eru 71; liðirnir 71 eru allir ólíkir og ekkert bendir til tvítalningar, svo ósamræmið milli inngangstextans og listans er óútskýrt og bíður staðfestingar frá SVEF.
- **2025** — Síðan listar aðeins "Sigurvegara" og "Upphlaupara" í hverjum flokki, ekki allar tilnefningar. Upphlauparar eru skráðir sem nominee. Færslur unnar með þáttun á HTML og þarfnast yfirlesturs. Slóðin fyrir "HMS Byggingarleyfi á Íslandi" (byggingarleyfi-stg.hms.is) er prófunarumhverfisslóð (staging) og er orðrétt úr heimildinni — hana á ekki að birta óbreytta. "Nova appið" hefur bæði iOS- og Android-slóð í heimildinni; fyrri slóðin (iOS) er geymd í "url" og hin er ekki geymd, sbr. sourceNotes.

## 4. `frettir/` — þriðja heimildin, ólesin

Geymslan inniheldur **141 fréttaskjal** í `frettir/` sem **voru ekki notuð** í þessari umferð. Þau eru ekki tóm: 17 þeirra eru listar yfir vefi í úrslitum eða „topp fimm“ í hverjum flokki, einmitt fyrir þau ár sem tafla 1 sýnir án tilnefninga:

- `frettir/2008-01-26_vefir-i-urslitum-vefverdlaunanna-2007.md`
- `frettir/2008-02-01_islensku-vefverdlaunin-2007-urslit.md`
- `frettir/2009-01-26_vefir-i-urslitum-vefverdlaunanna-2008.md`
- `frettir/2009-01-30_islensku-vefverdlaunin-2008-urslit.md`
- `frettir/2010-02-05_vefir-i-urslitum-til-islensku-vefverdlaunanna-2009.md`
- `frettir/2011-01-30_vefir-i-urslitum-til-islensku-vefverdlaunanna-2010.md`
- `frettir/2011-02-05_urslit-i-islensku-vefverdlaununum.md`
- `frettir/2012-01-30_vefir-i-urslitum-til-islensku-vefverdlaunanna-2011.md`
- `frettir/2012-02-03_urslit-islensku-vefverdlaunanna-2011.md`
- `frettir/2013-02-04_vefir-i-urslitum-til-islensku-vefverdlaunanna-2012.md`
- `frettir/2014-01-21_islensku-vefverdlaunin-2013-verkefni-i-urslitum.md`
- `frettir/2015-01-14_topp-fimm-vefir-tilkynntir.md`
- `frettir/2015-01-21_vefir-i-urslitum-vefverdlaunanna.md`
- `frettir/2015-01-30_bestu-vefir-landsins-urslit-vefverdlaunanna-2014.md`
- `frettir/2016-01-21_buid-er-ad-birta-urslit-topp-fimm-i-hverjum-flokki-til-islensku-vefverdlaunanna.md`
- `frettir/2017-01-20_topp-fimm-i-hverjum-flokki-til-islensku-vefverdlaunanna-2016.md`
- `frettir/2017-01-28_urslit-islensku-vefverdlaunanna.md`

Dæmi: `frettir/2009-01-26_vefir-i-urslitum-vefverdlaunanna-2008.md` er fullur topp-fimm-listi í hverjum flokki fyrir árið 2008, með lénum. Sama gildir um 2007, 2009, 2010, 2011, 2012, 2013, 2014, 2015 og 2016.

**Þess vegna á ekki að lesa „vantar“ í þessari skrá sem „er ekki til“.** Þar sem tafla 1 og kafli 5 segja að tilnefningar vanti fyrir 2008–2016 þýðir það að þær fundust hvorki í `vefverdlaun/`-skjölunum né á svef.is; `frettir/` er þekkt, ónýtt heimild sem mjög líklega inniheldur þær. Að vinna úr `frettir/` er sérstakt verkefni og bíður eftirfylgnimáls; það var vísvitandi ekki gert hér svo þessi skrá héldist bundin við þær tvær heimildir sem `sourceNotes` lýsir.

**Undantekning — raunverulegt gat, ekki ónýtt heimild:** dómnefnd ársins 2007. `frettir/2008-01-17_domnefnd-islensku-vefverdlaunanna-2007.md` segir berum orðum að nöfnunum hafi verið haldið leyndum („Nöfnum dómnefndarmanna verður haldið leyndu fram yfir keppnina svo að þeir geti starfað í næði“). Þar dugar engin frekari vinnsla á `frettir/`; upplýsingarnar voru aldrei birtar þar.

## 5. Forgangsgöt

### 5.1 Ár án nokkurra gagna (1)

2001

### 5.2 Ár án sigurvegara (3)

2001, 2021, 2024

### 5.3 Ár án tilnefninga í þeim tveimur heimildum sem voru notaðar (11)

2001, 2008, 2009, 2010, 2011, 2012, 2013, 2014, 2015, 2016, 2017

Fyrir 2007–2016 eru líklegustu gögnin í `frettir/`, sbr. kafla 4.

### 5.4 Ár án dómnefndar í þeim tveimur heimildum sem voru notaðar (17)

2001, 2007, 2008, 2009, 2012, 2014, 2015, 2016, 2017, 2018, 2019, 2020, 2021, 2022, 2023, 2024, 2025

### 5.5 Hátíðin sjálf

- Dagsetning vantar (16 ár): 2001, 2006, 2007, 2008, 2009, 2010, 2011, 2013, 2014, 2015, 2017, 2018, 2019, 2020, 2021, 2023
- Staður vantar (9 ár): 2000, 2001, 2003, 2015, 2017, 2018, 2019, 2020, 2021

### 5.6 Framleiðendur

Reiturinn `producers` (og orðrétti strengurinn `producersRaw`) er fylltur þar sem heimildin nefnir framleiðanda. Ár þar sem engin færsla hefur framleiðanda (19): 2000, 2002, 2003, 2004, 2005, 2006, 2007, 2008, 2009, 2010, 2011, 2012, 2013, 2014, 2015, 2016, 2017, 2021, 2022.

Heimildirnar fyrir 2018 nefna almennt enga framleiðendur, og tilnefningasíðurnar 2021–2022 telja aðeins nöfn verkefna. Þetta er gat í heimildunum sjálfum, ekki í þáttuninni.

### 5.7 Það sem README Skjalasafns merkti sjálft sem ólokið

README-skráin í rót geymslunnar telur þetta upp undir „Todo“. Staðan hér miðað við `data/awards.json`:

| README-atriði | Ár | Staða núna |
|---|---|---|
| Upplýsingar um verðlaun | 2007 | leyst af svef.is (8 sigurvegarar skráðir) |
| Upplýsingar um verðlaun | 2012 | leyst af svef.is (12 sigurvegarar skráðir) |
| Dómnefndir | 2007 | **ólokið — og líklega óleysanlegt**: heimildin segir að nöfnunum hafi verið haldið leyndum (sjá kafla 4) |
| Dómnefndir | 2008 | **ólokið — fannst ekki í þeim tveimur heimildum sem voru notaðar; `frettir/` ólesið** |
| Dómnefndir | 2009 | **ólokið — fannst ekki í þeim tveimur heimildum sem voru notaðar; `frettir/` ólesið** |
| Dómnefndir | 2012 | **ólokið — fannst ekki í þeim tveimur heimildum sem voru notaðar; `frettir/` ólesið** |
| Dómnefndir | 2014 | **ólokið — fannst ekki í þeim tveimur heimildum sem voru notaðar; `frettir/` ólesið** |
| Dómnefndir | 2016 | **ólokið — fannst ekki í þeim tveimur heimildum sem voru notaðar; `frettir/` ólesið** |
| Listi af tilnefndum vefjum + wayback-linkar | 2008 | **ólokið — fannst ekki í þeim tveimur heimildum sem voru notaðar; topp-fimm-listi fyrir þetta ár er til í `frettir/` (sjá kafla 4)** |
| Listi af tilnefndum vefjum + wayback-linkar | 2009 | **ólokið — fannst ekki í þeim tveimur heimildum sem voru notaðar; topp-fimm-listi fyrir þetta ár er til í `frettir/` (sjá kafla 4)** |
| Listi af tilnefndum vefjum + wayback-linkar | 2010 | **ólokið — fannst ekki í þeim tveimur heimildum sem voru notaðar; topp-fimm-listi fyrir þetta ár er til í `frettir/` (sjá kafla 4)** |
| Listi af tilnefndum vefjum + wayback-linkar | 2011 | **ólokið — fannst ekki í þeim tveimur heimildum sem voru notaðar; topp-fimm-listi fyrir þetta ár er til í `frettir/` (sjá kafla 4)** |
| Listi af tilnefndum vefjum + wayback-linkar | 2013 | **ólokið — fannst ekki í þeim tveimur heimildum sem voru notaðar; topp-fimm-listi fyrir þetta ár er til í `frettir/` (sjá kafla 4)** |
| Listi af tilnefndum vefjum + wayback-linkar | 2014 | **ólokið — fannst ekki í þeim tveimur heimildum sem voru notaðar; topp-fimm-listi fyrir þetta ár er til í `frettir/` (sjá kafla 4)** |
| Listi af tilnefndum vefjum + wayback-linkar | 2015 | **ólokið — fannst ekki í þeim tveimur heimildum sem voru notaðar; topp-fimm-listi fyrir þetta ár er til í `frettir/` (sjá kafla 4)** |
| Listi af tilnefndum vefjum + wayback-linkar | 2016 | **ólokið — fannst ekki í þeim tveimur heimildum sem voru notaðar; topp-fimm-listi fyrir þetta ár er til í `frettir/` (sjá kafla 4)** |
| Hver er sagan á bakvið árið 2001? | 2001 | **ólokið — engin heimild um 2001 í þeim tveimur heimildum sem voru notaðar** |

## 6. Aðferð og takmarkanir

Þessi skrá er **skrásetning þess sem er til**, ekki tilraun til að endurgera söguna. Tvær heimildir voru notaðar: Markdown-skjölin í `vefverdlaun/` í þessari geymslu (til fyrir 2000 og 2002–2016) og gamli WordPress-vefurinn svef.is (winners-færslur sóttar um `admin-ajax` ACF-reiti, tilnefninga- og verðlaunasíður um WP REST API). **Þriðja heimildin, `frettir/`, var ekki lesin** (kafli 4) — það er val, ekki fullyrðing um að hún sé tóm. Ekkert var ályktað eða giskað á: ef heimild nefnir ekki ártal hátíðar, dómnefndarmann eða tilnefningu er reiturinn `null` eða `known: false`, jafnvel þegar „augljóst“ svar virðist blasa við. Tölurnar segja því aðeins hversu margar **færslur tókst að lesa úr þessum tveimur heimildum** — þær segja hvorki að flokkar hafi verið svona margir það árið né að vefur sem vantar hafi ekki unnið.

Sigurvegarar 2000–2020, 2022 og 2023 eru teknir úr skipulögðum ACF-reitum og eru `confidence: high`; tilnefningar 2000 og 2002–2007 eru lesnar úr punktalistum í Skjalasafninu (feitletraður liður = sigurvegari) og eru einnig `high`. Allt sem var þáttað úr frjálsu HTML á svef.is (tilnefningar 2018–2025 og öll gögn 2025) er `confidence: medium` og þarf mannlegan yfirlestur. Viðurkenningarnar 2016 eru líka `medium`: flokkaheiti þeirra eru staðlaðar merkingar búnar til úr lausu máli og orðrétt orðalag heimildarinnar er í `categoryVerbatim`.

Flokkaheiti eru geymd orðrétt og eru því ósamræmd milli ára — og stundum **innan** sama árs, því sigurvegarar koma úr ACF en tilnefningar úr lausu máli. Þau er ekki hægt að tengja saman án samsvörunartöflu; sama á við um `siteName`. Sami vefur getur birst oftar en einu sinni á ári þegar hann vann í fleiri en einum flokki; færslufjöldi er því ekki fjöldi ólíkra verkefna.
