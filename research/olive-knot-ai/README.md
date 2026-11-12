<a href="media/exhibition-booth.jpg"><img src="media/exhibition-booth.jpg" alt="Eren Arıkan at the 2022 TÜBİTAK research exhibition, standing in front of his olive knot poster with olive specimens and a mobile prototype on the table" width="100%"></a>

<sub>At the 2022 TÜBİTAK exhibition with the research poster, olive specimens and working prototype. [View original photo](media/exhibition-booth.jpg).</sub>

# Olive Knot AI — computer vision and plant research

**National second place in Software, TÜBİTAK 2204-A (2022)** · Regional first place in Software

I built a research prototype to classify the visible stage of olive knot disease from plant images, put the classifier into a mobile app, and studied disease progression in olive saplings over four months. The public archive shows the work as it was presented: real photographs, prototype screens, the training chart, and a public edition of my original research poster.

**[View the public poster (PDF)](media/public-research-poster.pdf)** · [Public presentation (PDF)](media/public-presentation.pdf) · [PowerPoint](media/public-presentation.pptx) · [Award evidence](AWARDS_AND_SOURCES.md) · [Media and rights](MEDIA_CREDITS.md)

## The original poster, ready to explore

<a href="media/public-research-poster.pdf"><img src="media/public-research-poster.jpg" alt="Public edition of Eren Arıkan's 2022 olive knot research poster; title, research context, plant images, results and charts remain visible while source code and detailed methods are obscured" width="100%"></a>

<sub>[Open the readable PDF](media/public-research-poster.pdf). This is a public edition of the original 2022 poster. The central code screenshot, exact experimental doses and procedures, and model/data workflow were removed from the PDF itself. The original stays private.</sub>

## What I built and investigated

| Workstream | Public evidence | Outcome |
|---|---|---|
| Image classification | Four visible disease-stage classes; CNN developed with TensorFlow/Keras | The 2022 poster reports **88.33% classification accuracy**. This is a self-reported research result, not an independently validated field score. |
| Mobile prototype | Real stage-1 and stage-4 app screenshots below | A phone interface displayed ranked stage predictions and confidence for an image. |
| Plant study | Olive specimens, laboratory image, original poster's result plots | **12 olive saplings**, four comparison groups, approximately four months of observation. The reported plant findings are preliminary. |

The research question was whether a phone image could give a useful, fast indication of **visible disease stage**. I also examined how the disease progressed under comparison conditions involving *Bacillus subtilis*. The app was a research demonstration; it was not a certified diagnosis, field-validated product, or proven treatment.

## See the project at the exhibition

<table><tr><td width="55%"><a href="media/research-demonstration.jpg"><img src="media/research-demonstration.jpg" alt="Eren demonstrating the olive knot project in front of the original poster and an olive specimen" width="100%"></a><br><sub>Explaining the project with a specimen and the original poster. [Full image](media/research-demonstration.jpg)</sub></td><td width="45%"><a href="media/regional-first-place-graphic.jpg"><img src="media/regional-first-place-graphic.jpg" alt="2022 TÜBİTAK and İstanbul Technical University graphic naming Hüseyin Eren Arıkan first place in the regional Software category" width="100%"></a><br><sub>The supplied **regional first-place** announcement. The national second-place result is documented separately in the [official final list](AWARDS_AND_SOURCES.md). [Full image](media/regional-first-place-graphic.jpg)</sub></td></tr></table>

## Mobile prototype — real screens

<table><tr><td width="50%"><a href="media/mobile-stage-1.jpg"><img src="media/mobile-stage-1.jpg" alt="Original mobile prototype showing an olive branch image and a stage-1 prediction with 98.03 percent confidence" width="100%"></a><br><sub>Stage-1 example: **98.03% prediction confidence** for this image. [Full screen](media/mobile-stage-1.jpg)</sub></td><td width="50%"><a href="media/mobile-stage-4.jpg"><img src="media/mobile-stage-4.jpg" alt="Original mobile prototype showing an olive branch image and a stage-4 prediction with 93.27 percent confidence" width="100%"></a><br><sub>Stage-4 example: **93.27% prediction confidence** for this image. [Full screen](media/mobile-stage-4.jpg)</sub></td></tr></table>

These percentages are the prototype's **per-image predictions**, separate from the poster's reported overall accuracy. They should not be read as clinical or agricultural reliability estimates.

<a href="media/mobile-app-icon.png"><img src="media/mobile-app-icon.png" alt="Original phone home screen showing the Kanser Tespit mobile app icon" width="260"></a>

<sub>The original “Kanser Tespit” app icon on the phone home screen. [Full image](media/mobile-app-icon.png).</sub>

## Research images and training record

<table><tr><td width="50%"><a href="media/olive-branch-specimen.jpg"><img src="media/olive-branch-specimen.jpg" alt="Original photograph of an olive branch specimen used in the project presentation" width="100%"></a><br><sub>Olive branch specimen. [Full image](media/olive-branch-specimen.jpg)</sub></td><td width="50%"><a href="media/laboratory-sample.jpg"><img src="media/laboratory-sample.jpg" alt="Original photograph of a red laboratory sample plate from the plant research" width="100%"></a><br><sub>Laboratory sample from the plant study. [Full image](media/laboratory-sample.jpg)</sub></td></tr></table>

<a href="media/training-validation-chart.jpg"><img src="media/training-validation-chart.jpg" alt="Original notebook photograph showing noisy training and validation accuracy and loss curves over about 110 training epochs" width="100%"></a>

<sub>Original training and validation chart. The visible variation is part of the experiment record; it is not evidence of performance on an independent external dataset. [Full image](media/training-validation-chart.jpg).</sub>

## Recognition and context

TÜBİTAK's [archived official 2022 national-final list](https://web.archive.org/web/20240520125501id_/https://tubitak.gov.tr/sites/default/files/2750/final_sonuc_web_son.pdf) records **Hüseyin Eren Arıkan**, advisor **Volkan Gönen**, and this project as an **İkincilik Ödülü** (second-place award) in **Yazılım** (Software). The [2022 TÜBİTAK competition report](https://tubitak.gov.tr/tr/haber/53-lise-ogrencileri-arastirma-projeleri-yarismasinin-kazananlari-odullerini-cumhurbaskani-erdoganin-elinden-aldi) reports **25,095 project submissions**, **37,283 participating students** and **216 national-final projects** across all 12 fields. Those totals are competition-wide, not a Software-only ranking.

The 2022 national awards ceremony took place at the Presidential Complex with President Recep Tayyip Erdoğan present. TÜBİTAK says he presented first-place prizes; ministers and TÜBİTAK leadership presented second-place prizes. National award winners could be considered in a further **Regeneron ISEF** selection process; a national prize did not automatically mean ISEF participation. [Award details and source notes](AWARDS_AND_SOURCES.md).

## Public release and rights

The original source code, model weights, training images, detailed model architecture, laboratory procedures, and unredacted poster remain private. This archive documents the problem, prototype and reported results without releasing the implementation. The original photographs are preserved as supplied, apart from the separately prepared public poster edition.

**© 2026 Hüseyin Eren Arıkan. All rights reserved for original materials I own.** No open-source licence is granted. Institutional logos, official documents, graphics and photographs belonging to others remain with their respective rights holders. See [LICENSE.md](LICENSE.md) and [MEDIA_CREDITS.md](MEDIA_CREDITS.md).

[← Back to my GitHub profile](https://github.com/erudaperu)
