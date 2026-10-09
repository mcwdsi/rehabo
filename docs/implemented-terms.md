# REHABO — Implemented Terms

**Last updated:** October 2026  
**Source file:** `src/ontology/rehabo-edit.owl`  
**Total:** 63 classes + 4 object properties = **67 named terms**

This page lists every term currently implemented in the REHABO ontology, grouped by category.
No GitHub account or technical knowledge is needed to view this page.
To propose a new term, see [Contributing](contributing.md).

---

## Therapy Types

| REHABO ID | Label | Parent Class |
|---|---|---|
| REHABO:0000000 | rehabilitation therapy | therapeutic procedure (OGMS:0000112) |
| REHABO:0000001 | physical therapy | rehabilitation therapy |
| REHABO:0000002 | occupational therapy | rehabilitation therapy |
| REHABO:0000010 | meta-cognitive strategy training | therapeutic procedure (OGMS:0000112) |

---

## Therapy Cues

| REHABO ID | Label | Parent Class |
|---|---|---|
| REHABO:0000003 | rehabilitation therapy cue | communicative act (OMRSE:00002068) |
| REHABO:0000004 | guided rehabilitation therapy cue | rehabilitation therapy cue |
| REHABO:0000005 | directed rehabilitation therapy cue | rehabilitation therapy cue |

---

## Encounters

| REHABO ID | Label | Parent Class |
|---|---|---|
| REHABO:0000006 | rehabilitation encounter | health care encounter (OGMS:0000097) |
| REHABO:0000007 | physical therapy encounter | health care encounter (OGMS:0000097) |
| REHABO:0000008 | occupational therapy encounter | health care encounter (OGMS:0000097) |

---

## Roles

| REHABO ID | Label | Parent Class |
|---|---|---|
| REHABO:0000009 | occupational therapist role | institutional health care provider role (OMRSE:00000300) |
| REHABO:0010001 | physical therapist role | institutional health care provider role (OMRSE:00000300) |
| REHABO:0011018 | task object role | role (BFO:0000023) |

---

## Body Functions

| REHABO ID | Label | Parent Class |
|---|---|---|
| REHABO:0000013 | musculoskeletal system function | function (BFO:0000034) |
| REHABO:0000014 | nervous system function | function (BFO:0000034) |
| REHABO:0000015 | bodily movement function | musculoskeletal system function |
| REHABO:0000016 | motor control function | nervous system function |
| REHABO:0000017 | bodily mobility function | function (BFO:0000034) |
| REHABO:0011004 | joint function | function (BFO:0000034) |
| REHABO:0011005 | muscle function | function (BFO:0000034) |
| REHABO:0011006 | range of motion function of a joint | joint function |
| REHABO:0011007 | power of a muscle | muscle function |
| REHABO:0011008 | strength of a muscle | muscle function |

---

## Joint Motion

| REHABO ID | Label | Parent Class |
|---|---|---|
| REHABO:0000012 | joint motion | bodily process (OGMS:0000060) |
| REHABO:0011001 | range of motion process | joint motion |
| REHABO:0011002 | active range of motion process | range of motion process |
| REHABO:0011003 | passive range of motion process | range of motion process |
| REHABO:0000011 | active assisted range of motion process | range of motion process |

---

## Exercise

| REHABO ID | Label | Parent Class |
|---|---|---|
| REHABO:0011011 | physical exercise | bodily process (OGMS:0000060) |
| REHABO:0011012 | range of motion exercise | physical exercise |
| REHABO:0011013 | active range of motion exercise | range of motion exercise |
| REHABO:0011014 | passive range of motion exercise | range of motion exercise |
| REHABO:0011015 | active assisted range of motion exercise | range of motion exercise |
| REHABO:0011016 | strength exercise | physical exercise |
| REHABO:0011017 | power exercise | physical exercise |

---

## Energy and Exertion

| REHABO ID | Label | Parent Class |
|---|---|---|
| REHABO:0010022 | bodily energy expenditure | bodily process (OGMS:0000060) |
| REHABO:0010023 | physical exertion | bodily energy expenditure |

---

## Dispositions

| REHABO ID | Label | Parent Class |
|---|---|---|
| REHABO:0010012 | facilitation-requiring disposition | disposition (BFO:0000016) |
| REHABO:0010013 | facilitating | process (BFO:0000015) |
| REHABO:0010014 | requires physical assistance disposition | facilitation-requiring disposition |
| REHABO:0010015 | requires assistive device disposition | requires physical assistance disposition |
| REHABO:0010016 | requires personal assistance disposition | requires physical assistance disposition |
| REHABO:0010024 | requires minimal personal assistance disposition | requires personal assistance disposition |
| REHABO:0010025 | requires moderate personal assistance disposition | requires personal assistance disposition |
| REHABO:0010026 | requires maximal personal assistance disposition | requires personal assistance disposition |
| REHABO:0010027 | requires total personal assistance disposition | requires personal assistance disposition |

---

## Assistive Devices

| REHABO ID | Label | Parent Class |
|---|---|---|
| REHABO:0010002 | medical device | object (BFO:0000030) |
| REHABO:0010003 | activity of daily living assistive device | medical device |
| REHABO:0010004 | locomotion assistive device | activity of daily living assistive device |
| REHABO:0010005 | assistive device for donning or removing clothing | activity of daily living assistive device |
| REHABO:0010006 | grasping or holding assistive device | object (BFO:0000030) |
| REHABO:0010007 | wheelchair | locomotion assistive device |
| REHABO:0010028 | patient lift | activity of daily living assistive device |
| REHABO:0000018 | wheeled walker *(rollator)* | locomotion assistive device |
| REHABO:0000019 | hemi walker | locomotion assistive device |
| REHABO:0000020 | single point cane *(SPC)* | locomotion assistive device |
| REHABO:0000021 | quad cane | locomotion assistive device |
| REHABO:0000022 | sliding board *(transfer board)* | locomotion assistive device |
| REHABO:0010017 | sock aid | assistive device for donning or removing clothing |
| REHABO:0010018 | dressing stick | assistive device for donning or removing clothing |
| REHABO:0010019 | shoe horn | assistive device for donning or removing clothing |
| REHABO:0010020 | long handled shoe horn | shoe horn |
| REHABO:0010021 | reacher device | grasping or holding assistive device |

---

## Object Properties (Relations)

These are the relations defined by REHABO, used to connect classes to one another.

| REHABO ID | Label | Parent Property |
|---|---|---|
| REHABO:0010008 | is realizably related to | — *(top-level REHABO property)* |
| REHABO:0010009 | is facilitated by | is realizably related to |
| REHABO:0010010 | is reciprocal realizable of | is realizably related to |
| REHABO:0010011 | is necessarily facilitated by | is facilitated by |

---

## Terms in Progress

The following categories are under active discussion and will be added in upcoming pull requests.
See the [GitHub Issues](https://github.com/mcwdsi/rehabo/issues) page for details.

- **Client position** — supine, long sit, sitting edge of bed (EOB), standing, seated in wheelchair
- **Mood and temperament** — patient behavioral and affective observations during therapy (pleasant, fatigued, flat affect, etc.)
- **Assist level (remaining)** — independent, modified independent, supervision, contact guard, hand-over-hand assist, assisted fall
