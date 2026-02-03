# Model Outputs (Zero-shot vs Few-shot)

**Model:** GPT-4–class LLM  
**Runs per prompt:** 3  
**Method:** Same task, same input domain

---

## Zero-shot Prompt

### Run 1
* The platypus evolved in long isolation in Australia, where mammals followed different evolutionary paths.
* It retained egg-laying from early mammal ancestors, before live birth became dominant.
* A cloaca persists because its lineage split before separate openings evolved in most mammals.
* The duck-like bill developed as a sensory organ packed with electroreceptors for hunting underwater.
* Webbed feet improve swimming, while claws support digging burrows on land.
* Venomous spurs in males likely evolved through sexual competition rather than hunting.

### Run 2
* The platypus evolved in geographic isolation, allowing ancient mammalian traits to persist.
* Egg-laying reflects retention of early mammal reproductive biology.
* A cloaca remains because its lineage diverged before specialized openings evolved.
* The bill functions as a sensory organ with electroreceptors for detecting prey underwater.
* Webbed feet support swimming, while claws aid digging and movement on land.
* Male venomous spurs evolved for competition during mating rather than for defense or hunting.

### Run 3
* Long geographic isolation allowed early mammalian traits to persist.
* Egg-laying reflects inheritance from primitive mammal ancestors.
* A cloaca remains because the lineage diverged before separate openings evolved.
* The bill evolved as a highly sensitive electroreceptive organ for underwater hunting.
* Webbed feet improve swimming, while claws support digging and movement on land.
* Male venomous spurs evolved through sexual competition rather than predation.

---

## Few-shot Prompt

### Run 1
The platypus evolved in isolation in Australia, where early mammals faced little competition
and experimented with different survival strategies.
Its mix of traits—egg-laying, a duck-like bill, electroreception, and venom—reflects an ancient
evolutionary lineage that combines reptile-like and mammal-like features adapted to a semi-aquatic life.

### Run 2
The platypus evolved in long geographic isolation in Australia,
where early mammals adapted to unique ecological conditions.
Its unusual traits, such as egg-laying, a sensitive bill, and venom,
helped it survive and hunt effectively in freshwater environments.

### Run 3
The platypus evolved in isolated freshwater environments in Australia,
where early mammals adapted to unusual ecological niches.
Traits like egg-laying, a sensitive bill, and venom helped it survive,
find food, and compete successfully in its habitat.

---

### Notes
- Zero-shot outputs showed high informational detail but varied in structure and formatting across runs.
- The model independently chose list-based responses in zero-shot runs, without explicit instructions.
- Few-shot outputs consistently followed the narrative style and length demonstrated in the example.
- A single example was sufficient to significantly reduce structural variability.
- Content relevance was preserved across both prompting strategies.


