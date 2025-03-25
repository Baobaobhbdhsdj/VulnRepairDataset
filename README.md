# VulnRepairDataset

This repository contains the datasets used in the paper:  
**"Exploring Prompt Patterns for Effective Vulnerability Repair in Real-World Code by Large Language Models"**

##  Dataset Structure

The dataset is organized based on the number of lines of code (LOC) in each C/C++ file:

- `small/` (0–40): 2749 simple and short vulnerable code cases
- `medium/` (41–80): 1286 mid-sized code cases with moderate complexity  
- `large/` (>80): 1791 large and complex vulnerable code cases

##  Usage

You can use this dataset to:

- Reproduce the experiments from our research  
- Test LLM-based code repair under varying levels of code complexity  
- Analyze how vulnerability repair performance scales with code size  

---

*This dataset is provided for academic and research purposes only.*
