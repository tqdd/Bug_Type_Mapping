# Bug Type Annotations for Figure 19

This repository provides the bug type annotations corresponding to **Figure 19** in our ASPLOS submission.  
The included table maps each bug type identifier to its description and the frequency counts across different LLMs and Infinitas.

## Example (First 10 Rows)

| Bug Type                   | Bug Tyepe ID | Llama3.1-8B | Claude3.5 | DeepSeek-v3 | GPT-4o | Infinas |
|:---------------------------|:-------|------------:|----------:|------------:|-------:|--------:|
| Logical Error              | Bug1   |          10 |         0 |           1 |      0 |       6 |
| Index Error                | Bug2   |           0 |         3 |           3 |      3 |       6 |
| Semantic Error             | Bug3   |           0 |         0 |           0 |      0 |       1 |
| Conditional Error          | Bug4   |          10 |         0 |           0 |      0 |      10 |
| Data Width Error           | Bug5   |           0 |        10 |          10 |     10 |       7 |
| Bit Range Error            | Bug6   |           0 |         0 |           0 |      0 |       4 |
| Behavioral Error           | Bug7   |           3 |         0 |           5 |      0 |       4 |
| Sensitivity and Edge Error | Bug8   |           0 |         1 |           1 |      0 |       8 |
| Incorrect Usage            | Bug9   |          10 |         0 |           0 |      0 |       6 |
| Timing Control Error       | Bug10  |           0 |         2 |           0 |     10 |       2 |

## Full Table

The complete mapping is available in bug_type_mapping.md.  
It includes all bug types and their corresponding statistics.


### Notes
- This repository is shared **anonymously** for the purpose of the ASPLOS artifact evaluation and double-blind review.  
- No identifying author or institutional information is included.  
- The dataset here serves only as supplementary material; all methodology and detailed analysis are described in the paper submission.
