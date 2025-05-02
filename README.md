# Summary

A Universal Dependencies corpus for Bokota, a member of the Chibchan language family. The language is spoken by about 500 speakers in Panama. The variant of the Bokota treebank is spoken in the Comarca Ngobe-Bugle, at the border of the Veraguas Province, along the Caribbean coast. The other known variant of the language is called Buglere, and is spoken in the province of Chiriqui, in Panama.

# Introduction

The treebank is an automatic conversion of the SUD_Bokota-ChibErgIS, which is an automatic conversion of the [mSUD_Bokota-ChibErgIS](https://github.com/surfacesyntacticud/mSUD_Bokota-ChibErgIS) which was extracted from Marie Benzerrak interlinearized corpus in Flex format, itself an extension of an oral corpus documented by Marie Benzerrak (https://doi.org/10.5281/zenodo.13829160).

# Acknowledgments

Sentences are annotated with the following metadata:
 - `sent_timecode` (which will enable playback of the sentence)
 - `morphemic_text`: (original segmentation of the text into morphemes)
 - `text`: (lexical tokenization)
 - `text_en`: (English interpretation)
 - `text_phrase-gls-sab`: (original id)

## Structure
This version of the treebank is a dependency parsing of some files from the original corpus.

The original data are spoken data, which were originally segmented in words with concatenated clitics, then interlinearized and glossed in Flex with clitics as separate tokens. Tokens comprize words and affixes (preceded by a "-" sign). 

The **UD_Bokota-ChibErgIS** counts NUMBER tokens for NUMBER sentences.

## References

- Benzerrak, Marie. Chamoreau, C., Skopeteas, S., & Verhoeven, E. 2024. Bokota Spoken Corpus. Controlled Narrative Subcollection (1.0). Zenodo. https://doi.org/10.5281/zenodo.13829160

## Acknowledgments

This treebank was produced as part of the ChibErgIS project. Natalia Caceres is a main contributor in the annotation process, in association with Jana Bajorat who is at the same time annotating the Ika corpus. With special thanks to Bruno Guillaume for the conversion from SUD to UD.

# Changelog

* 2025-05-15 v2.16
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.16
License: CC BY-SA 4.0
Includes text: yes
Genre: spoken
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Benzerrak, Marie; Cáceres Arandia, Natalia
Contributing: here
Contact: marie.benzerrak@laposte.net
===============================================================================
</pre>