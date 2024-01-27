# CodellamaATP
Study on Codellama model for Automated Theorem Proving on Lean's dataset

This study investigates the reasoning capabilities of the Codellama model through fine-tuning on theorem proving. 
Codellama-7b is fine-tuned on Lean 4’s mathlib dataset and tested on benchmark datasets such as minif2f and proofnet along with a held out dataset. 
The results are rather modest, completing approximately 10% of the proofs in the held out test set indicating limitations in codellama when it comes to reasoning.
