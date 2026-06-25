---
layout: page
title: Guidelines
order: 3
---
<div id="top"></div>
* Table of Contents
{:toc}

# Set-up & Directions
## Getting your data
## Using the script

## The Task
The script will begin with the first interval and proceed through all intervals as you click through the options. Please note that when you have reached a specific interval, we're expecting you are changing the right most boundary (the offset) for that phone.

A dialog box will appear and ask you to select from the options how you would like to proceed with the selected boundary. Select the option according to your judgement of whether the boundary is correct or not:

<span style="color:red">**Do not press STOP**</span>

<span style="color:red">**Next**</span> Select if the boundary is correct and it will proceed to the next interval.

<span style="color:red">**Adjust**</span> Select if you would like to adjust the boundary. 

<span style="color:red">**Add**</span> Select if you would like to add a boundary. This will proceed to a secondary question that will prompt you for the phone label.

<span style="color:red">**Remove**</span> 


# Canonical Boundary Placement
You will be updating the right boundary in an interval. Keep in mind this serves as the end boundary for the current interval, but the initial boundary for the following interval. So you must consider both segments when shifting the boundary.

Consider the canonical placements below when determining whether a boundary is placed "correctly" or not. 
- If they follow these canonical placements, select 'Next' on the script. 
- If they do not follow the canonical placements, select 'Adjust' on the script and move the boundary to a more canonical location. (Or, if necessary, 'Add' or 'Remove')

## Stop Consonants and Affricates
Phones: P, T, K, B, D, G, CH, and JH

### Voiceless stop consonants
#### Following silence
In English, voiceless stops have a longer period of noise following release of the burst than voiced consonant do. The boundary should be placed adjacent to and preceding the release of the burst.

Example: 
![voiceless stop](/assets/img/sil_p.png)

#### Preceding silence & transitions
The boundary should be placed at the release of the consonant, include any phonation, aspiration, or noise associated with the release, but exclude exhalation.

[Back to TOC](#top)

### Voiced stop consonants
#### Following silence
For voiced stops without pre-voicing, the boundary should be placed adjacent to the short release burst. This may result in a very short segmental duration between the stop burst and the onset of the following vowel.

Example: ![voiced stop following silence](/assets/img/sil_b.png)

For voiced stops with pre-voicing, the onset boundary of the segment should include any pre-voicing; place preceding and adjacent to the voicing onset.

Example: ![voiced stop with prevoicing](/assets/img/sil_d_pvcd.png)

#### Preceding silence & transitions
The boundary should be placed at the release of the consonant, include any phonation, aspiration, or noise associated with the release, but exclude exhalation.

Place the boundary for the beginning of the unreleased consonant at the end of formant structure of the vowel, and place the final boundary at the end of visible energy related to the consonant.

[Back to TOC](#top)

### Stops in Connected Speech

**Unreleased Stops**

For voiced stops, place the boundary for the beginning of the unreleased consonant at the end of formant structure of the vowel, and place the final boundary at the end of visible energy related to the consonant.

Without visible glottalization but visible voicing following formant cessation, include only the voicing following formant cessation.

For voiceless stops, if you see an indication of the closure for the stop with no release, you can mark the onset at the closure and then the offset <=10ms. 

Example: ![voiceless stop](/assets/img/p_sil_unreleased.png)


*If no visual or auditory indication of the consonant, delete the segment.* 
In the previous example, you can choose to delete the segment altogether. We think this is a judgement call, so use your intuition. Below is another example 

Example: ![voiceless stop](/assets/img/mp_sil.png)

**Glottalization**

With visible glottalization and no creaky vowel, include the glottalization as part of the segment and place the boundary where glottalization ends.

With visible glottalization and the presence of a creaky vowel, segment the final two glottal pulses.

[Back to TOC](#top)

### Fricatives & Affricates
#### Following silence
Phones: S, Z, H, SH, ZH, F, V, TH, and DH

The boundary should be placed adjacently preceding the first sign of frication noise for the fricative.

Example: ![voiceless stop](/assets/img/sil_s.png)

#### Preceding silence
The boundary should be placed at the end of the noise associated with articulation of the fricative/affricate (be sure to listen to make sure that the noise doesn’t include exhalation).

[Back to TOC](#top)

### Nasals 
#### Following silence
Phones: M, N, and NG

The boundary is placed adjacent preceding the onset of phonation/nasalization. 

Visual anchors: Anti-formants during the segment and lower amplitude compared to surrounding segments. At the offset of the nasal, a rise in F1/F2

Example: ![voiceless stop](/assets/img/initial_nasal.jpg)

#### Preceding silence & transitions
The boundary should placed at the end of phonation and articulation associated with the nasal consonant but excluding exhalation. Look for evidence of F1 dropping out in the spectrogram. There is often spectral discontinuity between nasals and vowels, which may mark transition between phones.

### Liquids and Rhotics
Phones: L and R

#### Following silence
**L - Lateral Approximant**

The boundary should be placed at the onset of the segment. This may be clear phonation and intensity seen as nearly black on the spectrogram. Some formants started to be present as part of the articulation of L, so the boundary should be placed at the onset of the noise and formant structure.

Example: ![voiceless stop](/assets/img/initial_liquid.jpg)

**R - Rhotic**
Place boundary at the onset of articulation-related noise in the signal. In this case, some articulation of R preceded phonation.

Example: ![voiceless stop](/assets/img/initial_rhotic.jpg)

#### Preceding silence & transitions
**L - Lateral Approximant**

Look for vowel-like formants, but note that the acoustic energy is weaker than regular vowels, and higher than nasals.

**R - Rhotic**

The boundary should be placed at the transition into the next segment or at the cessation of acoustic energy preceding silence. Look for the F3 band plunges downward, sometimes almost touching F2. The offset of the liquid is the exact point where F3 begins to rapidly rise in frequency for the following vowel.

[Back to TOC](#top)

### Vowels and Glides
#### Following silence
**Vowels**
The boundary should be placed at the onset of phonation/laryngeal activity related to the beginning of the vowel. Look for the onset of complex voicing (with higher frequency components).

Example: ![voiceless stop](/assets/img/initial_vowel.jpg)

“Glottal pop” at the beginning of a vowel should be included as part of the vowel and the boundary should be placed adjacent to the glottal pulse.

**Glides (W and Y)**
The boundary placed at the onset of phonation or articulation (onset of glide may be something like a voiceless vowel).

Example: ![voiceless stop](/assets/img/initial_glide.jpg)

[Back to TOC](#top)

#### Preceding silence & transitions

[Back to TOC](#top)

## Ambiguity & fuzzy boundaries
### Transitions
Transition segments of consonants and vowels should be included in the vowel portion. If the vowel segmentation occurs within the transition but does not include the entire transition, you do not need to adjust the boundaries.

### Reductions
Connected speech reductions that result in deletion of segments from the citation form (e.g., /P R AA1 B AH0 B L IY0/ -> [P R AA1 B L IY0]) should have the phones removed.

### Consonant deletion
Listen to the audio for verification of whether the consonant is produced in addition to using the visual cues in the spectrogram. 

If no visual or auditory indication of the consonant, delete the segment.

For stop consonant clusters (e.g., skipped [S K IH1 P T]), if there is an audible cluster, place the segment halfway through the closure and the final boundary at the end of the aspiration. 

## Special Cases
### Syllabic Consonants
There are two ways we will deal with syllabic liquids, for /l/ there will be two phone segments, and for /r/ there will be a single phone segment. Be aware of this when you're reviewing the boundaries and adjust accordingly.

**Syllabic L:** Occurs word finally in unstressed syllables (words ending in -le, -al, -el, -ol)

Rule: keep the vowel but make the duration of the vowel segment very short in duration (<=10ms).

**Syllabic Nasals:**
Rule: keep the vowel but make the duration of the vowel segment very short in duration (<=10ms).

**Syllabic R:** 
Rule: syllabic R should be indicated by a single phone-label, [ER0], thus should be segmented to contain the entire interval.

[Back to TOC](#top)

## Removing and adding segments
### When to delete segments
Only delete segments if there is an error or when there is clear evidence that the segment is not present audibly or visually, such as consonant cluster reduction or unreleased consonants.

Occasionally silence phones will be inserted where there is no silence, in these cases you can delete the silence phone and merge it with the following segment, and adjust the new phone boundary as needed.

In some cases, stop closures can be long for emphasis or performative reasons and there will occasionally be a silence inserted. Review the sound file, if it sounds like a transition into a stop closure, delete the silence and lengthen the closure.

Select "Remove" to merge the sound with the following segment and provide the correct phone label.

### When to add segments
Only insert segments when a segment is clearly missing. 

Cases where segments may be missing:

- Silence at the beginning of the file. There should be a <sil> phone at the beginning of each file, but if it is not present you can insert a boundary at the onset of the initial phone.
- Insert silence if there appears to be 20-30ms of silence between phones that is currently missing.
- Clear errors in alignment or pronunciation, where the wrong pronunciation variant was chosen and a segment is missing from the pronunciation. These cases are very rare.

Select "Add" to add an new boundary and provide the correct phone label.

[Back to TOC](#top)
