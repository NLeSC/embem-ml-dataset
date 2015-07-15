# Embodied Emotions Multi-Label Dataset

This repository contains the Embodied Emotions Multi-Label Dataset. Experimental results are reported in
 
> J.M. van der Zwaan, I. Leemans, E. Kuijpers, and I. Maks.
> HEEM, a Complex Model for Mining Emotions in Historical Text.
> _11th IEEE International Conference on eScience_, 2015

The dataset consists of 29 Dutch theatre texts that were manually annotated with labels from HEEM (Historic Embodied Emotion Model). More details about HEEM can be found in the paper. The data was annotated for the project ["From Sentiment Mining to Mining Embodied Emotions, Emotional styles on the Dutch stage between 1600-1800"](https://www.esciencecenter.nl/project/from-sentiment-mining-to-mining-embodied-emotions) by VU University, the Meertens Institute, and the Netherlands eScience Center. 

All texts come from [DBNL](http://dbnl.nl/). Complete texts and additional metadata can be found online, by appending the text id (file name without extension) to the URL `http://dbnl.nl/titels/titel.php?id=`, for example [http://dbnl.nl/titels/titel.php?id=alew001besl01](http://dbnl.nl/titels/titel.php?id=alew001besl01).

## Format

The data can be found in the directory `txt`. The lines in each file conatin the sentence id, sentence, and labels separated by tabs. The words (and punctuation marks) in the sentences are separated by spaces and the labels are concatenated using underscores. For example:

    alew001besl01_01.TEI.2.text.body.div.div.sp.stage.764.s.1   Carel spreekt zoetjes teegens Crelis en Fobert .	Emotion_Benevolence

Sentences without labels are followed by `None`: 

    alew001besl01_01.TEI.2.text.body.div.div.sp.293.s.3	Maer , daerom 's ' er recht in 't Land ; Neen , Crelis , 't zel ' er niet by blyven .	None

Spelling normalized data can be found in the directory `txt-spelling-normalized`. The procedure for spelling normalization is described in more detail in the paper.

## Citing

If you use this dataset in your work, please cite the following paper:

> To be added.