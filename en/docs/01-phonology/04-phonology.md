# Phonology

This file defines the phonemic inventory, stress system, phonotactics, and major morphophonological alternations of Arcadia.

## Phonemic Vowels

Arcadia has five vowel phonemes:

```ipa
/i e a o u/
```

| Height | Front | Central | Back |
| ------ | ----- | ------- | ---- |
| Close  | /i/   |         | /u/  |
| Mid    | /e/   |         | /o/  |
| Open   |       | /a/     |      |

Vowel quality is stable across stressed and unstressed syllables.

## Stress and Vowel Length

Stress is phonologically significant.

The stressed vowel is phonetically long:

```ipa
/V/ → [Vː] / stressed syllable
```

Unstressed vowels are phonetically short.

Vowel length is therefore predictable from stress and is not an independent phonemic contrast.

## Default Stress

Monosyllabic words are stressed on their only syllable.

In multisyllabic words, stress defaults to the penultimate syllable.

Non-penultimate stress is marked orthographically with an acute accent on the stressed vowel.

## Consonant Inventory

| Manner                 | Bilabial | Labiodental | Dental | Alveolar | Post-Alveolar | Palatal | Velar |
| ---------------------- | -------- | ----------- | ------ | -------- | ------------- | ------- | ----- |
| Nasal                  | /m/      |             |        | /n/      |               | /ɲ/     |       |
| Plosive                | /p b/    |             | /t d/  |          |               |         | /k g/ |
| Sibilant fricative     |          |             |        | /s z/    | /ʃ ʒ/         |         |       |
| Non-sibilant fricative |          | /f v/       | /θ ð/  |          |               |         | /x ɣ/ |
| Affricate              |          |             |        |          | /t͡ʃ d͡ʒ/       |         |       |
| Tap/flap               |          |             |        | /ɾ/      |               |         |       |
| Approximant            |          |             |        |          |               | /j/     |       |
| Lateral approximant    |          |             |        | /l/      |               | /ʎ/     |       |

## Obstruent Pairing

Most obstruents are organised into voicing pairs.

| Voiceless | Voiced |
| --------- | ------ |
| /p/       | /b/    |
| /t/       | /d/    |
| /k/       | /g/    |
| /f/       | /v/    |
| /θ/       | /ð/    |
| /s/       | /z/    |
| /ʃ/       | /ʒ/    |
| /x/       | /ɣ/    |
| /t͡ʃ/      | /d͡ʒ/   |

This pairing supports secondary devoicing and other regular morphophonological alternations.

## Sonorants

The sonorants are:

```ipa
/m n ɲ l ʎ ɾ j/
```

Sonorants do not undergo secondary devoicing.

## Marked Velar Fricatives

The velar fricatives /x/ and /ɣ/ are part of the phonemic inventory but should remain relatively marked in inherited vocabulary.

The voiced velar fricative /ɣ/ is preferred in sonorous environments, especially between vowels or near liquids.

The voiceless velar fricative /x/ is stronger and should be used more sparingly in high-register native roots.
It is also the regular secondary-devoiced counterpart of /ɣ/.

## Marked Affricates

The affricates /t͡ʃ/ and /d͡ʒ/ are highly restricted.

They do not occur freely in inherited lexical roots.

The voiced affricate /d͡ʒ/ marks the dubitative mood.
The voiceless affricate /t͡ʃ/ is its secondary-clause devoiced counterpart.

Outside dubitative morphology, these affricates are permitted primarily in loanwords, names, and explicit transcription.

## Basic Syllable Structure

The basic syllable template is:

```text
(C)(R/J)V(C)(C)
```

Where:

- `C` is a consonant;
- `R` is a liquid, /l/, /ʎ/ or /ɾ/;
- `J` is /j/;
- `V` is a vowel.

The preferred syllable shapes are:

```text
CV
CVC
CCV
CCVC
```

The following shapes are permitted but less central:

```text
V
VC
CVCC
```

No native syllable has more than two consonants in the onset or coda.

## Onsets

Single-consonant onsets are broadly permitted.

The affricates /t͡ʃ/ and /d͡ʒ/ are restricted by morphology and loanword status rather than by ordinary onset phonotactics.

The phoneme /ɣ/ is permitted as an onset but is preferred medially or in sonorous environments.

## Onset Clusters

Native onset clusters are limited.

Preferred onset clusters consist of an obstruent followed by a liquid:

```text
OR
```

A more restricted set of obstruent + /j/ clusters is also permitted:

```text
Oj
```

Onset clusters involving /x/, /ɣ/, /t͡ʃ/, or /d͡ʒ/ are disfavored in inherited vocabulary.

Three-consonant onsets are not permitted in native words.

## Codas

Codas are more restricted than onsets.

Preferred codas are sonorants and voiceless fricatives:

```ipa
/m n ɲ l ʎ ɾ f θ s ʃ x/
```

Voiceless stops are permitted as stronger codas:

```ipa
/p t k/
```

Voiced obstruents are normally avoided word-finally:

```ipa
/b d g v ð z ʒ ɣ d͡ʒ/
```

The final dental fricative /θ/ is a preferred high-register ending and is especially compatible with archaic, formal, or secondary morphology.

## Final Devoicing

Word-final obstruents are normally voiceless in native phonology.

| Non-final voiced obstruent | Word-final voiceless counterpart |
| -------------------------- | -------------------------------- |
| /b/                        | /p/                              |
| /d/                        | /t/                              |
| /g/                        | /k/                              |
| /v/                        | /f/                              |
| /ð/                        | /θ/                              |
| /z/                        | /s/                              |
| /ʒ/                        | /ʃ/                              |
| /ɣ/                        | /x/                              |
| /d͡ʒ/                       | /t͡ʃ/                             |

Final devoicing is the default phonological outcome for native words.
However, morphology may explicitly preserve a final voiced obstruent where it carries grammatical meaning.

The fractional number is one such example.
It is realised with a final /d/, which remains voiced despite occurring word-finally.
This preserves the morphological identity of the fractional number and gives it a distinct phonetic character.

Foreign names, technical terms, and careful citation forms may also preserve final voiced obstruents.

## Medial Clusters

Medial clusters may be broader than onset or coda clusters, especially across morpheme boundaries.

Preferred medial clusters follow one of these patterns:

```text
RC
NC
OR
Oj
```

Where:

- `R` is /l/, /ʎ/ or /ɾ/;
- `N` is /m/, /n/, or /ɲ/;
- `O` is an obstruent;
- `C` is any consonant;
- `j` is /j/.

Clusters with more than two consonants are avoided in native roots and should arise only through morphology, compounding, or non-native material.

## Sonority

Native syllables generally rise in sonority toward the vowel and fall in sonority after it.

Preferred onsets move from less sonorous to more sonorous material.
Preferred codas move from more sonorous to less sonorous material or end in a single sonorant.

This principle may be overridden at morpheme boundaries, but inherited roots should remain sonority-compliant.

## Hiatus

Roots avoid vowel hiatus.

Across morpheme boundaries, adjacent vowels may be resolved by:

- glide insertion after front vowels;
- glide insertion after back vowels;
- contraction of identical vowels;
- preservation of hiatus in careful or poetic speech.

Identical vowel contraction may be shown with a macron in dictionaries or grammatical references.

## Gemination

Consonant gemination is phonemic where specified by the lexicon or morphology.

Gemination may occur medially in native words.

Geminated affricates are avoided except in loanwords, expressive forms, or technical transcription.

## Secondary Devoicing

Secondary devoicing is a grammatical morphophonological process affecting verbs in secondary clauses.

In the affected verbal domain, voiced obstruents become their voiceless counterparts.

| Primary voiced consonant | Secondary devoiced consonant |
| ------------------------ | ---------------------------- |
| /b/                      | /p/                          |
| /d/                      | /t/                          |
| /g/                      | /k/                          |
| /v/                      | /f/                          |
| /ð/                      | /θ/                          |
| /z/                      | /s/                          |
| /ʒ/                      | /ʃ/                          |
| /ɣ/                      | /x/                          |
| /d͡ʒ/                     | /t͡ʃ/                         |

Secondary devoicing does not affect vowels, sonorants, stress, or predictable stress-based vowel length.

The grammatical scope of secondary devoicing is defined by the verbal morphology.
Phonologically, the output must respect the ordinary voiceless counterpart of each affected obstruent.

## Dubitative Mood

The dubitative mood is marked by /d͡ʒ/.

In secondary clauses, dubitative /d͡ʒ/ undergoes secondary devoicing to /t͡ʃ/.

This makes /t͡ʃ/ and /d͡ʒ/ part of the regular voicing architecture while keeping them rare in ordinary lexical material.

## Loanwords and Names

Loanwords and names may contain phonological or orthographic material outside the native system.

When naturalised, loanwords should be adapted to native grapheme-phoneme correspondence and native phonotactics.

When not naturalised, they may retain source spelling, capitalisation, and non-native letters.

## Phonological Style

Arcadian inherited vocabulary should prefer:

- sonorants over dense stop clusters;
- dental and alveolar fricatives over harsh gutturals;
- limited, strategic use of /x/ and /ɣ/;
- rare use of /t͡ʃ/ and /d͡ʒ/ outside their grammatical role;
- predictable stress and stress-based vowel length;
- moderate syllable weight rather than extreme consonant density.
