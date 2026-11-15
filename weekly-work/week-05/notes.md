# Corpus Analysis – Notes

---

## Part 6

### Step 1: Cirrus

- **Word count:** 134,815 unique forms
- **Largest words in Cirrus:** *government, people, states, great, shall*
- **Word size:** Shows either raw or relative frequency. I did not find any information on which one, but I would go with raw frequency.
- **Possible stop words:** "the", "and", "or", etc.

### Step 2: Corpus Terms

| Term     | Count |
|----------|------:|
| citizens | 243   |
| freedom  | 187   |
| public   | 225   |
| country  | 295   |
| spirit   | 139   |

- **Prominence:** *congress*
- **Historical question:** *foreign*

### Step 3: Observation vs. Explanation

- **Evidence:** In the processed corpus, the token *power* occurs 233 times and ranks among the 15 most frequent displayed terms.
- **Possible interpretation:** This pattern might relate to power in a political, militaristic, public or personal sense. Establishing that interpretation would require examining the context in which the word was used and comparing it with other use cases.

---

## Part 7

### Step 1: Default Setting

- **Stopwords:** auto recognition

### Step 2

- **Most frequent words now:** *the, of, and, to, in*
- The word cloud doesn't convey any real information about the corpus. Just looking at the cloud (depending on how many words are shown) will not give you insight into the content of the speeches.
- **Less visible now:** *state, people, government, nation*

### Step 4

- **Excluded term:** *right*
- **Why?** It can refer to *right* in a juridical, political or directional sense, but also to correctness.
- **Result:** The top terms did not change.

### Reflection Questions

1. With the auto-generated stopwords, the word cloud is more meaningful for a historical analysis of the text. From a literary standpoint, using no stopwords could provide more useful insight, depending on the research question.
2. Trying to understand word density / language vs. content.
3. Because it is needed to understand what has been left out of the interpretation.

---

## Part 8

### Step 2: Trends

The graph uses relative frequency. I did not find the raw values at first, so I recorded the relative ones *(edit: I should have just read ahead)*.

| Address            | Term       | Relative  | Raw |
|--------------------|------------|----------:|----:|
| 19_lincoln_1861    | people     | 0.0054990 | 20  |
|                    | government | 0         | 0   |
|                    | nation     | 0         | 0   |
| 36_hoover_1929     | people     | 0.0043814 | 17  |
|                    | government | 0.0085052 | 33  |
|                    | nation     | 0.0030928 | 12  |
| 9_monroe_1821      | people     | 0.0024559 | 11  |
|                    | government | 0.0029024 | 13  |
|                    | nation     | 0.0017861 | 8   |

### Step 3: Visual

- **Top 3 (raw):** 15_polk_1845, 14_harrison_1841, 36_hoover_1929
- Switching to relative frequency flattens the graph a bit, and the top 3 change as well.

### Step 4: Provisional Observation

> In this corpus, the relative frequency of *government* is higher in the 15_polk_1845 address than in the 26_harrison_1889 address.

- **Important note:** Both speeches have a similar length (Polk: 4,814 words vs. Harrison: 4,400 words).
- **Possible reasons:** The focus of the speeches – Polk focuses on government, whereas Harrison talks about the people.

### Step 5

- A difference between presidents
- A feature of changing inaugural rhetoric

---

## Part 9

### Step 2

#### 15_polk_1845

> "… of every man who lives upon our soil, whether of native or foreign birth; of every religious sect, …"

- **Appears to refer to:** immigrants
- **Helpful words:** *soil, native, birth*
- **Tone:** contrast

#### 12_jackson_1833

> "… to the confidence and affections of the American people. Finally …"

- **Appears to refer to:** the US population
- **Helpful words:** *American*
- **Tone:** positive

#### 34_harding_1921

> "… and the righteousness of representative democracy, where our freedom never has made offensive warfare, …"

- **Appears to refer to:** the freedom of the nation
- **Helpful words:** *our*
- **Tone:** positive
