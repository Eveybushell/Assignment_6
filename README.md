# Assignment_6
## by Evelyn Bushell

### LLM Used
ChatGPT via browser

### Task
Extract particular elements in a freeform excerpt into JSON format

### Prompt types

| Prompt | Score | Notes |
|-------|-----|----------|
| Baseline | 4 | Correctly identified food, but not in JSON and included extraneous information |
| System Prompt | 5 | (Requested JSON format) JSON formatted, but non-uniform information still including extraneous information |
| Context Prompt | 8 | (Included which fields to look for) JSON formatted with all requested fields, but with some additional ones |
| Few-shot Prompt | 10 | (Included two examples with fields needed) Exactly the correct information |
| Combination of all 3 Prompts | 10 | Same as few-shot, exactly perfect

### Lessons learned
Prompt engineering can go a long way towards getting what you need. Powerful LLMs can be very good at deciphering generic prompts, but adding more details is a better method to get exactly what you are looking for. Giving examples, while more cumbersome to write than other basic prompting, can yield very good results.
