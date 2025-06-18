# Imp_Concept_DSA_Solving

## Comparator fn 
```bash
        auto comp = [&](pair<int, int>& p1, pair<int, int>& p2) {
            if (p1.second == p2.second) {
                return p1.first < p2.first;  // smaller 'first' comes first if 'second' is same
            }
            return p1.second > p2.second;    // larger 'second' comes first
        };
```
