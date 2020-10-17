---
patient: "{{ substr .Name  17 -11 | humanize | title }}"
type: "assessment"
date: {{ substr .Name 0 10 }}
time: "{{ replace (substr .Name 11 5) "-" ":" }}"
toc: true
---

# {{ substr .Name  17 -11 | humanize | title }}

**Date of assessment:** {{ dateFormat "2 January 2006" (substr .Name 0 10) }}, {{ replace (substr .Name 11 5) "-" ":" }}

## Patient Details

#### DoB / Age:

#### Email address:

#### Other contact details: *(if provided)*

#### [Informed Consent](/docs/informed-consent/) Agreed: *(note any questions here)*

#### Occupation:

#### General medical history: *(previous injuries, medications, operations, etc)*

#### Red flags:

#### Daily activity level:

#### Sport / exercise: *(type, level, position, competition, training, intensity, frequency,  duration)*

## Subjective Assessment

#### Description of main problem:

#### Location:

#### History of main problem: *(and previous treatment if applicable)*

#### Pain level and description:

#### Aggravating:

#### Easing:

#### 24 hour cycle: *(On wake, on rise, day, evening, sleeping)*

#### SIN:

#### Do they have any theories on what the problem is?

#### What questions / worries / major concerns do they have?

## Objective Assessment

#### Observation:

#### Palpation:

### Physiological Movements

| Area | Action | Active | Passive | Resisted |
| ---- | ------ | ------ | ------- | -------- |
|      |        |        |         |          |
|      |        |        |         |          |
|      |        |        |         |          |
|      |        |        |         |          |

### Accessory Movements

| Area | Accessory | Pain / Stiffness / NAD / ROM |
| ---- | --------- | ---------------------------- |
|      |           |                              |
|      |           |                              |
|      |           |                              |
|      |           |                              |

### Muscle Tests

| Muscle | Notes |
| ------ | ----- |
|        |       |
|        |       |
|        |       |
|        |       |

### Ligament Tests

| Ligament | Notes |
| -------- | ----- |
|          |       |
|          |       |
|          |       |
|          |       |

### Special Tests

| Test | +ive / -ive | Notes |
| ---- | ----------- | ----- |
|      |             |       |
|      |             |       |
|      |             |       |
|      |             |       |

### Joints Above/Below

| Area | Action | Notes |
| ---- | ------ | ----- |
|      |        |       |
|      |        |       |
|      |        |       |
|      |        |       |

#### Additional comments:

#### Possible diagnoses:

## Treatment

#### What are they looking for from treatment?

#### What do they think will help?

#### What barriers to success can we identify?

#### General advice / education given: *(Timeframes, physiology, expectations, resources)*

#### Details of exercises given: *(What, when, why, how long/much, daily movement, graded, flare ups, equipment)*

#### Goals, timeframes and markers: