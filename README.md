# Graph-Foundation-Models-Are-Already-Here

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) 

Accompanied repositories for our **ICML 2024 spotlight** paper [Position:Graph Foundation Models Are Already Here](https://arxiv.org/abs/2402.02216)

## Existing GFM papers

### Domain-specific GFMs

* (**BioRxiv '22**)[**Protein**]Language models of protein sequences at the scale of evolution enable accurate structure prediction [[Paper](https://www.biorxiv.org/content/10.1101/2022.07.20.500902v1.full.pdf)]
* (**Arxiv '24**)[**Molecule**]A foundation model for atomistic materials chemistry [[Paper](https://arxiv.org/abs/2401.00096)]
* (**ICLR '24**)[**Molecule**] From Molecules to Materials: Pre-training Large Generalizable Models for Atomic Property Prediction [[Paper](https://arxiv.org/abs/2310.16802)]
* (**Arxiv '23**)[**Molecule**]Towards Predicting Equilibrium Distributions for Molecular Systems with Deep Learning [[Paper](https://arxiv.org/abs/2306.05445)]
* (**Arxiv '23**)[**Molecule**] DPA-2: Towards a universal large atomic model for molecular and material simulation [[Paper](https://arxiv.org/abs/2312.15492)]
* (**Arxiv '24**)[**Molecule**]MatterSim: A Deep Learning Atomistic Model Across Elements, Temperatures and Pressures[[Paper](https://arxiv.org/pdf/2405.04967)]
* (**ICLR '23**)[**Molecule**]Mole-BERT: Rethinking Pre-training Graph Neural Networks for Molecules [[Paper](https://openreview.net/forum?id=jevY-DtiZTR)]
* (**Arxiv '24**)[**Molecule**]On the Scalability of GNNs for Molecular Graphs [[Paper](https://arxiv.org/pdf/2404.11568v3)]
* (**Arxiv '24**)[**Molecule**]MiniMol: A Parameter-Efficient Foundation Model for Molecular Learning [[Paper](https://arxiv.org/pdf/2404.14986)]
* (**ICML '24**)[**Molecule**] A Graph is Worth K Words: Euclideanizing Graph using Pure Transformer [[Paper](https://arxiv.org/abs/2402.02464)]



### Task-specific GFMs

* (**Arxiv '24**)[**Knowledge Graph Reasoning**] Zero-shot Logical Query Reasoning on any Knowledge Graph [[Paper](https://arxiv.org/pdf/2404.07198)]
* (**ICLR '24**)[**Knowledge Graph Reasoning**] Towards Foundation Models for Knowledge Graph Reasoning [[Paper](https://arxiv.org/abs/2310.04562)]
* (**Arxiv '24**)[**Graph Reasoning**] Let Your Graph Do the Talking: Encoding Structured Data for LLMs [[Paper](https://arxiv.org/pdf/2402.05862)]
* (**Arxiv '24**)[**Node Classification**] GraphFM: A Scalable Framework for Multi-Graph Pretraining [[Paper](https://arxiv.org/abs/2407.11907)]
* (**Arxiv '24**)[**Node Classification**] GraphAny: A Foundation Model for Node Classification on Any Graph [[Paper](https://arxiv.org/pdf/2405.20445)]
* (**Arxiv '23**)[**Node Classification**] GraphText: Graph Reasoning in Text Space [[Paper](https://arxiv.org/abs/2310.01089)]
* (**LoG '22**) [**Algorithm Reasoning**]A Generalist Neural Algorithmic Learner [[Paper](https://proceedings.mlr.press/v198/ibarz22a/ibarz22a.pdf)]



### Primitive GFMs

* (**NeurIPS '24**) GFT: Graph Foundation Model with Transferable Tree Vocabulary [[Paper](https://openreview.net/pdf?id=0MXzbAv8xy)]
* (**Arxiv '24**) GOFA: A Generative One-For-All Model for Joint Graph Language Modeling [[Paper](https://arxiv.org/pdf/2407.09709)]
* (**Arxiv '24**) Cross-Domain Graph Data Scaling: A Showcase with Diffusion Models [[Paper](https://arxiv.org/pdf/2406.01899)]
* (**ICLR '24**) One For All: Towards Training One Graph Model For All Classification Tasks [[Paper](https://openreview.net/forum?id=4IT2pgc9v6)]
* (**NeurIPS '23**) PRODIGY: Enabling In-context Learning Over Graphs [[Paper](https://arxiv.org/abs/2305.12600)]



### Scaling Law

* (**Arxiv '24**) Towards Neural Scaling Laws for Foundation Models on Temporal Graphs [[Paper](https://arxiv.org/pdf/2406.10426)]
* (**Arxiv '24**) Neural Scaling Laws on Graphs [[Paper](https://arxiv.org/abs/2402.02054)]
* (**NIPS '23**) Uncovering neural scaling laws in molecular representation learning [[Paper](https://openreview.net/forum?id=Ys8RmfF9w1)]
* (**NMI '23**) Neural scaling of deep chemical models [[Paper](https://www.nature.com/articles/s42256-023-00740-3)]


## Gathering more real-world data

We put a collection of large-scale real-world datasets below.

| Name                     	| URL                                                                      	| Description                                                                  	|
|--------------------------	|--------------------------------------------------------------------------	|------------------------------------------------------------------------------	|
| TU-Dataset               	| https://chrsmrrs.github.io/datasets/                                     	| A collection of graph-level prediction datasets                              	|
| NetworkRepository        	| https://networkrepository.com/                                           	| The largest graph datasets, with graphs coming from 30+ different domains    	|
| Open Graph Benchmark     	| https://ogb.stanford.edu/                                                	| Contains a bunch of large-scale graph datasets                               	|
| Pyg                      	| https://pytorch-geometric.readthedocs.io/en/latest/modules/datasets.html 	| Official datasets provided by Pyg, containing popular datasets for benchmark 	|
| SNAP                     	| https://snap.stanford.edu/data/                                          	| Mainly focus on social network                                               	|
| Aminer                   	| https://www.aminer.cn/data/                                              	| A collection of academic graphs                                              	|
| OAG                      	| https://www.aminer.cn/open-academic-graph                                	| A large-scale academic graph                                                 	|
| MalNet                   	| https://www.mal-net.org/#home                                            	| A large-scale function calling graph for malware detection                   	|
| ScholKG                  	| https://scholkg.kmi.open.ac.uk/                                          	| A large-scale scholarly knowledge graph                                      	|
| Graphium                 	| https://github.com/datamol-io/graphium                                   	| A massive dataset for molecular property prediction                          	|
| Live Graph Lab           	| https://livegraphlab.github.io/                                          	| A large-scale temporal graph for NFT transactions                            	|
| Temporal Graph Benchmark 	| https://docs.tgb.complexdatalab.com/                                     	| A large-scale benchmark for temporal graph learning                          	|
| MoleculeNet              	| https://moleculenet.org/                                                 	| A benchmark for molecular machine learning                                   	|
| Recsys data              	| https://cseweb.ucsd.edu/~jmcauley/datasets.html                          	| A collection of datasets for recommender systems                             	|
| LINKX                    	| https://github.com/CUAI/Non-Homophily-Large-Scale                        	| A collection of large-scale non-homophilous graphs                           	|
| GADBench                  | https://github.com/squareRoot3/GADBench                                   | A collection of datasets for graph-based anomaly detection                    |
| Text-attributed datasets                  | https://github.com/CurryTang/TSGFM                                   | A collection of text-attributed graph datasets            |
| TAGLAS                    | https://arxiv.org/abs/2406.14683                                          | A collection of text-attributed graph datasets                     |







## Theoretical backgrounds for GFM development

A curated list of papers grounding the theoretical foundations of GFMs

### General Theory


* **Geometric ML Book** Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges [[Book](https://arxiv.org/abs/2104.13478)]
* (**Arxiv '24**) Understanding Transformer Reasoning Capabilities via Graph Algorithms [[Paper](https://arxiv.org/pdf/2405.18512)]
* (**Arxiv '24**) Future Directions in Foundations of Graph Machine Learning [[Paper](https://arxiv.org/pdf/2402.02287.pdf)]
* (**ICML '23**) On Over-Squashing in Message Passing Neural Networks: The Impact of Width, Depth, and Topology [[Paper](https://arxiv.org/abs/2302.02941)]
* (**ICLR '22**) Understanding over-squashing and bottlenecks on graphs via curvature [[Paper](https://arxiv.org/abs/2111.14522)]
* (**ICLR '21**) HOW NEURAL NETWORKS EXTRAPOLATE: FROM FEEDFORWARD TO GRAPH NEURAL NETWORKS [[Paper](https://arxiv.org/pdf/2009.11848.pdf)]
* (**ICMLW '20**) A Note on Over-Smoothing for Graph Neural Networks [[Paper](https://arxiv.org/abs/2006.13318)]
* (**ICLR '20**) WHAT CAN NEURAL NETWORKS REASON ABOUT? [[Paper](https://arxiv.org/pdf/1905.13211.pdf)]
* (**ICLR '20**) The Logical Expressiveness of Graph Neural Networks  [[Paper](https://openreview.net/forum?id=r1lZ7AEKvB)]

### Node-level tasks (Node classification)

* (**Arxiv '24**) Understanding Heterophily for Graph Neural Networks [[Paper](https://arxiv.org/abs/2401.09125)]
* (**NeurIPS '23**) Demystifying Structural Disparity in Graph Neural Networks: Can One Size Fit All? [[Paper](https://arxiv.org/abs/2306.01323)]
* (**NeurIPS '23**) When Do Graph Neural Networks Help with Node Classification? Investigating the Impact of Homophily Principle on Node Distinguishability [[Paper](https://arxiv.org/abs/2304.14274)]
* (**NIPS '23**) Demystifying Oversmoothing in Attention-Based Graph Neural Networks [[Paper](https://arxiv.org/pdf/2305.16102.pdf)]
* (**ICLR '23**) Graph domain adaptation via theory-grounded spectral regularization [[Paper](https://openreview.net/forum?id=OysfLgrk8mk)]
* (**NIPS '22**) Revisiting Heterophily For Graph Neural Networks [[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/092359ce5cf60a80e882378944bf1be4-Abstract-Conference.html)]
* (**NIPS '22**) Revisiting Graph Contrastive Learning from the Perspective of Graph Spectrum [[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/13b45b44e26c353c64cba9529bf4724f-Paper-Conference.pdf)]
* (**ICLR '22**) Is Homophily a Necessity for Graph Neural Networks? [[Paper](https://arxiv.org/abs/2106.06134)]
* (**ICLR '20**) Graph Neural Networks Exponentially Lose Expressive Power for Node Classification [[Paper](https://arxiv.org/pdf/1905.10947)]
* (**Annual Review of Sociology '01**) Birds of a Feather: Homophily in Social Networks [[Paper](https://www.jstor.org/stable/2678628)]


### Link-level tasks (Link prediction)

* (**ICLR '24**) Revisiting link prediction a data perspective [[Paper](https://arxiv.org/abs/2310.00793)]
* (**NeurIPS '23**) A Theory of Link Prediction via Relational Weisfeiler-Leman on Knowledge Graphs [[Paper](https://arxiv.org/abs/2302.02209)]
* (**NIPSW '23**) A Multi-Task Perspective for Link Prediction with New Relation Types and Nodes [[Paper](https://openreview.net/forum?id=KIISfvU806)]
* (**NIPSW '23**) Double Equivariance for Inductive Link Prediction for Both New Nodes and New Relation Types [[Paper](https://arxiv.org/pdf/2302.01313.pdf)]
* (**ACL '23**) Are Message Passing Neural Networks Really Helpful for Knowledge Graph Completion? [[Paper](https://arxiv.org/abs/2205.10652)]
* (**TMLR '23**) You Only Transfer What You Share: Intersection-Induced Graph Transfer Learning for Link Prediction [[Paper](https://arxiv.org/pdf/2302.14189.pdf)]
* (**ICLR '22**) Equivariant and Stable Positional Encoding for More Powerful Graph Neural Networks [[Paper](https://arxiv.org/abs/2203.00199)]
* (**NeurIPS '21**) Labeling Trick: A Theory of Using Graph Neural Networks for Multi-Node Representation Learning [[Paper](https://arxiv.org/abs/2010.16103)]
* (**ICLR '20**) On the Equivalence between Positional Node Embeddings and Structural Graph Representations [[Paper](https://arxiv.org/pdf/1910.00452.pdf)]
* (**Scientific Reports '19**) Structural transition in social networks: The role of homophily [[Paper](https://www.nature.com/articles/s41598-019-40990-z)]
* (**ICML '19**) Position-aware Graph Neural Networks [[Paper](http://proceedings.mlr.press/v97/you19b.html)]
* (**NeurIPS '18**) Link Prediction Based on Graph Neural Networks [[Paper](https://arxiv.org/abs/1802.09691)]
* (**TKDE '15**) Triadic closure pattern analysis and prediction in social networks [[Paper](https://ieeexplore.ieee.org/abstract/document/7152900)]
* (**KDD '02**) SimRank: A Measure of Structural-Context Similarity [[Paper](http://www.cse.cuhk.edu.hk/~cslui/CMSC5734/simrank.pdf)]
* (**Social Networks '03**) Friends and neighbors on the Web [[Paper](https://www.sciencedirect.com/science/article/pii/S0378873303000091)]
* (**Psychometrika '53**) A new status index derived from sociometric analysis [[Paper](https://link.springer.com/article/10.1007/BF02289026)]



### Graph-level tasks (Graph classification)

* (**ICLR '24**) On the Stability of Expressive Positional Encodings for Graph Neural Networks [[Paper](https://openreview.net/forum?id=xAqcJ9XoTf)]
* (**ICLR '24**) Beyond weisfeiler-lehman: A quantitative framework for gnn expressiveness [[Paper](https://arxiv.org/abs/2401.08514)]
* (**NeurIPS '23**) Fine-grained Expressivity of Graph Neural Networks [[Paper](https://arxiv.org/pdf/2306.03698.pdf)]
* (**JMLR '23**) Weisfeiler and Leman go Machine Learning: The Story so far [[Paper](https://jmlr.org/papers/v24/22-0240.html)]
* (**ICML '23**) WL meet VC [[Paper](https://arxiv.org/abs/2301.11039)]
* (**ICLR '23**) Sign and Basis Invariant Networks for Spectral Graph Representation Learning [[Paper](https://openreview.net/forum?id=Q-UHqMorzil)]
* (**ICLR '23**) Rethinking the Expressive Power of GNNs via Graph Biconnectivity [[Paper](https://arxiv.org/abs/2301.09505)]
* (**NeurIPS '22**) Tree Mover’s Distance: Bridging Graph Metrics and Stability of Graph Neural Networks [[Paper](https://arxiv.org/pdf/2210.01906.pdf)]
* (**NeurIPS '21**) Rethinking Graph Transformers with Spectral Attention [[Paper](https://arxiv.org/abs/2106.03893)]
* (**Physics Reports '20**) Networks beyond pairwise interactions: structure and dynamics [[Paper](https://arxiv.org/abs/2006.01764)]
* (**Science '16**) Higher-order organization of complex networks [[Paper](https://arxiv.org/pdf/2402.02216.pdf)]
* (**JMLR '10**) Graph Kernels [[Paper](https://www.jmlr.org/papers/volume11/vishwanathan10a/vishwanathan10a.pdf)]
* (**Science '02**) Network Motifs: Simple Building Blocks of Complex Networks [[Paper](https://www.science.org/doi/10.1126/science.298.5594.824)]


### Transferring across tasks (practical techniques)

* (**Arxiv '23**) Graph Prompt Learning: A Comprehensive Survey and Beyond [[Paper](https://arxiv.org/abs/2311.16534)]
* (**NIPS '23**) Universal Prompt Tuning for Graph Neural Networks [[Paper](https://arxiv.org/abs/2209.15240)]
* (**KDD '23**) All in One: Multi-Task Prompting for Graph Neural Networks [[Paper](https://arxiv.org/abs/2307.01504)]
* (**WWW '23**) GraphPrompt: Unifying Pre-Training and Downstream Tasks for Graph Neural Networks [[Paper](https://dl.acm.org/doi/10.1145/3543507.3583386)]
* (**KDD '22**) GPPT: Graph Pre-training and Prompt Tuning to Generalize Graph Neural Networks [[Paper](https://dl.acm.org/doi/10.1145/3534678.3539249)]



## GFM development: A data perspective

### Handling feature heterogeneity

* (**ICMLW '24**) Zero-Shot Generalization of GNNs over Distinct Attribute Domains [[Paper](https://openreview.net/forum?id=W4Q4SwCjgY)]
* (**Arxiv '24**) GraphAlign: Pretraining One Graph Neural Network on Multiple Graphs via Feature Alignment [[Paper](https://arxiv.org/pdf/2406.02953)]
* (**Arxiv '24**) Text-space Graph Foundation Models: Comprehensive Benchmarks and New Insights [[Paper](https://arxiv.org/html/2406.10727v1)]
* (**ICLR '24**) One For All: Towards Training One Graph Model For All Classification Tasks [[Paper](https://openreview.net/forum?id=4IT2pgc9v6)]
* (**Arxiv '23**) GraphText: Graph Reasoning in Text Space [[Paper](https://arxiv.org/abs/2310.01089)]
* (**ICML '23**) GRAFENNE: Learning on Graphs with Heterogeneous and Dynamic Feature Sets [[Paper](https://arxiv.org/abs/2306.03447)]
* (**CVPR '23**) Deep graph reprogramming [[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Jing_Deep_Graph_Reprogramming_CVPR_2023_paper.pdf)]
* (**ICLR '23**) Confidence-Based Feature Imputation for Graphs with Partially Known Features [[Paper](https://openreview.net/forum?id=YPKBIILy-Kt)]
* (**Future Generation Computer Systems '21**) Graph convolutional networks for graphs containing missing features [[Paper](https://arxiv.org/abs/2007.04583)]


### Synthetic data generation

* (**Arxiv '24**) Cross-Domain Graph Data Scaling: A Showcase with Diffusion Models [[Paper](https://arxiv.org/pdf/2406.01899)]
* (**NIPS '23**) Data-Centric Learning from Unlabeled Graphs with Diffusion Model [[Paper](https://arxiv.org/abs/2303.10108)]
* (**ICLR '23**) Digress: Discrete denoising diffusion for graph generation [[Paper](https://openreview.net/forum?id=UaAD-Nu86WX)]
* (**ICML '22**) Score-based Generative Modeling of Graphs via the System of Stochastic Differential Equations [[Paper](https://arxiv.org/abs/2202.02514)]
* (**KDD '22**) GraphWorld: Fake Graphs Bring Real Insights for GNNs [[Paper](https://arxiv.org/pdf/2203.00112.pdf)]
* (**ICML '21**) Graphdf: A discrete flow model for molecular graph generation [[Paper](https://arxiv.org/abs/2102.01189)]
* (**ICML '20**) Hierarchical Generation of Molecular Graphs using Structural Motifs [[Paper](https://arxiv.org/abs/2002.03230)]
* (**JMLR '10**) Kronecker Graphs: An Approach to Modeling Networks [[Paper](https://cs.stanford.edu/people/jure/pubs/kronecker-jmlr10.pdf)]
* (**NIPS '08**) Mixed membership stochastic blockmodels [[Paper](https://jmlr.csail.mit.edu/papers/volume9/airoldi08a/airoldi08a.pdf)]
* (**Social Networks '07**) An introduction to exponential random graph (p*) models for social networks [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0378873306000372)]
* (**Reviews of modern physics '02**) Statistical mechanics of complex networks [[Paper](https://link.aps.org/doi/10.1103/RevModPhys.74.47)]

## GFM development: Backbone models

### Message-passing NN & Graph transformers

**A paper list of graph transformers [[Awesome graph transformers](https://github.com/wehos/awesome-graph-transformer)]**

* (**TMLR '23**) Graph Neural Networks Designed for Different Graph Types: A Survey [[Paper](https://openreview.net/forum?id=h4BYtZ79uy)]
* (**Arxiv '23**) GraphGPT: Graph Learning with Generative Pre-trained Transformers [[Paper](https://arxiv.org/abs/2401.00529)]
* (**Arxiv '23**) Attending to Graph Transformers [[Paper](https://arxiv.org/abs/2302.04181)]
* (**Arxiv '22**) GPS++: An Optimised Hybrid MPNN/Transformer for Molecular Property Prediction [[Paper](https://arxiv.org/abs/2212.02229)]

### LLM for Graph 

* (**Arxiv' 24**) Can Large Language Models Improve the Adversarial Robustness of Graph Neural Networks? [[Paper](https://arxiv.org/pdf/2408.08685)]
* (**Arxiv '24**) STARK: Benchmarking LLM Retrieval on Textual and Relational Knowledge Bases [[Paper](https://arxiv.org/abs/2404.13207)]
* (**Arxiv '24**) G-Retriever: Retrieval-Augmented Generation for Textual Graph Understanding and Question Answering [[Paper](https://arxiv.org/pdf/2402.07630)]
* (**Arxiv '24**) Let Your Graph Do the Talking: Encoding Structured Data for LLMs [[Paper](https://arxiv.org/pdf/2402.05862)]
* (**Arxiv '24**) InstructGraph: Boosting Large Language Models via Graph-centric Instruction Tuning and Preference Alignment [[Paper](https://arxiv.org/pdf/2402.08785)]
* (**ICML '24**) LLaGA: Large Language and Graph Assistant [[Paper](https://arxiv.org/pdf/2402.08170)]
* (**ICLR '24**) Talk like a Graph: Encoding Graphs for Large Language Models [[Paper](https://arxiv.org/abs/2310.04560)]
* (**WWW '24**) GraphGPT: Graph Instruction Tuning for Large Language Models [[Paper](https://arxiv.org/pdf/2310.13023)]

