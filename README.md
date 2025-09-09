# AI-generated-protein
This study aims to generate proteins with EF-hand structures using a deep learning large language model, while evaluating the performance differences of deep learning models in protein design and enhancing the success rate and functionality of designs through a multi-tool collaborative strategy. ESM3 was employed for sequence generation and structure prediction, combined with AlphaFold3 for structure validation, and DeepGO for function prediction, successfully designing artificially customized proteins. This research provides an efficient framework for customized protein design, holding significant application value in fields such as biomedicine and industrial enzyme engineering.

# Methods and Materials
This study adopts a three-phase "Generation-Validation-Optimization" research framework, integrating three deep learning tools - ESM3 for sequence generation, AlphaFold3 for structural validation, and DeepGO for functional prediction - to establish a comprehensive workflow for EF-hand protein design. The research design follows the DBTL (Design-Build-Test-Learn) cycle concept, with iterative optimization conducted through multiple rounds.

Experiment 1: ESM3-based EF-hand Protein Sequence Generation

‌Software tools:‌
• ESM3 pre-trained models (open-source version and 98B parameter version)
• PyTorch framework
‌Databases:‌
• Protein Data Bank (PDB)

<img width="501" height="386" alt="image" src="https://github.com/user-attachments/assets/079d4a13-8fd2-4efa-82fc-8f51e31e5ad2" />



 Experiment 2: AlphaFold3-based Protein Structure Validation
 
 ‌Software tools:‌
• AlphaFold3 online service (https://alphafoldserver.com/welcome)
• PyMOL 2.5 (for structure visualization and analysis)

<img width="472" height="275" alt="image" src="https://github.com/user-attachments/assets/08ae1179-bdc2-48f5-b5ae-ea6f48d93518" />


Experiment 3: DeepGO-based Protein Function Prediction

Experimental Materials
‌Software tools:‌
• DeepGO online service
‌Databases:‌
• Gene Ontology (GO) database

<img width="415" height="217" alt="image" src="https://github.com/user-attachments/assets/77a7afaa-6b76-4047-8759-7f445e617e15" />


For more research details, please refer to the paper 《Deep Learning-Based Generation of Proteins with EF-hand Structures Using ESM3》.
