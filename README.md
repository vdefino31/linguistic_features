Prediction of L2 speech proficiency based on multi-level linguistic features
==

This repository is part of an Interspeech paper (edition 2022) focusing on the prediction of speech proficiency of L2 learners.

 Corpora
 --
The data employed in this study are from the CLIJAF corpora [1], collected within the general methodological framework of the IPFC project [2, 3]. A subset of CLIJAF is analysed, corresponding to a semi-spontaneous oral production task of Japanese students learning French at university in Japan. This task consists of an individual semi-directive interview in French, conducted by a native speaker (teacher of doctoral student).

Four specific questions were asked to the students : 
1. _How old are you and what is your nationality?_
2. _Which languages do you speak?_
3. _What are your biggest difficulties when learning French?_
4. _What are the main cultural or social differences between France and Japan?_

The data were recorded at the students' respective universities, segmented into speech turns (a speech turn being the first answer produced by the learner, in accordance with the question asked) and transcribed orthographically with text-to-sound alignement.

Phonetic-linguistic features
--
A set of 14 phonetic-linguistic features were semi-automatically assessed and extracted from the speech productions of Japanese learners of French. The features are: 
* based on the acoustic signal:
    * a confidence index (CI) associated to a phoneme recognition performed on the acoustic signal,
    * the speech rate (SR),
    * the percentage of speech (PS),
    * the standard deviation of the duration of pseudo-syllables (SD),
    * the normalized number of silent pauses (NSP),
* based on the transcripts of the speech productions:
    * for lexical richness:
        * lexical diversity (using the Guiraud index) (GI),
        * lexical density (LD),
        * lexical sophistication (LS),
    * for the syntactic complexity:
        * the average length of speech turns (SL),
        * the average depth of syntactic trees (AD),
    * for the discourse cohesion:
        * the proportion of discourse connectors (DC),
        * diversity of discourse connectors (DivC),
    * for disfluencies:
        * the proportion of hesitation words (HW),
        * the proportion of unfinished words (UW).


Assessing speech proficiency
--
Three FFL (_French as a Foreign Language_) teachers were asked to evaluate the students' speech proficiencies, using a scale from **A1** to **C2**, in accordance with the Common European Framework of Reference for Languages (_CEFR_).

Evolution of the phonetic-linguistic features according to the speech proficiency
--
The Figures presenting the evolution of the above-mentioned features according to the speech proficiency are placed in the dedicated folders.

References
--
[1] Detey, S. (Ed.) (2011-2019). A longitudinal interphonological corpus of Japanese learners of French. JSPS: Grant-in-Aid for Scientific Research (B) 23320121 & 15h03227

[2] S. Detey and Y. Kawaguchi, “Interphonologie du Français Contemporain (IPFC): récolte automatisée des données et apprenants japonais,” in Journées PFC: Phonologie du françis contemporain: variation, interfaces, cognition, Paris: MSH, Dec. 2008.

[3] I. Racine, F. Zay, S. Detey, and Y. Kawaguchi, “Des atouts d’un corpus multitâches pour l’étude de la phonologie en L2: l’exemple du projet “Interphonologie du français contemporain” (IPFC),” in Recherches récentes en FLE, A. Kamber and C. Skupien, Eds. Bern: Peter Lang, 2012, pp. 1–19.
