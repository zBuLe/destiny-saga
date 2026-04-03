---
layout: default
title: Ninklish
---

# 📘 **Ninklish**

The Nink people communicate differently than others; instead of conventional language, they communicate using bells and whistles. Their unique vocal abilities have led to the development of a language tailored to these sounds.

## Notation

To facilitate the study of Ninklish, a specialized notation system has been created. The details of this system are documented below.

### Solfège

Nink Solfège is a system that assigns unique symbols to musical phonemes, enabling the Nink to communicate using bells and whistles. Each phoneme (Do, Re, Mi, etc.) is represented by a specific letter, allowing for precise notation of their language.

| Note | Symbol |
| ---- | ------ |
| Do   | `D`    |
| da   | `d`    |
| Re   | `R`    |
| ri   | `r`    |
| Mi   | `M`    |
| Fa   | `F`    |
| fi   | `f`    |
| So   | `S`    |
| su   | `s`    |
| Lu   | `L`    |
| le   | `l`    |
| Ti   | `T`    |

---

### Voice

Ninks communicate using two primary vocal modes: bell voice and whistle voice. These modes can be switched freely during conversation. The notation system specifies which voice is active and indicates any changes between them.

| Symbol | Meaning |
| ---- | ------ |
| (none) | default bell voice |
| `'`    | bell voice |
| `*`    | whistle voice |

- `DRM` : DoReMi in bell voice
- `'DRM` : DoReMi in bell voice
- `*DRM` : DoReMi in whistle voice
- `*D'RM` : Do in whistle voice, ReMi in bell voice

---

### Octave

Ninks typically communicate using a three-octave vocal range. Upon reaching adulthood, they gain a fourth octave, which can expand their range either lower or higher. Octave markers in the notation indicate when the vocal range shifts; all subsequent notes remain in the new octave until another marker changes it.

| Octave Marker | Semitone Shift |
| ------------- | -------------- |
| `\\` or `¡¡`  | –24 (lower)    |
| `\` or `¡`    | –12 (low)      |
| (none) or `#` | +0  (natural)  |
| `/` or  `!`   | +12 (high)     |
| `//` or `!!`  | +24 (higher)   |

- `DRM` : DoReMi in natural octave
- `/DRM` : DoReMi in high octave
- `//DR#M` : DoRe in higher octave, Mi in natural octave
- `D\R\\M` : Do in natural octave, Re in low octave, Mi in lower octave

---

### Length

Ninks pronounce a note with a duration of 1 beat, typically at 140 bpm, though this tempo varies among individuals. They may shorten or lengthen notes as needed. The notation specifies the duration for each subsequent note.

| Marker | Duration |
| ------ | -------- |
| none   | 1 beat   |
| `:`    | ½ beat   |
| `::`   | ¼ beat   |
| `_`    | 2 beats  |
| `__`   | 4 beats  |

- `DRM` : DoReMi 1 beat in length
- `DR:M` : DoRe are 1 beat each, Mi is half beat
- `::D::RM` : Do and Re are quarter beat, Mi is one beat
- `__DR_M` : Do is quad beat, Re is one beat, Mi is double beat
- `_DR:M` : Do is double beat, Re is one beat, Mi is half beat

---

#### Tempo

| Term      |     BPM Range |
| --------- | ------------: |
| **Toll** |   20 – 60 BPM |
| **Gong** |   60 – 80 BPM |
| **Slide** |  80 – 100 BPM |
| **Peal** | 100 – 140 BPM |
| **Clash** | 140 – 180 BPM |
| **Trill** | 180 – 220 BPM |
| **Roll** | 220 – 280 BPM |

---

### Rest

Rests in Ninklish indicate pauses or silences between notes, allowing for rhythmic separation and phrasing in speech. A rest can be marked by a space or a dot (`.`) in the notation. Multiple rests can be combined for longer pauses, and rests can be assigned durations using length markers, just like notes.

| Marker | Duration |
| ------ | -------- |
| none   | 1 rest   |
| `.`    | 1 rest   |

- `DRM` : DoReMi with no rests
- `DR M` : DoRe, rest, Mi
- `DR.M` : DoRe, rest, Mi
- `D.R..M` : Do, rest, Re, rest, rest, Mi
- `D.R_.M` : Do, rest, Re, double rest, Mi
- `D.R::.M` : Do, rest, Re, quarter rest, Mi
- `D.R:: M` : Do, rest, Re, quarter rest, Mi
- `D.R::.::M` : Do, rest, Re, quarter rest, quarter Mi

---

## DoTi Mode

By default, Nink notes are interpreted as words. However, there are situations where they need to represent something else. "DoTi" is a term in Ninklish that signals the following notes should be interpreted differently. DoTi mode continues until a double pause or a longer rest occurs, which ends the mode.

| Mode              | Notation  |
| ----------------- | --------- |
| **Numbers** | `*:D:T`   |
| **Letters** | `':D:T`   |
| **Nink Names** | `':D*:T`  |
| **Foreign Names** | `*:D':T`  |

### Numbers `*:D:T`

Cardinal numbers are always conveyed in whistle voice and use the natural octave. They are primarily used for counting.

| Note   | Digit |
| ------ | ----- |
| `d`    | 0     |
| `R`    | 1     |
| `r`    | 2     |
| `M`    | 3     |
| `F`    | 4     |
| `f`    | 5     |
| `S`    | 6     |
| `s`    | 7     |
| `L`    | 8     |
| `l`    | 9     |

- `*:D:T RrM` : 123
- `*:D:T l` : 9
- `*:D:T sd R` : 70, 1
- `*:D:T M M d` : 3, 3, 0

---

### Letters `':D:T`

Ninks use a distinct system for ordinal numbers, separate from their cardinal numbers. There are 26 ordinal levels, each mapped to a letter of the alphabet. Ordinals are always pronounced in bell voice and utilize notes from both the low and high octaves.

| High | Letter |   | Natural | Letter |   | Low  | Letter |
|------|--------|---|---------|--------|---|------|--------|
| `/S` | A      |   | `l`     | I      |   | `\T` | S      |
| `/f` | B      |   | `L`     | J      |   | `\l` | T      |
| `/F` | C      |   | `s`     | K      |   | `\L` | U      |
| `/M` | D      |   | `S`     | L      |   | `\s` | V      |
| `/r` | E      |   | `f`     | M      |   | `\S` | W      |
| `/R` | F      |   | `F`     | N      |   | `\f` | X      |
| `/d` | G      |   | `M`     | O      |   | `\F` | Y      |
| `/D` | H      |   | `r`     | P      |   | `\M` | Z      |
|      |        |   | `R`     | Q      |   |      |        |
|      |        |   | `d`     | R      |   |      |        |

- `':D:T /sdF` : ABC
- `':D:T \fFM` : XYZ
- `':D:T RMF` : QON
- `':D:T \Tl/s#d\l` : START

---

### Nink Names `':D*:T`

Nink names start with at least one order (letter), followed by a count (number): D935, T983, B137, KR1574, A923, GW797.

- `':D*:T '/M#*lMf` : D935
- `':D*:T '\l#*lLM` : T983
- `':D*:T '/f#*RMs` : B137
- `':D*:T 'sd*Rfs` : KR157
- `':D*:T '/s#*lrM` : A923
- `':D*:T '/d\S#*sls` : GW797

---

#### Nink Name Normalization

Nink names are often normalized to make them easier to pronounce or remember. This can involve substituting parts of the name based on how they sound when spoken, or by using visual similarities between letters and numbers. For example, the number "4" resembles the letter "A" and, when pronounced, "four" can be used in place of "F" or "FO".

- `D935` : Demitri
- `T983` : Tina
- `B137` : Birt
- `KR157` : Krista
- `A923` : Anya
- `GW797` : Gwen

---

#### Foreign Names `*:D':T`

Used to represent names of individuals who are not Nink. When encoding a foreign name, each vowel in the name is mapped to one or more corresponding notes, as shown in the table above. Any note associated with a vowel is valid, and the speaker may freely choose between bell or whistle voice for each note.

| Vowel | Options             |
| ----- | ------------------- |
| A     | `d` , `F`           |
| E     | `R` , `l`           |
| I     | `r`, `M`, `f` , `T` |
| O     | `D` , `S`           |
| U     | `s` , `L`           |

- Sara : `*:D':T dF`
- Sara : `*:D':T /F'F`
- Manuel : `*:D':T FsR`
- Leonardo : `*:D':T lDFS`
- Sonia : `*:D':T SMd`

---

## Voice Properties

Each Nink has unique properties that shape their vocal characteristics:

- **Natural Tone:** The root note for their voice, which determines their vocal range. This typically falls between A1 and C#7.
- **Whistle Offset:** The whistle voice’s root note is set as an offset from the bell voice’s natural tone, but must remain within the A1 to C#7 range.
- **Developed Octave:** Ninks possess three octaves by default. As they mature, they may gain a fourth octave, either higher or lower than their initial range.
- **Full Range:** Calculated from the natural tone, spanning –12 semitones for the lowest note and +23 for the highest. If a fourth octave is developed, –12 is added for a lower octave or +12 for a higher octave. The whistle range is derived by applying the whistle offset to the full range.
- **Personal Shift:** Ninks can modulate their voices by shifting their natural note, affecting both bell and whistle voices equally. This does not alter their full range. Attempting notes outside their range may strain their voice.

> **Example Stats**
> Name: D935 - "Dimitri"
> Natural Tone: C3
> Whistle Offset: 0
> Fourth Octave: Higher
> Full Range: C2 - B5
> Pace: Trill
> Note: He tends to Shift -4 when speaking to M174 - "Mila"

## Grammar

The meaning of a base word can be changed by the manner in which the last note is pronounced. This is marked by accent marks: `~` (tilde), `´` (acute), and `` ` `` (grave). Alternatively, `:=`, `:+`, and `:-` can be appended after the modified note.

This is used to indicate if the pronunciation of the note is doubled, pitched up, or pitched down. In effect, the modified note is split from one beat into two half beats. The first half beat is the same as the original note. The second half beat is either the same note, one semitone higher, or one semitone lower.

| Script | Typed  | Speech  |
|--------|--------|---------|
| DRM̃    | DRM:=  | DR:M:M  |
| DRḾ    | DRM:+  | DR:M:F  |
| DRM̀    | DRM:-  | DR:M:r  |

While it depends on the root word, typically a **double note** indicates a plural. It can also make a concept greater, bigger, or represent an opposite.

**Pitched up** notes tend to signify agreement, "good," increasing, or a positive variant.
**Pitched down** notes tend to indicate disagreement, "bad," decreasing, or a negative variant.

| Base Note | Double (:=) | Pitch Up (:+) | Pitch Down (:-) |
| :-------: | :---------: | :-----------: | :-------------: |
|   **D** |  D̃ `:D:D`   |   D́ `:D:d`    |    D̀ `:D:\T`    |
|   **d** |  d̃ `:d:d`   |   d́ `:d:R`    |    d̀ `:d:D`     |
|   **R** |  R̃ `:R:R`   |   Ŕ `:R:r`    |    R̀ `:R:d`     |
|   **r** |  r̃ `:r:r`   |   ŕ `:r:M`    |    r̀ `:r:R`     |
|   **M** |  M̃ `:M:M`   |   Ḿ `:M:F`    |    M̀ `:M:r`     |
|   **F** |  F̃ `:F:F`   |   F́ `:F:f`    |    F̀ `:F:M`     |
|   **f** |  f̃ `:f:f`   |   f́ `:f:S`    |    f̀ `:f:F`     |
|   **S** |  S̃ `:S:S`   |   Ś `:S:s`    |    S̀ `:S:f`     |
|   **s** |  s̃ `:s:s`   |   ś `:s:L`    |    s̀ `:s:S`     |
|   **L** |  L̃ `:L:L`   |   Ĺ `:L:l`    |    L̀ `:L:s`     |
|   **l** |  l̃ `:l:l`   |   ĺ `:l:T`    |    l̀ `:l:L`     |
|   **T** |  T̃ `:T:T`   |   T́ `:T:/D`   |    T̀ `:T:l`     |

## Vocabulary

### One Beat Words

| Word | Base                | ( := ) | Double      | ( :+ )  | Pitch Up      | ( :- ) | Pitch Down    |
|------|---------------------|--------|-------------|---------|---------------|--------|---------------|
| `D`  | I / me              | `:D:D` | we / us     |         | --            |        | --            |
| `d`  | you                 | `:d:d` | you all     |         | --            |        | --            |
| `R`  | he / she / it       | `:R:R` | they / them |         | --            |        | --            |
| `r`  | to speak/state      |        | --          | `:r:M`  | shout/born    | `:r:R` | silence/die   |
| `M`  | to eat/drink        |        | --          | `:M:F`  | feast/heal    | `:M:r` | starve/suffer |
| `F`  | to hear/understand  |        | --          | `:F:f`  | yes           | `:F:M` | no            |
| `f`  | and                 | `:f:f` | not         | `:f:S`  | or            | `:f:F` | either        |
| `S`  | if                  | `:S:S` | while       | `:S:s`  | then          | `:S:f` | else          |
| `s`  | to sense/experience |        | --          | `:s:L`  | joy           | `:s:S` | sad           |
| `L`  | to do/act/work      |        | --          | `:L:l`  | active/ awake | `:L:s` | laze/ rest    |
| `l`  | to possess/belong   |        | --          | `:l:T`  | receive/ take | `:l:L` | give/ lose    |
| `T`  | to stop/finish      |        | --          | `:T:/D` | don't stop    | `:T:l` | STOP NOW      |

### Two Beat Words

| Base Word | Meaning          | ( := )  | Double          | ( :+ )   | Pitch Up                      | ( :- )   | Pitch Down                       |
|-----------|------------------|---------|-----------------|----------|-------------------------------|----------|----------------------------------|
| **`Dd`** | friend           | `D:d:d` | "friends"       | `D:d:R`  | "ally"                        | `D:d:D`  | "frenemy"                        |
| **`Rd`** | rival            | `R:d:d` | "rivals"        | `R:d:R`  | "challenger"                  | `R:d:D`  | "enemy"                          |
| **`MD`** | food             | `M:D:D` | "meal"          | `M:D:d`  | "delicious"                   | `M:D:\T` | "spoiled"                        |
| **`sL`** | water            | `s:L:L` | "beverage"      | `s:L:l`  | "medicine"                    | `s:L:s`  | "poison"                         |
| **`lL`** | tool             | `l:L:L` | "tools"         | `l:L:l`  | "masterwork tool"             | `l:L:s`  | "broken tool"                    |
| **`Dl`** | home             | `D:l:l` | "village"       | `D:l:T`  | "sanctuary"                   | `D:l:L`  | "prison"                         |
| **`ST`** | day / light      | `S:T:T` | "days"          | `S:T:/D` | "dawn / morning"              | `S:T:l`  | "dusk / twilight"                |
| **`dr`** | dark / night     | `d:r:r` | "nights"        | `d:r:M`  | "midnight"                    | `d:r:R`  | "shadow"                         |
| **`sT`** | sky / above      | `s:T:T` | "skies"         | `s:T:/D` | "heavens / zenith"            | `s:T:l`  | "storm / overcast"               |
| **`Lf`** | land / ground    | `L:f:f` | "lands"         | `L:f:S`  | "fertile ground"              | `L:f:F`  | "barren land"                    |
| **`fS`** | Sun              | `f:S:S` | "Noon"          | `f:S:s`  | "Sunrise/ Morning"            | `f:S:f`  | "Sunset/ Twilight"               |
| **`Sf`** | Moon / Full Moon | `S:f:f` | "New Moon"      | `S:f:S`  | "Waxing Moon / First Quarter" | `S:f:F`  | "Waning Moon / Third Quarter"    |
| **`LR`** | thought          | `L:R:R` | "ideas"         | `L:R:r`  | "insight"                     | `L:R:d`  | "confusion"                      |
| **`TS`** | time / present   | `T:S:S` | "NOW"           | `T:S:s`  | "future"                      | `T:S:f`  | "past"                           |
| **`TT`** | warning / danger | `T:T:T` | "calamity"      | `T:T:/D` | "foreboding"                  | `T:T:l`  | "all-clear / safety"             |
| **`LL`** | parent           | `L:L:L` | "family / clan" | `L:L:l`  | "mother"                      | `L:L:s`  | "father"                         |
| **`DT`** | (encode) shift   |         | (none)          |          | (none)                        |          | (none)                           |
| **`rM`** | Warm Colors      | `r:M:M` | orange          | `r:M:F`  | yellow                        | `r:M:r`  | Red                              |
| **`Mr`** | Cool Colors      | `M:r:r` | blue            | `M:r:M`  | purple                        | `M:r:R`  | green                            |

### Three Beat Words

| Word      | Base           | ( := ) | Double | ( :+ ) | Pitch Up | ( :- ) | Pitch Down |
|-----------|----------------|--------|--------|--------|----------|--------|------------|
| **`lLl`** | weapon         |        | --     |        | --       |        | --         |
| **`lLs`** | instrument     |        | --     |        | --       |        | --         |
| **`RTR`** | The North Tree |        | --     |        | --       |        | --         |
| **`STS`** | Eastern Cliffs |        | --     |        | --       |        | --         |
| **`FTF`** | Southern Falls |        | --     |        | --       |        | --         |
| **`MTM`** | West Caverns   |        | --     |        | --       |        | --         |