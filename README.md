<!-- markdownlint-disable -->
<h1 align="center">
    <!-- ⚛️🧬❄️/💎,  🤖🧠🦾✨, ▶️⏩➡️↔️🔄🔁♻️-->
    Best of Atomistic Machine Learning ⚛️🧬💎
    <br>
</h1>

<p align="center">
    <!-- Note: For image preview, use path relative to source file, config/header.md. For production, use path relative to README.md. -->
    <!-- Either only Atom + NN, or NN + Atom, DNA, Crystal, standing for materials & molecules -->
    <!-- <img src="config/images/emoji-neural-network-like-atom_atom.svg" width="40"> -->
    <!-- <img src="config/images/emoji-neural-network-like-atom_nn-purple.svg" width="40"> -->
    <!-- <img src="./images/emoji-dna.svg" width="40"> -->
    <!-- <img src="./images/emoji-gem-stone.svg" width="40"> -->
</p>

<p align="center">
    <strong>🏆&nbsp; A ranked list of awesome atomistic machine learning (AML) projects. Updated regularly.</strong>
</p>

<p align="center">
    <a href="https://best-of.org" title="Best-of Badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-430-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/JuDFTteam/best-of-atomistic-machine-learning?color=green&label=updated"></a>
    <a href="https://doi.org/10.5281/zenodo.10430261"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.10430261.svg" alt="DOI"></a>
</p>

This curated list contains 430 awesome open-source projects with a total of 180K stars grouped into 22 categories. All projects are ranked by a [project-quality score](https://github.com/best-of-lists/best-of-generator#project-quality-score), which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/issues/new/choose), submit a [pull request](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/pulls), or directly edit the [projects.yaml](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/edit/main/projects.yaml).

The current focus of this list is more on simulation data rather than experimental data, and more on materials rather than drug design. Nevertheless, contributions from other fields are warmly welcome!

<strong>How to cite.</strong> See the button "Cite this repository" on the right side-bar.

> 🧙‍♂️  Discover other [best-of lists](https://best-of.org) or [create your own](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

## Contents

- [Active learning](#active-learning) _6 projects_
- [Community resources](#community-resources) _30 projects_
- [Datasets](#datasets) _45 projects_
- [Data Structures](#data-structures) _4 projects_
- [Density functional theory (ML-DFT)](#density-functional-theory-ml-dft) _33 projects_
- [Educational Resources](#educational-resources) _28 projects_
- [Explainable Artificial intelligence (XAI)](#explainable-artificial-intelligence-xai) _3 projects_
- [Electronic structure methods (ML-ESM)](#electronic-structure-methods-ml-esm) _5 projects_
- [General Tools](#general-tools) _22 projects_
- [Generative Models](#generative-models) _14 projects_
- [Interatomic Potentials (ML-IAP)](#interatomic-potentials-ml-iap) _70 projects_
- [Language Models](#language-models) _22 projects_
- [Materials Discovery](#materials-discovery) _12 projects_
- [Mathematical tools](#mathematical-tools) _11 projects_
- [Molecular Dynamics](#molecular-dynamics) _10 projects_
- [Reinforcement Learning](#reinforcement-learning) _2 projects_
- [Representation Engineering](#representation-engineering) _25 projects_
- [Representation Learning](#representation-learning) _58 projects_
- [Universal Potentials](#universal-potentials) _10 projects_
- [Unsupervised Learning](#unsupervised-learning) _7 projects_
- [Visualization](#visualization) _6 projects_
- [Wavefunction methods (ML-WFT)](#wavefunction-methods-ml-wft) _5 projects_
- [Others](#others) _1 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects

<br>

## Active learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on enabling active learning, iterative learning schemes for atomistic ML._

<details><summary><b><a href="https://github.com/mir-group/flare">FLARE</a></b> (🥇20 ·  ⭐ 290) - An open-source Python package for creating fast and accurate interatomic potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>C++</code> <code>ML-IAP</code></summary>

- [GitHub](https://github.com/mir-group/flare) (👨‍💻 36 · 🔀 66 · 📥 7 · 📦 11 · 📋 210 - 17% open · ⏱️ 15.08.2024):

	```
	git clone https://github.com/mir-group/flare
	```
</details>
<details><summary><b><a href="https://github.com/zincware/IPSuite">IPSuite</a></b> (🥈17 ·  ⭐ 18) - A Python toolkit for FAIR development and deployment of machine-learned interatomic potentials. <code><a href="http://bit.ly/2M0xmjV">EPL-2.0</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>workflows</code> <a href="https://en.wikipedia.org/wiki/High-throughput_computing"><code>HTC</code></a> <a href="https://www.go-fair.org/fair-principles/"><code>FAIR</code></a></summary>

- [GitHub](https://github.com/zincware/IPSuite) (👨‍💻 8 · 🔀 8 · 📦 6 · 📋 130 - 50% open · ⏱️ 20.08.2024):

	```
	git clone https://github.com/zincware/IPSuite
	```
- [PyPi](https://pypi.org/project/ipsuite) (📥 180 / month · ⏱️ 08.08.2024):
	```
	pip install ipsuite
	```
</details>
<details><summary><b><a href="https://github.com/ulissigroup/finetuna">Finetuna</a></b> (🥉10 ·  ⭐ 42) - Active Learning for Machine Learning Potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ulissigroup/finetuna) (👨‍💻 11 · 🔀 11 · 📋 20 - 25% open · ⏱️ 15.05.2024):

	```
	git clone https://github.com/ulissigroup/finetuna
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/ACEHAL">ACEHAL</a></b> (🥉5 ·  ⭐ 11 · 💤) - Hyperactive Learning (HAL) Python interface for building Atomic Cluster Expansion potentials. <code>Unlicensed</code> <code>Julia</code></summary>

- [GitHub](https://github.com/ACEsuit/ACEHAL) (👨‍💻 3 · 🔀 7 · 📋 10 - 40% open · ⏱️ 21.09.2023):

	```
	git clone https://github.com/ACEsuit/ACEHAL
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/mir-group/flare_pp">flare++</a></b> (🥈13 ·  ⭐ 35 · 💀) - A many-body extension of the FLARE code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>C++</code> <code>ML-IAP</code>
- <b><a href="https://github.com/nec-research/alebrew">ALEBREW</a></b> (🥉3 ·  ⭐ 9) - Official repository for the paper Uncertainty-biased molecular dynamics for learning uniformly accurate interatomic.. <code><a href="https://github.com/nec-research/alebrew/blob/main/LICENSE.txt">Custom</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a>
</details>
<br>

## Community resources

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that collect atomistic ML resources or foster communication within community._

🔗&nbsp;<b><a href="https://www.air4.science/map">AI for Science Map</a></b>  - Interactive mindmap of the AI4Science research field, including atomistic machine learning, including papers,..

🔗&nbsp;<b><a href="https://cortner.github.io/ACEweb/">Atomic Cluster Expansion</a></b>  - Atomic Cluster Expansion (ACE) community homepage.

🔗&nbsp;<b><a href="https://crystallm.com">CrystaLLM</a></b>  - Generate a crystal structure from a composition. <a href="https://en.wikipedia.org/wiki/Language_model"><code>language-models</code></a> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a>

🔗&nbsp;<b><a href="https://gap-ml.org/">GAP-ML.org community homepage</a></b>   <code>ML-IAP</code>

🔗&nbsp;<b><a href="https://matsci.org/">matsci.org</a></b>  - A community forum for the discussion of anything materials science, with a focus on computational materials science..

🔗&nbsp;<b><a href="https://mattermodeling.stackexchange.com/questions/tagged/machine-learning">Matter Modeling Stack Exchange - Machine Learning</a></b>  - Forum StackExchange, site Matter Modeling, ML-tagged questions.

<details><summary><b><a href="https://github.com/ml-tooling/best-of-ml-python">Best-of Machine Learning with Python</a></b> (🥇21 ·  ⭐ 16K · 📈) - A ranked list of awesome machine learning Python libraries. Updated weekly. <code><a href="https://tldrlegal.com/search?q=CC-BY-4.0">CC-BY-4.0</a></code> <code>general-ml</code> <code>Python</code></summary>

- [GitHub](https://github.com/ml-tooling/best-of-ml-python) (👨‍💻 47 · 🔀 2.3K · 📋 59 - 42% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/ml-tooling/best-of-ml-python
	```
</details>
<details><summary><b><a href="https://github.com/naganandy/graph-based-deep-learning-literature">Graph-based Deep Learning Literature</a></b> (🥇19 ·  ⭐ 4.7K) - links to conference publications in graph-based deep learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>general-ml</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/naganandy/graph-based-deep-learning-literature) (👨‍💻 12 · 🔀 770 · ⏱️ 28.08.2024):

	```
	git clone https://github.com/naganandy/graph-based-deep-learning-literature
	```
</details>
<details><summary><b><a href="https://github.com/materialsproject/matbench">MatBench</a></b> (🥇18 ·  ⭐ 110 · 💤) - Matbench: Benchmarks for materials science property prediction. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>datasets</code> <code>benchmarking</code> <code>model-repository</code></summary>

- [GitHub](https://github.com/materialsproject/matbench) (👨‍💻 25 · 🔀 44 · 📦 16 · 📋 65 - 60% open · ⏱️ 20.01.2024):

	```
	git clone https://github.com/materialsproject/matbench
	```
- [PyPi](https://pypi.org/project/matbench) (📥 470 / month · 📦 2 · ⏱️ 27.07.2022):
	```
	pip install matbench
	```
</details>
<details><summary><b><a href="https://github.com/janosh/matbench-discovery">MatBench Discovery</a></b> (🥈17 ·  ⭐ 88) - An evaluation framework for machine learning models simulating high-throughput materials discovery. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>datasets</code> <code>benchmarking</code> <code>model-repository</code></summary>

- [GitHub](https://github.com/janosh/matbench-discovery) (👨‍💻 8 · 🔀 12 · 📦 2 · 📋 36 - 8% open · ⏱️ 04.09.2024):

	```
	git clone https://github.com/janosh/matbench-discovery
	```
- [PyPi](https://pypi.org/project/matbench-discovery) (📥 660 / month · ⏱️ 15.07.2024):
	```
	pip install matbench-discovery
	```
</details>
<details><summary><b><a href="https://github.com/openml/OpenML">OpenML</a></b> (🥈16 ·  ⭐ 660 · 💤) - Open Machine Learning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>datasets</code></summary>

- [GitHub](https://github.com/openml/OpenML) (👨‍💻 35 · 🔀 90 · 📋 930 - 39% open · ⏱️ 12.01.2024):

	```
	git clone https://github.com/openml/OpenML
	```
</details>
<details><summary><b><a href="https://huggingface.co/GT4SD">GT4SD - Generative Toolkit for Scientific Discovery</a></b> (🥈16 ·  ⭐ 330) - Gradio apps of generative models in GT4SD. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a> <code>model-repository</code></summary>

- [GitHub](https://github.com/GT4SD/gt4sd-core) (👨‍💻 20 · 🔀 67 · 📋 110 - 12% open · ⏱️ 04.07.2024):

	```
	git clone https://github.com/GT4SD/gt4sd-core
	```
</details>
<details><summary><b><a href="https://github.com/divelab/AIRS/blob/main/Overview/resources.md">AI for Science Resources</a></b> (🥈13 ·  ⭐ 490) - List of resources for AI4Science research, including learning resources. <code><a href="https://tldrlegal.com/search?q=GPL-3.0%20license">GPL-3.0 license</a></code></summary>

- [GitHub](https://github.com/divelab/AIRS) (👨‍💻 29 · 🔀 58 · 📋 14 - 7% open · ⏱️ 03.09.2024):

	```
	git clone https://github.com/divelab/AIRS
	```
</details>
<details><summary><b><a href="https://github.com/Eipgen/Neural-Network-Models-for-Chemistry">Neural-Network-Models-for-Chemistry</a></b> (🥈11 ·  ⭐ 74) - A collection of Nerual Network Models for chemistry. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/Eipgen/Neural-Network-Models-for-Chemistry) (👨‍💻 3 · 🔀 9 · 📋 2 - 50% open · ⏱️ 28.08.2024):

	```
	git clone https://github.com/Eipgen/Neural-Network-Models-for-Chemistry
	```
</details>
<details><summary><b><a href="https://next-gen.materialsproject.org/materials/gnome">GNoME Explorer</a></b> (🥈9 ·  ⭐ 860) - Graph Networks for Materials Exploration Database. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>datasets</code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a></summary>

- [GitHub](https://github.com/google-deepmind/materials_discovery) (👨‍💻 2 · 🔀 130 · 📋 22 - 81% open · ⏱️ 04.09.2024):

	```
	git clone https://github.com/google-deepmind/materials_discovery
	```
</details>
<details><summary><b><a href="https://github.com/tilde-lab/awesome-materials-informatics">Awesome Materials Informatics</a></b> (🥈9 ·  ⭐ 360) - Curated list of known efforts in materials informatics, i.e. in modern materials science. <code><a href="https://github.com/tilde-lab/awesome-materials-informatics#license">Custom</a></code></summary>

- [GitHub](https://github.com/tilde-lab/awesome-materials-informatics) (👨‍💻 19 · 🔀 80 · ⏱️ 12.07.2024):

	```
	git clone https://github.com/tilde-lab/awesome-materials-informatics
	```
</details>
<details><summary><b><a href="https://molformer.res.ibm.com/">MoLFormers UI</a></b> (🥈9 ·  ⭐ 240 · 💤) - A family of foundation models trained on chemicals. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a> <a href="https://en.wikipedia.org/wiki/Language_model"><code>language-models</code></a> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a></summary>

- [GitHub](https://github.com/IBM/molformer) (👨‍💻 5 · 🔀 41 · 📋 19 - 47% open · ⏱️ 16.10.2023):

	```
	git clone https://github.com/IBM/molformer
	```
</details>
<details><summary><b><a href="https://github.com/sherrylixuecheng/AI_for_Science_paper_collection">AI for Science paper collection</a></b> (🥈9 ·  ⭐ 52 · 🐣) - List the AI for Science papers accepted by top conferences. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/sherrylixuecheng/AI_for_Science_paper_collection) (👨‍💻 5 · 🔀 6 · ⏱️ 19.08.2024):

	```
	git clone https://github.com/sherrylixuecheng/AI_for_Science_paper_collection
	```
</details>
<details><summary><b><a href="https://github.com/neurreps/awesome-neural-geometry">Awesome Neural Geometry</a></b> (🥉8 ·  ⭐ 900) - A curated collection of resources and research related to the geometry of representations in the brain, deep networks,.. <code>Unlicensed</code> <code>educational</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/neurreps/awesome-neural-geometry) (👨‍💻 11 · 🔀 57 · ⏱️ 17.07.2024):

	```
	git clone https://github.com/neurreps/awesome-neural-geometry
	```
</details>
<details><summary><b><a href="https://github.com/yuanqidu/awesome-graph-generation">Awesome-Graph-Generation</a></b> (🥉7 ·  ⭐ 260) - A curated list of up-to-date graph generation papers and resources. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/yuanqidu/awesome-graph-generation) (👨‍💻 4 · 🔀 17 · ⏱️ 17.03.2024):

	```
	git clone https://github.com/yuanqidu/awesome-graph-generation
	```
</details>
<details><summary><b><a href="https://github.com/smsharma/awesome-neural-sbi">Awesome Neural SBI</a></b> (🥉7 ·  ⭐ 84) - Community-sourced list of papers and resources on neural simulation-based inference. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a></summary>

- [GitHub](https://github.com/smsharma/awesome-neural-sbi) (👨‍💻 3 · 🔀 4 · 📋 2 - 50% open · ⏱️ 17.06.2024):

	```
	git clone https://github.com/smsharma/awesome-neural-sbi
	```
</details>
<details><summary><b><a href="https://optimade.science">optimade.science</a></b> (🥉7 ·  ⭐ 8) - A sky-scanner Optimade browser-only GUI. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>datasets</code></summary>

- [GitHub](https://github.com/tilde-lab/optimade.science) (👨‍💻 8 · 🔀 2 · 📋 26 - 26% open · ⏱️ 10.06.2024):

	```
	git clone https://github.com/tilde-lab/optimade.science
	```
</details>
<details><summary><b><a href="https://github.com/sedaoturak/data-resources-for-materials-science">The Collection of Database and Dataset Resources in Materials Science</a></b> (🥉6 ·  ⭐ 250) - A list of databases, datasets and books/handbooks where you can find materials properties for machine learning.. <code>Unlicensed</code> <code>datasets</code></summary>

- [GitHub](https://github.com/sedaoturak/data-resources-for-materials-science) (👨‍💻 2 · 🔀 41 · 📋 2 - 50% open · ⏱️ 07.06.2024):

	```
	git clone https://github.com/sedaoturak/data-resources-for-materials-science
	```
</details>
<details><summary><b><a href="https://github.com/kdmsit/Awesome-Crystal-GNNs">Awesome-Crystal-GNNs</a></b> (🥉6 ·  ⭐ 56) - This repository contains a collection of resources and papers on GNN Models on Crystal Solid State Materials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/kdmsit/Awesome-Crystal-GNNs) (👨‍💻 2 · 🔀 7 · ⏱️ 16.06.2024):

	```
	git clone https://github.com/kdmsit/Awesome-Crystal-GNNs
	```
</details>
<details><summary><b><a href="https://thismaterialdoesnotexist.com/">Does this material exist?</a></b> (🥉5 ·  ⭐ 15) - Vote on whether you think predicted crystal structures could be synthesised. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>for-fun</code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a></summary>

- [GitHub](https://github.com/ml-evs/this-material-does-not-exist) (👨‍💻 2 · 🔀 3 · ⏱️ 10.04.2024):

	```
	git clone https://github.com/ml-evs/this-material-does-not-exist
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="MADICES/MADICES.github.io/blob/main/docs/awesome_interoperability.md">MADICES Awesome Interoperability</a></b> (🥉8 ·  ⭐ 1) - Linked data interoperability resources of the Machine-actionable data interoperability for the chemical sciences.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>datasets</code>
- <b><a href="https://github.com/ncfrey/resources">A Highly Opinionated List of Open-Source Materials Informatics Resources</a></b> (🥉7 ·  ⭐ 120 · 💀) - A Highly Opinionated List of Open Source Materials Informatics Resources. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/AlexDuvalinho/geometric-gnns">Geometric-GNNs</a></b> (🥉4 ·  ⭐ 91 · 💤) - List of Geometric GNNs for 3D atomic systems. <code>Unlicensed</code> <code>datasets</code> <code>educational</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://github.com/topics/materials-informatics">GitHub topic materials-informatics</a></b> (🥉1) - GitHub topic materials-informatics. <code>Unlicensed</code>
- <b><a href="https://ma.issp.u-tokyo.ac.jp/en/">MateriApps</a></b> (🥉1) - A Portal Site of Materials Science Simulation. <code>Unlicensed</code>
</details>
<br>

## Datasets

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Datasets, databases and trained models for atomistic ML._

🔗&nbsp;<b><a href="https://alexandria.icams.rub.de/">Alexandria Materials Database</a></b>  - A database of millions of theoretical crystal structures (3D, 2D and 1D) discovered by machine learning accelerated..

🔗&nbsp;<b><a href="https://www.catalysis-hub.org/">Catalysis Hub</a></b>  - A web-platform for sharing data and software for computational catalysis research!.

🔗&nbsp;<b><a href="https://citrination.com/">Citrination Datasets</a></b>  - AI-Powered Materials Data Platform. Open Citrination has been decommissioned.

🔗&nbsp;<b><a href="https://crystals.ai/">crystals.ai</a></b>  - Curated datasets for reproducible AI in materials science.

🔗&nbsp;<b><a href="https://huggingface.co/DeepChem">DeepChem Models</a></b>  - DeepChem models on HuggingFace. <code>model-repository</code> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Language_model"><code>language-models</code></a>

🔗&nbsp;<b><a href="https://figshare.com/articles/dataset/Graphs_of_Materials_Project_20190401/8097992">Graphs of Materials Project 20190401</a></b>  - The dataset used to train the MEGNet interatomic potential. <code>ML-IAP</code>

🔗&nbsp;<b><a href="https://doi.org/10.6084/m9.figshare.19658538">HME21 Dataset</a></b>  - High-temperature multi-element 2021 dataset for the PreFerred Potential (PFP).. <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a>

🔗&nbsp;<b><a href="https://pages.nist.gov/jarvis_leaderboard/">JARVIS-Leaderboard</a></b> ( ⭐ 57)  - Explore State-of-the-Art Materials Design Methods: https://www.nature.com/articles/s41524-024-01259-w. <code>model-repository</code> <code>benchmarking</code> <code>community-resource</code> <code>educational</code>

🔗&nbsp;<b><a href="https://materialsproject.org/ml/charge_densities">Materials Project - Charge Densities</a></b>  - Materials Project has started offering charge density information available for download via their public API.

🔗&nbsp;<b><a href="https://figshare.com/articles/dataset/Materials_Project_Trjectory_MPtrj_Dataset/23713842">Materials Project Trajectory (MPtrj) Dataset</a></b>  - The dataset used to train the CHGNet universal potential. <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a>

🔗&nbsp;<b><a href="https://matterverse.ai/">matterverse.ai</a></b>  - Database of yet-to-be-sythesized materials predicted using state-of-the-art machine learning algorithms.

🔗&nbsp;<b><a href="https://figshare.com/articles/dataset/MPF_2021_2_8/19470599">MPF.2021.2.8</a></b>  - The dataset used to train the M3GNet universal potential. <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a>

🔗&nbsp;<b><a href="https://materials.nrel.gov/">NRELMatDB</a></b>  - Computational materials database with the specific focus on materials for renewable energy applications including, but..

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">Quantum-Machine.org Datasets</a></b>  - Collection of datasets, including QM7, QM9, etc. MD, DFT. Small organic molecules, mostly.

🔗&nbsp;<b><a href="http://sgdml.org/#datasets">sGDML Datasets</a></b>  - MD17, MD22, DFT datasets.

🔗&nbsp;<b><a href="https://moleculenet.org/">MoleculeNet</a></b>  - A Benchmark for Molecular Machine Learning. <code>benchmarking</code>

🔗&nbsp;<b><a href="https://zinc15.docking.org/">ZINC15</a></b>  - A free database of commercially-available compounds for virtual screening. ZINC contains over 230 million purchasable.. <code>graph</code> <a href="https://en.wikipedia.org/wiki/Biomolecule"><code>biomolecules</code></a>

🔗&nbsp;<b><a href="https://zinc.docking.org/">ZINC20</a></b>  - A free database of commercially-available compounds for virtual screening. ZINC contains over 230 million purchasable.. <code>graph</code> <a href="https://en.wikipedia.org/wiki/Biomolecule"><code>biomolecules</code></a>

<details><summary><b><a href="https://github.com/Materials-Consortia/optimade-python-tools">OPTIMADE Python tools</a></b> (🥇25 ·  ⭐ 65 · 📉) - Tools for implementing and consuming OPTIMADE APIs in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Materials-Consortia/optimade-python-tools) (👨‍💻 28 · 🔀 42 · 📋 450 - 22% open · ⏱️ 03.09.2024):

	```
	git clone https://github.com/Materials-Consortia/optimade-python-tools
	```
- [PyPi](https://pypi.org/project/optimade) (📥 7.3K / month · 📦 4 · ⏱️ 03.09.2024):
	```
	pip install optimade
	```
- [Conda](https://anaconda.org/conda-forge/optimade) (📥 88K · ⏱️ 04.09.2024):
	```
	conda install -c conda-forge optimade
	```
</details>
<details><summary><b><a href="https://github.com/materialsproject/MPContribs">MPContribs</a></b> (🥇23 ·  ⭐ 34) - Platform for materials scientists to contribute and disseminate their materials data through Materials Project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/materialsproject/MPContribs) (👨‍💻 25 · 🔀 20 · 📦 38 · 📋 99 - 21% open · ⏱️ 04.09.2024):

	```
	git clone https://github.com/materialsproject/MPContribs
	```
- [PyPi](https://pypi.org/project/mpcontribs-client) (📥 2.9K / month · 📦 3 · ⏱️ 20.06.2024):
	```
	pip install mpcontribs-client
	```
</details>
<details><summary><b><a href="https://github.com/FAIR-Chem/fairchem">FAIR Chemistry datasets</a></b> (🥇21 ·  ⭐ 760) - Datasets OC20, OC22, etc. Formerly known as Open Catalyst Project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Catalysis"><code>catalysis</code></a></summary>

- [GitHub](https://github.com/FAIR-Chem/fairchem) (👨‍💻 41 · 🔀 230 · 📋 200 - 6% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/FAIR-Chem/fairchem
	```
</details>
<details><summary><b><a href="https://github.com/Materials-Consortia/OPTIMADE">Open Databases Integration for Materials Design (OPTIMADE)</a></b> (🥈17 ·  ⭐ 77) - Specification of a common REST API for access to materials databases. <code><a href="https://tldrlegal.com/search?q=CC-BY-4.0">CC-BY-4.0</a></code></summary>

- [GitHub](https://github.com/Materials-Consortia/OPTIMADE) (👨‍💻 21 · 🔀 35 · 📋 240 - 28% open · ⏱️ 12.06.2024):

	```
	git clone https://github.com/Materials-Consortia/OPTIMADE
	```
</details>
<details><summary><b><a href="https://github.com/jla-gardner/load-atoms">load-atoms</a></b> (🥈14 ·  ⭐ 38) - download and manipulate atomistic datasets. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>data-structures</code></summary>

- [GitHub](https://github.com/jla-gardner/load-atoms) (👨‍💻 3 · 🔀 2 · 📦 3 · 📋 31 - 6% open · ⏱️ 06.04.2024):

	```
	git clone https://github.com/jla-gardner/load-atoms
	```
- [PyPi](https://pypi.org/project/load-atoms) (📥 340 / month · ⏱️ 06.04.2024):
	```
	pip install load-atoms
	```
</details>
<details><summary><b><a href="https://github.com/divelab/AIRS/tree/main/OpenDFT/QHBench/QH9">QH9</a></b> (🥈13 ·  ⭐ 490) - A Quantum Hamiltonian Prediction Benchmark. <code><a href="https://tldrlegal.com/search?q=CC-BY-NC-SA-4.0">CC-BY-NC-SA-4.0</a></code> <code>ML-DFT</code></summary>

- [GitHub](https://github.com/divelab/AIRS) (👨‍💻 29 · 🔀 58 · 📋 14 - 7% open · ⏱️ 03.09.2024):

	```
	git clone https://github.com/divelab/AIRS
	```
</details>
<details><summary><b><a href="https://github.com/openmm/spice-dataset">SPICE</a></b> (🥈11 ·  ⭐ 140) - A collection of QM data for training potential functions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a></summary>

- [GitHub](https://github.com/openmm/spice-dataset) (👨‍💻 1 · 🔀 8 · 📥 240 · 📋 62 - 25% open · ⏱️ 19.08.2024):

	```
	git clone https://github.com/openmm/spice-dataset
	```
</details>
<details><summary><b><a href="https://www.materialsdatafacility.org">Materials Data Facility (MDF)</a></b> (🥈9 ·  ⭐ 10 · 💤) - A simple way to publish, discover, and access materials datasets. Publication of very large datasets supported (e.g.,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/materials-data-facility/connect_client) (👨‍💻 7 · 🔀 1 · 📋 7 - 14% open · ⏱️ 05.02.2024):

	```
	git clone https://github.com/materials-data-facility/connect_client
	```
</details>
<details><summary><b><a href="https://github.com/HSE-LAMBDA/ai4material_design/blob/main/docs/DATA.md">2DMD dataset</a></b> (🥈9 ·  ⭐ 6 · 💤) - Code for Kazeev, N., Al-Maeeni, A.R., Romanov, I. et al. Sparse representation for machine learning the properties of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://en.wikipedia.org/wiki/Crystallographic_defect"><code>material-defect</code></a></summary>

- [GitHub](https://github.com/HSE-LAMBDA/ai4material_design) (👨‍💻 11 · 🔀 3 · ⏱️ 21.11.2023):

	```
	git clone https://github.com/HSE-LAMBDA/ai4material_design
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/AIS-Square">AIS Square</a></b> (🥉7 ·  ⭐ 10 · 💤) - A collaborative and open-source platform for sharing AI for Science datasets, models, and workflows. Home of the.. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>community-resource</code> <code>model-repository</code></summary>

- [GitHub](https://github.com/deepmodeling/AIS-Square) (👨‍💻 8 · 🔀 8 · 📋 6 - 83% open · ⏱️ 06.12.2023):

	```
	git clone https://github.com/deepmodeling/AIS-Square
	```
</details>
<details><summary><b><a href="https://github.com/Jesperkemist/perovskitedatabase">The Perovskite Database Project</a></b> (🥉5 ·  ⭐ 58) - Perovskite Database Project aims at making all perovskite device data, both past and future, available in a form.. <code>Unlicensed</code> <code>community-resource</code></summary>

- [GitHub](https://github.com/Jesperkemist/perovskitedatabase) (👨‍💻 2 · 🔀 18 · ⏱️ 07.03.2024):

	```
	git clone https://github.com/Jesperkemist/perovskitedatabase
	```
</details>
<details><summary><b><a href="https://github.com/aimat-lab/3DSC">3DSC Database</a></b> (🥉5 ·  ⭐ 15 · 💤) - Repo for the paper publishing the superconductor database with 3D crystal structures. <code><a href="https://github.com/aimat-lab/3DSC/blob/main/LICENSE.md">Custom</a></code> <a href="https://en.wikipedia.org/wiki/Superconductivity"><code>superconductors</code></a> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a></summary>

- [GitHub](https://github.com/aimat-lab/3DSC) (🔀 4 · ⏱️ 08.01.2024):

	```
	git clone https://github.com/aimat-lab/3DSC
	```
</details>
<details><summary>Show 15 hidden projects...</summary>

- <b><a href="https://github.com/drorlab/atom3d">ATOM3D</a></b> (🥈18 ·  ⭐ 300 · 💀) - ATOM3D: tasks on molecules in three dimensions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Biomolecule"><code>biomolecules</code></a> <code>benchmarking</code>
- <b><a href="https://openkim.org/">OpenKIM</a></b> (🥈10 ·  ⭐ 31 · 💀) - The Open Knowledgebase of Interatomic Models (OpenKIM) aims to be an online resource for standardized testing, long-.. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">LGPL-2.1</a></code> <code>model-repository</code> <a href="https://en.wikipedia.org/wiki/Knowledge_base"><code>knowledge-base</code></a> <code>pretrained</code>
- <b><a href="https://github.com/isayev/ANI1_dataset">ANI-1 Dataset</a></b> (🥉8 ·  ⭐ 96 · 💀) - A data set of 20 million calculated off-equilibrium conformations for organic molecules. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/deepchem/moleculenet">MoleculeNet Leaderboard</a></b> (🥉8 ·  ⭐ 88 · 💀) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code>
- <b><a href="https://github.com/learningmatter-mit/geom">GEOM</a></b> (🥉7 ·  ⭐ 190 · 💀) - GEOM: Energy-annotated molecular conformations. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a>
- <b><a href="https://github.com/aiqm/ANI1x_datasets">ANI-1x Datasets</a></b> (🥉6 ·  ⭐ 54 · 💀) - The ANI-1ccx and ANI-1x data sets, coupled-cluster and density functional theory properties for organic molecules. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/isayev/COMP6">COMP6 Benchmark dataset</a></b> (🥉6 ·  ⭐ 39 · 💀) - COMP6 Benchmark dataset for ML potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://www.optimade.org/providers-dashboard/">OPTIMADE providers dashboard</a></b> (🥉6 ·  ⭐ 1) - A dashboard of known providers. <code>Unlicensed</code>
- <b><a href="https://github.com/drcassar/SciGlass">SciGlass</a></b> (🥉5 ·  ⭐ 10 · 💀) - The database contains a vast set of data on the properties of glass materials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ORNL/Analysis-of-Large-Scale-Molecular-Datasets-with-Python">GDB-9-Ex9 and ORNL_AISD-Ex</a></b> (🥉5 ·  ⭐ 6 · 💀) - Distributed computing workflow for generation and analysis of large scale molecular datasets obtained running multi-.. <code>Unlicensed</code>
- <b><a href="https://github.com/BingqingCheng/linear-regression-benchmarks">linear-regression-benchmarks</a></b> (🥉5 ·  ⭐ 1 · 💀) - Data sets used for linear regression benchmarks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code> <code>single-paper</code>
- <b><a href="https://github.com/mathsphy/paper-data-redundancy">paper-data-redundancy</a></b> (🥉4 ·  ⭐ 8) - Repo for the paper Exploiting redundancy in large materials datasets for efficient machine learning with less data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>small-data</code> <code>single-paper</code>
- <b><a href="https://github.com/aimat-lab/visual_graph_datasets">Visual Graph Datasets</a></b> (🥉4 ·  ⭐ 2) - Datasets for the training of graph neural networks (GNNs) and subsequent visualization of attributional explanations.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Explainable_artificial_intelligence"><code>XAI</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://gitlab.com/brucefan1983/nep-data">nep-data</a></b> (🥉2 ·  ⭐ 12 · 💀) - Data related to the NEP machine-learned potential of GPUMD. <code>Unlicensed</code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <a href="https://en.wikipedia.org/wiki/Transport_phenomena"><code>transport-phenomena</code></a>
- <b><a href="https://github.com/ulissigroup/tmQM_wB97MV">tmQM_wB97MV Dataset</a></b> (🥉2 ·  ⭐ 6) - Code for Applying Large Graph Neural Networks to Predict Transition Metal Complex Energies Using the tmQM_wB97MV.. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Catalysis"><code>catalysis</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
</details>
<br>

## Data Structures

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on providing data structures used in atomistic machine learning._

<details><summary><b><a href="https://github.com/deepmodeling/dpdata">dpdata</a></b> (🥇24 ·  ⭐ 200) - A Python package for manipulating atomistic data of software in computational science. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/deepmodeling/dpdata) (👨‍💻 60 · 🔀 130 · 📦 120 · 📋 110 - 27% open · ⏱️ 03.09.2024):

	```
	git clone https://github.com/deepmodeling/dpdata
	```
- [PyPi](https://pypi.org/project/dpdata) (📥 30K / month · 📦 40 · ⏱️ 03.09.2024):
	```
	pip install dpdata
	```
- [Conda](https://anaconda.org/deepmodeling/dpdata) (📥 220 · ⏱️ 27.09.2023):
	```
	conda install -c deepmodeling dpdata
	```
</details>
<details><summary><b><a href="https://github.com/metatensor/metatensor">Metatensor</a></b> (🥈21 ·  ⭐ 49) - Self-describing sparse tensor data format for atomistic machine learning and beyond. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>Rust</code> <code>C-lang</code> <code>C++</code> <code>Python</code></summary>

- [GitHub](https://github.com/metatensor/metatensor) (👨‍💻 22 · 🔀 16 · 📥 25K · 📦 11 · 📋 210 - 35% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/lab-cosmo/metatensor
	```
</details>
<details><summary><b><a href="https://github.com/materialsproject/pyrho">mp-pyrho</a></b> (🥉16 ·  ⭐ 36 · 💤) - Tools for re-griding volumetric quantum chemistry data for machine-learning purposes. <code><a href="https://github.com/materialsproject/pyrho">Custom</a></code> <code>ML-DFT</code></summary>

- [GitHub](https://github.com/materialsproject/pyrho) (👨‍💻 8 · 🔀 6 · 📦 23 · 📋 4 - 25% open · ⏱️ 23.02.2024):

	```
	git clone https://github.com/materialsproject/pyrho
	```
- [PyPi](https://pypi.org/project/mp-pyrho) (📥 5.3K / month · 📦 3 · ⏱️ 23.02.2024):
	```
	pip install mp-pyrho
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/dlpack">dlpack</a></b> (🥉14 ·  ⭐ 890) - common in-memory tensor structure. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>C++</code></summary>

- [GitHub](https://github.com/dmlc/dlpack) (👨‍💻 23 · 🔀 130 · 📋 69 - 39% open · ⏱️ 26.03.2024):

	```
	git clone https://github.com/dmlc/dlpack
	```
</details>
<br>

## Density functional theory (ML-DFT)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects and models that focus on quantities of DFT, such as density functional approximations (ML-DFA), the charge density, density of states, the Hamiltonian, etc._

🔗&nbsp;<b><a href="https://rodare.hzdr.de/record/2720">IKS-PIML</a></b>  - Code and generated data for the paper Inverting the Kohn-Sham equations with physics-informed machine learning.. <a href="https://en.wikipedia.org/wiki/Neural_operators"><code>neural-operator</code></a> <a href="https://en.wikipedia.org/wiki/Physics-informed_neural_networks"><code>pinn</code></a> <code>datasets</code> <code>single-paper</code>

<details><summary><b><a href="https://github.com/google-research/google-research/tree/master/jax_dft">JAX-DFT</a></b> (🥇25 ·  ⭐ 34K) - This library provides basic building blocks that can construct DFT calculations as a differentiable program. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google-research/google-research) (👨‍💻 800 · 🔀 7.8K · 📋 1.8K - 81% open · ⏱️ 30.08.2024):

	```
	git clone https://github.com/google-research/google-research
	```
</details>
<details><summary><b><a href="https://github.com/mala-project/mala">MALA</a></b> (🥇18 ·  ⭐ 81) - Materials Learning Algorithms. A framework for machine learning materials properties from first-principles data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mala-project/mala) (👨‍💻 44 · 🔀 23 · 📦 1 · 📋 270 - 15% open · ⏱️ 04.07.2024):

	```
	git clone https://github.com/mala-project/mala
	```
</details>
<details><summary><b><a href="https://github.com/divelab/AIRS/tree/main/OpenDFT/QHNet">QHNet</a></b> (🥇13 ·  ⭐ 490) - Artificial Intelligence Research for Science (AIRS). <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/divelab/AIRS) (👨‍💻 29 · 🔀 58 · 📋 14 - 7% open · ⏱️ 03.09.2024):

	```
	git clone https://github.com/divelab/AIRS
	```
</details>
<details><summary><b><a href="https://github.com/andreagrisafi/SALTED">SALTED</a></b> (🥇13 ·  ⭐ 30) - Symmetry-Adapted Learning of Three-dimensional Electron Densities. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code></summary>

- [GitHub](https://github.com/andreagrisafi/SALTED) (👨‍💻 16 · 🔀 4 · 📋 6 - 16% open · ⏱️ 02.09.2024):

	```
	git clone https://github.com/andreagrisafi/SALTED
	```
</details>
<details><summary><b><a href="https://github.com/mzjb/DeepH-pack">DeepH-pack</a></b> (🥈12 ·  ⭐ 210) - Deep neural networks for density functional theory Hamiltonian. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>Julia</code></summary>

- [GitHub](https://github.com/mzjb/DeepH-pack) (👨‍💻 8 · 🔀 44 · 📋 50 - 24% open · ⏱️ 22.05.2024):

	```
	git clone https://github.com/mzjb/DeepH-pack
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/deepks-kit">DeePKS-kit</a></b> (🥈10 ·  ⭐ 96) - a package for developing machine learning-based chemically accurate energy and density functional models. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/deepmodeling/deepks-kit) (👨‍💻 7 · 🔀 35 · 📋 19 - 26% open · ⏱️ 13.04.2024):

	```
	git clone https://github.com/deepmodeling/deepks-kit
	```
</details>
<details><summary><b><a href="https://github.com/XanaduAI/GradDFT">Grad DFT</a></b> (🥈10 ·  ⭐ 72 · 💤) - GradDFT is a JAX-based library enabling the differentiable design and experimentation of exchange-correlation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/XanaduAI/GradDFT) (👨‍💻 4 · 🔀 6 · 📋 54 - 20% open · ⏱️ 13.02.2024):

	```
	git clone https://github.com/XanaduAI/GradDFT
	```
</details>
<details><summary><b><a href="https://github.com/lcmd-epfl/Q-stack">Q-stack</a></b> (🥈9 ·  ⭐ 14) - Stack of codes for dedicated pre- and post-processing tasks for Quantum Machine Learning (QML). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Excited_state"><code>excited-states</code></a> <code>general-tool</code></summary>

- [GitHub](https://github.com/lcmd-epfl/Q-stack) (👨‍💻 7 · 🔀 5 · 📋 29 - 31% open · ⏱️ 19.07.2024):

	```
	git clone https://github.com/lcmd-epfl/Q-stack
	```
</details>
<details><summary><b><a href="https://github.com/QuantumLab-ZY/HamGNN">HamGNN</a></b> (🥈8 ·  ⭐ 53) - An E(3) equivariant Graph Neural Network for predicting electronic Hamiltonian matrix. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <code>magnetism</code> <code>C-lang</code></summary>

- [GitHub](https://github.com/QuantumLab-ZY/HamGNN) (👨‍💻 1 · 🔀 12 · 📋 26 - 80% open · ⏱️ 04.09.2024):

	```
	git clone https://github.com/QuantumLab-ZY/HamGNN
	```
</details>
<details><summary><b><a href="https://github.com/AIforGreatGood/charge3net">ChargE3Net</a></b> (🥉7 ·  ⭐ 29) - Higher-order equivariant neural networks for charge density prediction in materials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/AIforGreatGood/charge3net) (👨‍💻 2 · 🔀 8 · 📋 5 - 40% open · ⏱️ 15.08.2024):

	```
	git clone https://github.com/AIforGreatGood/charge3net
	```
</details>
<details><summary><b><a href="https://github.com/ccr-cheng/InfGCN-pytorch">InfGCN for Electron Density Estimation</a></b> (🥉5 ·  ⭐ 11 · 💤) - Official implementation of the NeurIPS 23 spotlight paper of InfGCN. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Neural_operators"><code>neural-operator</code></a></summary>

- [GitHub](https://github.com/ccr-cheng/InfGCN-pytorch) (🔀 3 · ⏱️ 05.12.2023):

	```
	git clone https://github.com/ccr-cheng/infgcn-pytorch
	```
</details>
<details><summary>Show 21 hidden projects...</summary>

- <b><a href="https://github.com/google-deepmind/deepmind-research/tree/master/density_functional_approximation_dm21">DM21</a></b> (🥇20 ·  ⭐ 13K · 💀) - This package provides a PySCF interface to the DM21 (DeepMind 21) family of exchange-correlation functionals described.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/semodi/neuralxc">NeuralXC</a></b> (🥈10 ·  ⭐ 33 · 💀) - Implementation of a machine learned density functional. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/biklooost/PROPhet">PROPhet</a></b> (🥈9 ·  ⭐ 62 · 💀) - PROPhet is a code to integrate machine learning techniques with first-principles quantum chemistry approaches. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>single-paper</code> <code>C++</code>
- <b><a href="https://github.com/ACEsuit/ACEhamiltonians.jl">ACEhamiltonians</a></b> (🥈9 ·  ⭐ 12 · 💀) - Provides tools for constructing, fitting, and predicting self-consistent Hamiltonian and overlap matrices in solid-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>Julia</code>
- <b><a href="https://github.com/gomes-lab/Mat2Spec">Mat2Spec</a></b> (🥉7 ·  ⭐ 27 · 💀) - Density of States Prediction for Materials Discovery via Contrastive Learning from Probabilistic Embeddings. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Spectroscopy"><code>spectroscopy</code></a>
- <b><a href="https://github.com/semodi/libnxc">Libnxc</a></b> (🥉7 ·  ⭐ 16 · 💀) - A library for using machine-learned exchange-correlation functionals for density-functional theory. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code>C++</code> <code>Fortran</code>
- <b><a href="https://github.com/jwa7/rho_learn">rho_learn</a></b> (🥉7 ·  ⭐ 3) - A proof-of-concept framework for torch-based learning of the electron density and related scalar fields. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Xiaoxun-Gong/DeepH-E3">DeepH-E3</a></b> (🥉6 ·  ⭐ 66 · 💀) - General framework for E(3)-equivariant neural network representation of density functional theory Hamiltonian. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>magnetism</code>
- <b><a href="https://github.com/peterbjorgensen/DeepDFT">DeepDFT</a></b> (🥉6 ·  ⭐ 55 · 💀) - Official implementation of DeepDFT model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pedersor/ksr_dft">KSR-DFT</a></b> (🥉6 ·  ⭐ 4 · 💀) - Kohn-Sham regularizer for machine-learned DFT functionals. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/mzjb/xDeepH">xDeepH</a></b> (🥉5 ·  ⭐ 30 · 💀) - Extended DeepH (xDeepH) method for magnetic materials. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>magnetism</code> <code>Julia</code>
- <b><a href="https://github.com/MihailBogojeski/ml-dft">ML-DFT</a></b> (🥉5 ·  ⭐ 23 · 💀) - A package for density functional approximation using machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ulissigroup/charge-density-models">charge-density-models</a></b> (🥉4 ·  ⭐ 10 · 💤) - Tools to build charge density models using [fairchem](https://github.com/FAIR-Chem/fairchem). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://gitlab.com/jmargraf/gprep">gprep</a></b> (🥉4 · 💀) - Fitting DFTB repulsive potentials with GPR. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code>
- <b><a href="https://github.com/siddarthachar/deepcdp">DeepCDP</a></b> (🥉3 ·  ⭐ 6 · 💀) - DeepCDP: Deep learning Charge Density Prediction. <code>Unlicensed</code>
- <b><a href="https://github.com/emotionor/APET">APET</a></b> (🥉3 ·  ⭐ 4 · 💤) - Atomic Positional Embedding-based Transformer. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Density_of_states"><code>density-of-states</code></a> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a>
- <b><a href="https://github.com/foxjas/CSNN">CSNN</a></b> (🥉3 ·  ⭐ 2 · 💀) - Primary codebase of CSNN - Concentric Spherical Neural Network for 3D Representation Learning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/mala-project/malada">MALADA</a></b> (🥉3 ·  ⭐ 1 · 💀) - MALA Data Acquisition: Helpful tools to build data for MALA. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/brunocuevas/a3md">A3MD</a></b> (🥉2 ·  ⭐ 8 · 💀) - MPNN-like + Analytic Density Model = Accurate electron densities. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <code>single-paper</code>
- <b><a href="https://gitlab.com/jmargraf/kdf">kdft</a></b> (🥉1 ·  ⭐ 2 · 💀) - The Kernel Density Functional (KDF) code allows generating ML based DFT functionals. <code>Unlicensed</code>
- <b><a href="https://github.com/StefanoSanvitoGroup/MLdensity">MLDensity</a></b> ( ⭐ 2 · 💀) - Linear Jacobi-Legendre expansion of the charge density for machine learning-accelerated electronic structure.. <code>Unlicensed</code>
</details>
<br>

## Educational Resources

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Tutorials, guides, cookbooks, recipes, etc._

🔗&nbsp;<b><a href="https://ai4science101.github.io/">AI for Science 101</a></b>   <code>community-resource</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>

🔗&nbsp;<b><a href="https://sites.utu.fi/al4ms2023/media-and-tutorials/">AL4MS 2023 workshop tutorials</a></b>   <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a>

🔗&nbsp;<b><a href="https://www.elsevier.com/books-and-journals/book-companion/9780323900492">Quantum Chemistry in the Age of Machine Learning</a></b>  - Book, 2022.

<details><summary><b><a href="https://github.com/JARVIS-Materials-Design/jarvis-tools-notebooks">jarvis-tools-notebooks</a></b> (🥇12 ·  ⭐ 61) - A Google-Colab Notebook Collection for Materials Design: https://jarvis.nist.gov/. <code><a href="https://tldrlegal.com/search?q=NIST">NIST</a></code></summary>

- [GitHub](https://github.com/JARVIS-Materials-Design/jarvis-tools-notebooks) (👨‍💻 5 · 🔀 26 · ⏱️ 14.08.2024):

	```
	git clone https://github.com/JARVIS-Materials-Design/jarvis-tools-notebooks
	```
</details>
<details><summary><b><a href="https://github.com/schwallergroup/ai4chem_course">AI4Chemistry course</a></b> (🥈10 ·  ⭐ 130) - EPFL AI for chemistry course, Spring 2023. https://schwallergroup.github.io/ai4chem_course. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>chemistry</code></summary>

- [GitHub](https://github.com/schwallergroup/ai4chem_course) (👨‍💻 6 · 🔀 30 · 📋 4 - 25% open · ⏱️ 02.05.2024):

	```
	git clone https://github.com/schwallergroup/ai4chem_course
	```
</details>
<details><summary><b><a href="https://github.com/GDS-Education-Community-of-Practice/DSECOP">DSECOP</a></b> (🥈9 ·  ⭐ 43) - This repository contains data science educational materials developed by DSECOP Fellows. <code><a href="https://tldrlegal.com/search?q=CCO-1.0">CCO-1.0</a></code></summary>

- [GitHub](https://github.com/GDS-Education-Community-of-Practice/DSECOP) (👨‍💻 14 · 🔀 25 · 📋 8 - 12% open · ⏱️ 26.06.2024):

	```
	git clone https://github.com/GDS-Education-Community-of-Practice/DSECOP
	```
</details>
<details><summary><b><a href="https://github.com/Materials-Consortia/optimade-tutorial-exercises">OPTIMADE Tutorial Exercises</a></b> (🥈9 ·  ⭐ 14 · 💤) - Tutorial exercises for the OPTIMADE API. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>datasets</code></summary>

- [GitHub](https://github.com/Materials-Consortia/optimade-tutorial-exercises) (👨‍💻 6 · 🔀 7 · ⏱️ 27.09.2023):

	```
	git clone https://github.com/Materials-Consortia/optimade-tutorial-exercises
	```
</details>
<details><summary><b><a href="https://github.com/anthony-wang/BestPractices">BestPractices</a></b> (🥈8 ·  ⭐ 170 · 💤) - Things that you should (and should not) do in your Materials Informatics research. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/anthony-wang/BestPractices) (👨‍💻 3 · 🔀 69 · 📋 7 - 71% open · ⏱️ 17.11.2023):

	```
	git clone https://github.com/anthony-wang/BestPractices
	```
</details>
<details><summary><b><a href="https://github.com/ceriottm/iam-notebooks">iam-notebooks</a></b> (🥈8 ·  ⭐ 25) - Jupyter notebooks for the lectures of the Introduction to Atomistic Modeling. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ceriottm/iam-notebooks) (👨‍💻 6 · 🔀 5 · ⏱️ 26.06.2024):

	```
	git clone https://github.com/ceriottm/iam-notebooks
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/atomistic-cookbook">COSMO Software Cookbook</a></b> (🥉7 ·  ⭐ 15) - A cookbook wtih recipes for atomic-scale modeling of materials and molecules. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lab-cosmo/atomistic-cookbook) (👨‍💻 9 · 🔀 1 · 📋 12 - 16% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/lab-cosmo/software-cookbook
	```
</details>
<details><summary><b><a href="https://github.com/ilyes319/mace-tutorials">MACE-tutorials</a></b> (🥉6 ·  ⭐ 34) - Another set of tutorials for the MACE interatomic potential by one of the authors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a></summary>

- [GitHub](https://github.com/ilyes319/mace-tutorials) (👨‍💻 2 · 🔀 10 · ⏱️ 16.07.2024):

	```
	git clone https://github.com/ilyes319/mace-tutorials
	```
</details>
<details><summary>Show 17 hidden projects...</summary>

- <b><a href="https://github.com/chaitjo/geometric-gnn-dojo/blob/main/geometric_gnn_101.ipynb">Geometric GNN Dojo</a></b> (🥇12 ·  ⭐ 460 · 💀) - New to geometric GNNs: try our practical notebook, prepared for MPhil students at the University of Cambridge. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://github.com/deepchem/DeepLearningLifeSciences">DeepLearningLifeSciences</a></b> (🥇12 ·  ⭐ 350 · 💀) - Example code from the book Deep Learning for the Life Sciences. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://dmol.pub/">Deep Learning for Molecules and Materials Book</a></b> (🥈11 ·  ⭐ 610 · 💀) - Deep learning for molecules and materials book. <code><a href="https://github.com/whitead/dmol-book/blob/main/LICENSE">Custom</a></code>
- <b><a href="https://github.com/rdkit/rdkit-tutorials">RDKit Tutorials</a></b> (🥈8 ·  ⭐ 250 · 💀) - Tutorials to learn how to work with the RDKit. <code><a href="https://github.com/rdkit/rdkit-tutorials/blob/master/LICENSE">Custom</a></code>
- <b><a href="https://github.com/aimat-lab/MAChINE">MAChINE</a></b> (🥉7 ·  ⭐ 1 · 💤) - Client-Server Web App to introduce usage of ML in materials science to beginners. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/WardLT/applied-ai-for-materials">Applied AI for Materials</a></b> (🥉6 ·  ⭐ 58 · 💀) - Course materials for Applied AI for Materials Science and Engineering. <code>Unlicensed</code>
- <b><a href="https://github.com/ulissigroup/ml_catalysis_tutorials">ML for catalysis tutorials</a></b> (🥉6 ·  ⭐ 8 · 💀) - A jupyter book repo for tutorial on how to use OCP ML models for catalysis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/deepmodeling/AI4Science101">AI4Science101</a></b> (🥉5 ·  ⭐ 83 · 💀) - AI for Science. <code>Unlicensed</code>
- <b><a href="https://github.com/CompPhysVienna/MLSummerSchoolVienna2022">Machine Learning for Materials Hard and Soft</a></b> (🥉5 ·  ⭐ 34 · 💀) - ESI-DCAFM-TACO-VDSP Summer School on Machine Learning for Materials Hard and Soft. <code>Unlicensed</code>
- <b><a href="https://github.com/Teoroo-CMC/DoE_Course_Material">Data Handling, DoE and Statistical Analysis for Material Chemists</a></b> (🥉5 ·  ⭐ 1 · 💀) - Notebooks for workshops of DoE course, hosted by the Computational Materials Chemistry group at Uppsala University. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code>
- <b><a href="https://github.com/BingqingCheng/ML-in-chemistry-101">ML-in-chemistry-101</a></b> (🥉4 ·  ⭐ 68 · 💀) - The course materials for Machine Learning in Chemistry 101. <code>Unlicensed</code>
- <b><a href="https://github.com/gabor1/chemrev-gpr">chemrev-gpr</a></b> (🥉4 ·  ⭐ 6 · 💀) - Notebooks accompanying the paper on GPR in materials and molecules in Chemical Reviews 2020. <code>Unlicensed</code>
- <b><a href="https://github.com/ai4chemmat/ai4chemmat.github.io">AI4ChemMat Hands-On Series</a></b> (🥉4 ·  ⭐ 1) - Hands-On Series organized by Chemistry and Materials working group at Argonne Nat Lab. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/Teoroo-CMC/PiNN_lab">PiNN Lab</a></b> (🥉3 ·  ⭐ 2 · 💀) - Material for running a lab session on atomic neural networks. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code>
- <b><a href="https://github.com/bfocassio/MLDensity_tutorial">MLDensity_tutorial</a></b> (🥉2 ·  ⭐ 9 · 💀) - Tutorial files to work with ML for the charge density in molecules and solids. <code>Unlicensed</code>
- <b><a href="https://github.com/victorprincipe/pair_potentials">LAMMPS-style pair potentials with GAP</a></b> (🥉2 ·  ⭐ 4 · 💀) - A tutorial on how to create LAMMPS-style pair potentials and use them in combination with GAP potentials to run MD.. <code>Unlicensed</code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <a href="https://en.wikipedia.org/wiki/Feature_engineering"><code>rep-eng</code></a>
- <b><a href="https://github.com/mala-project/mala_tutorial">MALA Tutorial</a></b> (🥉2 ·  ⭐ 2 · 💤) - A full MALA hands-on tutorial. <code>Unlicensed</code>
</details>
<br>

## Explainable Artificial intelligence (XAI)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on explainability and model interpretability in atomistic ML._

<details><summary><b><a href="https://github.com/ur-whitelab/exmol">exmol</a></b> (🥇18 ·  ⭐ 280 · 💤) - Explainer for black box models that predict molecule properties. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ur-whitelab/exmol) (👨‍💻 7 · 🔀 40 · 📦 20 · 📋 69 - 15% open · ⏱️ 04.12.2023):

	```
	git clone https://github.com/ur-whitelab/exmol
	```
- [PyPi](https://pypi.org/project/exmol) (📥 750 / month · 📦 1 · ⏱️ 03.06.2022):
	```
	pip install exmol
	```
</details>
<details><summary><b><a href="https://github.com/aimat-lab/graph_attention_student">MEGAN: Multi Explanation Graph Attention Student</a></b> (🥉6 ·  ⭐ 5) - Minimal implementation of graph attention student model architecture. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/aimat-lab/graph_attention_student) (👨‍💻 2 · 🔀 1 · ⏱️ 19.08.2024):

	```
	git clone https://github.com/aimat-lab/graph_attention_student
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/CitrineInformatics-ERD-public/linear-vs-blackbox">Linear vs blackbox</a></b> (🥉3 ·  ⭐ 2 · 💀) - Code and data related to the publication: Interpretable models for extrapolation in scientific machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Explainable_artificial_intelligence"><code>XAI</code></a> <code>single-paper</code> <a href="https://en.wikipedia.org/wiki/Feature_engineering"><code>rep-eng</code></a>
</details>
<br>

## Electronic structure methods (ML-ESM)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects and models that focus on quantities of electronic structure methods, which do not fit into either of the categories ML-WFT or ML-DFT._

<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/masashitsubaki/QuantumDeepField_molecule">QDF for molecule</a></b> (🥇8 ·  ⭐ 200 · 💀) - Quantum deep field: data-driven wave function, electron density generation, and energy prediction and extrapolation.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="http://qmlearn.rutgers.edu/">QMLearn</a></b> (🥈5 ·  ⭐ 11 · 💀) - Quantum Machine Learning by learning one-body reduced density matrices in the AO basis... <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://gitlab.com/jmargraf/qpac">q-pac</a></b> (🥈5 ·  ⭐ 4 · 💀) - Kernel charge equilibration method. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Electrostatics"><code>electrostatics</code></a>
- <b><a href="https://github.com/ecignoni/halex">halex</a></b> (🥉4 ·  ⭐ 2 · 💤) - Hamiltonian Learning for Excited States https://doi.org/10.48550/arXiv.2311.00844. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Excited_state"><code>excited-states</code></a>
- <b><a href="https://github.com/muhrin/e3psi">e3psi</a></b> (🥉3 ·  ⭐ 3 · 💤) - Equivariant machine learning library for learning from electronic structures. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code>
</details>
<br>

## General Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General tools for atomistic machine learning._

<details><summary><b><a href="https://github.com/deepchem/deepchem">DeepChem</a></b> (🥇36 ·  ⭐ 5.4K) - Democratizing Deep-Learning for Drug Discovery, Quantum Chemistry, Materials Science and Biology. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/deepchem/deepchem) (👨‍💻 250 · 🔀 1.6K · 📦 420 · 📋 1.9K - 33% open · ⏱️ 23.08.2024):

	```
	git clone https://github.com/deepchem/deepchem
	```
- [PyPi](https://pypi.org/project/deepchem) (📥 36K / month · 📦 13 · ⏱️ 23.08.2024):
	```
	pip install deepchem
	```
- [Conda](https://anaconda.org/conda-forge/deepchem) (📥 110K · ⏱️ 05.04.2024):
	```
	conda install -c conda-forge deepchem
	```
- [Docker Hub](https://hub.docker.com/r/deepchemio/deepchem) (📥 7.6K · ⭐ 5 · ⏱️ 23.08.2024):
	```
	docker pull deepchemio/deepchem
	```
</details>
<details><summary><b><a href="https://github.com/rdkit/rdkit">RDKit</a></b> (🥇35 ·  ⭐ 2.6K) -  <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>C++</code></summary>

- [GitHub](https://github.com/rdkit/rdkit) (👨‍💻 230 · 🔀 860 · 📥 1.2K · 📦 3 · 📋 3.3K - 30% open · ⏱️ 03.09.2024):

	```
	git clone https://github.com/rdkit/rdkit
	```
- [PyPi](https://pypi.org/project/rdkit) (📥 820K / month · 📦 680 · ⏱️ 07.08.2024):
	```
	pip install rdkit
	```
- [Conda](https://anaconda.org/rdkit/rdkit) (📥 2.6M · ⏱️ 16.06.2023):
	```
	conda install -c rdkit rdkit
	```
</details>
<details><summary><b><a href="https://github.com/hackingmaterials/matminer">Matminer</a></b> (🥇27 ·  ⭐ 460) - Data mining for materials science. <code><a href="https://github.com/hackingmaterials/matminer/blob/main/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/hackingmaterials/matminer) (👨‍💻 54 · 🔀 190 · 📦 310 · 📋 230 - 12% open · ⏱️ 21.08.2024):

	```
	git clone https://github.com/hackingmaterials/matminer
	```
- [PyPi](https://pypi.org/project/matminer) (📥 10K / month · 📦 58 · ⏱️ 27.03.2024):
	```
	pip install matminer
	```
- [Conda](https://anaconda.org/conda-forge/matminer) (📥 69K · ⏱️ 28.03.2024):
	```
	conda install -c conda-forge matminer
	```
</details>
<details><summary><b><a href="https://github.com/libAtoms/QUIP">QUIP</a></b> (🥈26 ·  ⭐ 350) - libAtoms/QUIP molecular dynamics framework: https://libatoms.github.io. <code><a href="http://bit.ly/2KucAZR">GPL-2.0</a></code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Feature_engineering"><code>rep-eng</code></a> <code>Fortran</code></summary>

- [GitHub](https://github.com/libAtoms/QUIP) (👨‍💻 85 · 🔀 120 · 📥 540 · 📦 42 · 📋 460 - 22% open · ⏱️ 15.08.2024):

	```
	git clone https://github.com/libAtoms/QUIP
	```
- [PyPi](https://pypi.org/project/quippy-ase) (📥 3.2K / month · 📦 4 · ⏱️ 15.01.2023):
	```
	pip install quippy-ase
	```
- [Docker Hub](https://hub.docker.com/r/libatomsquip/quip) (📥 9.9K · ⭐ 4 · ⏱️ 24.04.2023):
	```
	docker pull libatomsquip/quip
	```
</details>
<details><summary><b><a href="https://github.com/materialsvirtuallab/maml">MAML</a></b> (🥈25 ·  ⭐ 360) - Python for Materials Machine Learning, Materials Descriptors, Machine Learning Force Fields, Deep Learning, etc. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/materialsvirtuallab/maml) (👨‍💻 33 · 🔀 77 · 📦 10 · 📋 71 - 12% open · ⏱️ 20.08.2024):

	```
	git clone https://github.com/materialsvirtuallab/maml
	```
- [PyPi](https://pypi.org/project/maml) (📥 280 / month · 📦 2 · ⏱️ 13.06.2024):
	```
	pip install maml
	```
</details>
<details><summary><b><a href="https://github.com/usnistgov/jarvis">JARVIS-Tools</a></b> (🥈23 ·  ⭐ 300) - JARVIS-Tools: an open-source software package for data-driven atomistic materials design. Publications:.. <code><a href="https://github.com/usnistgov/jarvis/blob/master/LICENSE.rst">Custom</a></code></summary>

- [GitHub](https://github.com/usnistgov/jarvis) (👨‍💻 15 · 🔀 120 · 📦 94 · 📋 90 - 50% open · ⏱️ 26.08.2024):

	```
	git clone https://github.com/usnistgov/jarvis
	```
- [PyPi](https://pypi.org/project/jarvis-tools) (📥 25K / month · 📦 31 · ⏱️ 26.08.2024):
	```
	pip install jarvis-tools
	```
- [Conda](https://anaconda.org/conda-forge/jarvis-tools) (📥 76K · ⏱️ 28.06.2024):
	```
	conda install -c conda-forge jarvis-tools
	```
</details>
<details><summary><b><a href="https://github.com/uw-cmg/MAST-ML">MAST-ML</a></b> (🥈19 ·  ⭐ 100) - MAterials Simulation Toolkit for Machine Learning (MAST-ML). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/uw-cmg/MAST-ML) (👨‍💻 18 · 🔀 58 · 📥 97 · 📦 43 · 📋 220 - 14% open · ⏱️ 17.04.2024):

	```
	git clone https://github.com/uw-cmg/MAST-ML
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/scikit-matter">Scikit-Matter</a></b> (🥈18 ·  ⭐ 75) - A collection of scikit-learn compatible utilities that implement methods born out of the materials science and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>scikit-learn</code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/scikit-matter) (👨‍💻 15 · 🔀 20 · 📦 10 · 📋 70 - 20% open · ⏱️ 06.08.2024):

	```
	git clone https://github.com/scikit-learn-contrib/scikit-matter
	```
- [PyPi](https://pypi.org/project/skmatter) (📥 1.3K / month · ⏱️ 24.08.2023):
	```
	pip install skmatter
	```
- [Conda](https://anaconda.org/conda-forge/skmatter) (📥 2.1K · ⏱️ 24.08.2023):
	```
	conda install -c conda-forge skmatter
	```
</details>
<details><summary><b><a href="https://github.com/yoshida-lab/XenonPy">XenonPy</a></b> (🥈16 ·  ⭐ 130) - XenonPy is a Python Software for Materials Informatics. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/yoshida-lab/XenonPy) (👨‍💻 10 · 🔀 57 · 📥 1.4K · 📋 87 - 24% open · ⏱️ 21.04.2024):

	```
	git clone https://github.com/yoshida-lab/XenonPy
	```
- [PyPi](https://pypi.org/project/xenonpy) (📥 380 / month · 📦 1 · ⏱️ 31.10.2022):
	```
	pip install xenonpy
	```
</details>
<details><summary><b><a href="https://github.com/divelab/AIRS">Artificial Intelligence for Science (AIRS)</a></b> (🥉13 ·  ⭐ 490) - Artificial Intelligence Research for Science (AIRS). <code><a href="https://tldrlegal.com/search?q=GPL-3.0%20license">GPL-3.0 license</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>ML-DFT</code> <code>ML-WFT</code> <a href="https://en.wikipedia.org/wiki/Biomolecule"><code>biomolecules</code></a></summary>

- [GitHub](https://github.com/divelab/AIRS) (👨‍💻 29 · 🔀 58 · 📋 14 - 7% open · ⏱️ 03.09.2024):

	```
	git clone https://github.com/divelab/AIRS
	```
</details>
<details><summary><b><a href="https://github.com/dralgroup/mlatom">MLatom</a></b> (🥉13 ·  ⭐ 43) - AI-enhanced computational chemistry. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>ML-DFT</code> <code>ML-ESM</code> <a href="https://en.wikipedia.org/wiki/Transfer_learning"><code>transfer-learning</code></a> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a> <a href="https://en.wikipedia.org/wiki/Spectroscopy"><code>spectroscopy</code></a> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>structure-optimization</code></a></summary>

- [GitHub](https://github.com/dralgroup/mlatom) (👨‍💻 3 · 🔀 7 · ⏱️ 22.08.2024):

	```
	git clone https://github.com/dralgroup/mlatom
	```
- [PyPi](https://pypi.org/project/mlatom) (📥 760 / month · ⏱️ 22.08.2024):
	```
	pip install mlatom
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/equisolve">Equisolve</a></b> (🥉6 ·  ⭐ 5 · 💤) - A ML toolkit package utilizing the metatensor data format to build models for the prediction of equivariant properties.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>ML-IAP</code></summary>

- [GitHub](https://github.com/lab-cosmo/equisolve) (👨‍💻 6 · 🔀 1 · 📋 23 - 82% open · ⏱️ 27.10.2023):

	```
	git clone https://github.com/lab-cosmo/equisolve
	```
</details>
<details><summary>Show 10 hidden projects...</summary>

- <b><a href="https://github.com/qmlcode/qml">QML</a></b> (🥈16 ·  ⭐ 200 · 💀) - QML: Quantum Machine Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/hackingmaterials/automatminer">Automatminer</a></b> (🥉14 ·  ⭐ 140 · 💀) - An automatic engine for predicting materials properties. <code><a href="https://github.com/hackingmaterials/automatminer/blob/main/LICENSE">Custom</a></code> <a href="https://en.wikipedia.org/wiki/Automated_machine_learning"><code>autoML</code></a>
- <b><a href="https://github.com/ulissigroup/amptorch">AMPtorch</a></b> (🥉11 ·  ⭐ 59 · 💀) - AMPtorch: Atomistic Machine Learning Package (AMP) - PyTorch. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code>
- <b><a href="https://github.com/Mariewelt/OpenChem">OpenChem</a></b> (🥉10 ·  ⭐ 670 · 💀) - OpenChem: Deep Learning toolkit for Computational Chemistry and Drug Design Research. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/deepchem/jaxchem">JAXChem</a></b> (🥉7 ·  ⭐ 77 · 💀) - JAXChem is a JAX-based deep learning library for complex and versatile chemical modeling. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ulissigroup/uncertainty_benchmarking">uncertainty_benchmarking</a></b> (🥉7 ·  ⭐ 38 · 💀) - Various code/notebooks to benchmark different ways we could estimate uncertainty in ML predictions. <code>Unlicensed</code> <code>benchmarking</code> <code>probabilistic</code>
- <b><a href="https://github.com/deepchem/torchchem">torchchem</a></b> (🥉7 ·  ⭐ 34 · 💀) - An experimental repo for experimenting with PyTorch models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ACEsuit/ACEatoms.jl">ACEatoms</a></b> (🥉4 ·  ⭐ 2 · 💀) - Generic code for modelling atomic properties using ACE. <code><a href="https://github.com/ACEsuit/ACEatoms.jl/blob/main/ASL.md">Custom</a></code> <code>Julia</code>
- <b><a href="https://bitbucket.org/wolverton/magpie/">Magpie</a></b> (🥉3) - Materials Agnostic Platform for Informatics and Exploration (Magpie). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>Java</code>
- <b><a href="https://github.com/hgheiberger/quantum-structure-ml">quantum-structure-ml</a></b> (🥉2 ·  ⭐ 2 · 💀) - Multi-class classification model for predicting the magnetic order of magnetic structures and a binary classification.. <code>Unlicensed</code> <code>magnetism</code> <code>benchmarking</code>
</details>
<br>

## Generative Models

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that implement generative models for atomistic ML._

<details><summary><b><a href="https://github.com/GT4SD/gt4sd-core">GT4SD</a></b> (🥇18 ·  ⭐ 330) - GT4SD, an open-source library to accelerate hypothesis generation in the scientific discovery process. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/GT4SD/gt4sd-core) (👨‍💻 20 · 🔀 67 · 📋 110 - 12% open · ⏱️ 04.07.2024):

	```
	git clone https://github.com/GT4SD/gt4sd-core
	```
- [PyPi](https://pypi.org/project/gt4sd) (📥 1K / month · ⏱️ 13.06.2024):
	```
	pip install gt4sd
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/molecule-generation">MoLeR</a></b> (🥇15 ·  ⭐ 260 · 💤) - Implementation of MoLeR: a generative model of molecular graphs which supports scaffold-constrained generation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/molecule-generation) (👨‍💻 5 · 🔀 41 · 📋 38 - 21% open · ⏱️ 03.01.2024):

	```
	git clone https://github.com/microsoft/molecule-generation
	```
- [PyPi](https://pypi.org/project/molecule-generation) (📥 230 / month · 📦 1 · ⏱️ 05.01.2024):
	```
	pip install molecule-generation
	```
</details>
<details><summary><b><a href="https://github.com/hspark1212/MOFTransformer">PMTransformer</a></b> (🥇15 ·  ⭐ 84) - Universal Transfer Learning in Porous Materials, including MOFs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Transfer_learning"><code>transfer-learning</code></a> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a></summary>

- [GitHub](https://github.com/hspark1212/MOFTransformer) (👨‍💻 2 · 🔀 11 · 📦 6 · 📋 37 - 2% open · ⏱️ 20.06.2024):

	```
	git clone https://github.com/hspark1212/MOFTransformer
	```
- [PyPi](https://pypi.org/project/moftransformer) (📥 410 / month · 📦 1 · ⏱️ 20.06.2024):
	```
	pip install moftransformer
	```
</details>
<details><summary><b><a href="https://github.com/atomistic-machine-learning/schnetpack-gschnet">SchNetPack G-SchNet</a></b> (🥈14 ·  ⭐ 44) - G-SchNet extension for SchNetPack. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/atomistic-machine-learning/schnetpack-gschnet) (👨‍💻 3 · 🔀 8 · ⏱️ 05.09.2024):

	```
	git clone https://github.com/atomistic-machine-learning/schnetpack-gschnet
	```
</details>
<details><summary><b><a href="https://github.com/RokasEl/simgen">SiMGen</a></b> (🥈9 ·  ⭐ 11 · 💤) - Zero Shot Molecular Generation via Similarity Kernels. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Visualization"><code>viz</code></a></summary>

- [GitHub](https://github.com/RokasEl/simgen) (👨‍💻 4 · 📦 1 · 📋 4 - 25% open · ⏱️ 15.02.2024):

	```
	git clone https://github.com/RokasEl/simgen
	```
- [PyPi](https://pypi.org/project/simgen) (📥 29 / month · ⏱️ 14.02.2024):
	```
	pip install simgen
	```
</details>
<details><summary><b><a href="https://github.com/terraytherapeutics/COATI">COATI</a></b> (🥉5 ·  ⭐ 96) - COATI: multi-modal contrastive pre-training for representing and traversing chemical space. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a> <a href="https://en.wikipedia.org/wiki/Multimodal_learning"><code>multimodal</code></a> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/terraytherapeutics/COATI) (👨‍💻 5 · 🔀 5 · 📋 3 - 33% open · ⏱️ 23.03.2024):

	```
	git clone https://github.com/terraytherapeutics/COATI
	```
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/whitead/synspace">synspace</a></b> (🥈12 ·  ⭐ 35 · 💀) - Synthesis generative model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ehoogeboom/e3_diffusion_for_molecules">EDM</a></b> (🥈9 ·  ⭐ 420 · 💀) - E(3) Equivariant Diffusion Model for Molecule Generation in 3D. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/atomistic-machine-learning/G-SchNet">G-SchNet</a></b> (🥉8 ·  ⭐ 130 · 💀) - G-SchNet - a generative model for 3d molecular structures. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tsudalab/bVAE-IM">bVAE-IM</a></b> (🥉8 ·  ⭐ 11 · 💀) - Implementation of Chemical Design with GPU-based Ising Machine. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Quantum_machine_learning"><code>QML</code></a> <code>single-paper</code>
- <b><a href="https://github.com/atomistic-machine-learning/cG-SchNet">cG-SchNet</a></b> (🥉7 ·  ⭐ 51 · 💀) - cG-SchNet - a conditional generative neural network for 3d molecular structures. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tsudalab/rxngenerator">rxngenerator</a></b> (🥉7 ·  ⭐ 11 · 💀) - A generative model for molecular generation via multi-step chemical reactions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tsudalab/MolSLEPA">MolSLEPA</a></b> (🥉5 ·  ⭐ 5 · 💀) - Interpretable Fragment-based Molecule Design with Self-learning Entropic Population Annealing. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Explainable_artificial_intelligence"><code>XAI</code></a>
- <b><a href="https://github.com/arnoldjulian/Mapping-out-phase-diagrams-with-generative-classifiers">Mapping out phase diagrams with generative classifiers</a></b> (🥉4 ·  ⭐ 7 · 💀) - Repository for our ``Mapping out phase diagrams with generative models paper. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>phase-transition</code>
</details>
<br>

## Interatomic Potentials (ML-IAP)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Machine learning interatomic potentials (aka ML-IAP, MLIAP, MLIP, MLP) and force fields (ML-FF) for molecular dynamics._

<details><summary><b><a href="https://github.com/deepmodeling/deepmd-kit">DeePMD-kit</a></b> (🥇27 ·  ⭐ 1.4K) - A deep learning package for many-body potential energy representation and molecular dynamics. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>C++</code></summary>

- [GitHub](https://github.com/deepmodeling/deepmd-kit) (👨‍💻 69 · 🔀 490 · 📥 39K · 📦 16 · 📋 760 - 11% open · ⏱️ 06.07.2024):

	```
	git clone https://github.com/deepmodeling/deepmd-kit
	```
- [PyPi](https://pypi.org/project/deepmd-kit) (📥 1.8K / month · 📦 4 · ⏱️ 27.07.2024):
	```
	pip install deepmd-kit
	```
- [Conda](https://anaconda.org/deepmodeling/deepmd-kit) (📥 1.3K · ⏱️ 06.04.2024):
	```
	conda install -c deepmodeling deepmd-kit
	```
- [Docker Hub](https://hub.docker.com/r/deepmodeling/deepmd-kit) (📥 2.7K · ⭐ 1 · ⏱️ 27.07.2024):
	```
	docker pull deepmodeling/deepmd-kit
	```
</details>
<details><summary><b><a href="https://github.com/mir-group/nequip">NequIP</a></b> (🥇24 ·  ⭐ 590) - NequIP is a code for building E(3)-equivariant interatomic potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mir-group/nequip) (👨‍💻 11 · 🔀 130 · 📦 24 · 📋 90 - 26% open · ⏱️ 09.07.2024):

	```
	git clone https://github.com/mir-group/nequip
	```
- [PyPi](https://pypi.org/project/nequip) (📥 2.1K / month · 📦 1 · ⏱️ 09.07.2024):
	```
	pip install nequip
	```
- [Conda](https://anaconda.org/conda-forge/nequip) (📥 5.7K · ⏱️ 10.07.2024):
	```
	conda install -c conda-forge nequip
	```
</details>
<details><summary><b><a href="https://github.com/aiqm/torchani">TorchANI</a></b> (🥇23 ·  ⭐ 460 · 💤) - Accurate Neural Network Potential on PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aiqm/torchani) (👨‍💻 19 · 🔀 120 · 📦 41 · 📋 170 - 14% open · ⏱️ 14.11.2023):

	```
	git clone https://github.com/aiqm/torchani
	```
- [PyPi](https://pypi.org/project/torchani) (📥 2.7K / month · 📦 4 · ⏱️ 14.11.2023):
	```
	pip install torchani
	```
- [Conda](https://anaconda.org/conda-forge/torchani) (📥 460K · ⏱️ 31.05.2024):
	```
	conda install -c conda-forge torchani
	```
</details>
<details><summary><b><a href="https://github.com/torchmd/torchmd-net">TorchMD-NET</a></b> (🥇23 ·  ⭐ 320) - Training neural network potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a> <code>pretrained</code></summary>

- [GitHub](https://github.com/torchmd/torchmd-net) (👨‍💻 16 · 🔀 70 · 📋 120 - 28% open · ⏱️ 28.08.2024):

	```
	git clone https://github.com/torchmd/torchmd-net
	```
- [Conda](https://anaconda.org/conda-forge/torchmd-net) (📥 150K · ⏱️ 20.08.2024):
	```
	conda install -c conda-forge torchmd-net
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/mace">MACE</a></b> (🥇22 ·  ⭐ 470) - MACE - Fast and accurate machine learning interatomic potentials with higher order equivariant message passing. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ACEsuit/mace) (👨‍💻 38 · 🔀 180 · 📋 260 - 27% open · ⏱️ 27.08.2024):

	```
	git clone https://github.com/ACEsuit/mace
	```
</details>
<details><summary><b><a href="https://github.com/brucefan1983/GPUMD">GPUMD</a></b> (🥇22 ·  ⭐ 440) - GPUMD is a highly efficient general-purpose molecular dynamic (MD) package and enables machine-learned potentials.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>C++</code> <a href="https://en.wikipedia.org/wiki/Electrostatics"><code>electrostatics</code></a></summary>

- [GitHub](https://github.com/brucefan1983/GPUMD) (👨‍💻 34 · 🔀 110 · 📋 180 - 12% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/brucefan1983/GPUMD
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/dpgen">DP-GEN</a></b> (🥇22 ·  ⭐ 300) - The deep potential generator to generate a deep-learning based model of interatomic potential energy and force field. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>workflows</code></summary>

- [GitHub](https://github.com/deepmodeling/dpgen) (👨‍💻 64 · 🔀 170 · 📥 1.8K · 📦 6 · 📋 300 - 11% open · ⏱️ 10.04.2024):

	```
	git clone https://github.com/deepmodeling/dpgen
	```
- [PyPi](https://pypi.org/project/dpgen) (📥 460 / month · 📦 1 · ⏱️ 10.04.2024):
	```
	pip install dpgen
	```
- [Conda](https://anaconda.org/deepmodeling/dpgen) (📥 200 · ⏱️ 16.06.2023):
	```
	conda install -c deepmodeling dpgen
	```
</details>
<details><summary><b><a href="https://github.com/FAIR-Chem/fairchem">fairchem</a></b> (🥈19 ·  ⭐ 760) - FAIR Chemistrys library of machine learning methods for chemistry. Formerly known as Open Catalyst Project (ocp). <code>Unlicensed</code> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Catalysis"><code>catalysis</code></a></summary>

- [GitHub](https://github.com/FAIR-Chem/fairchem) (👨‍💻 41 · 🔀 230 · 📋 200 - 6% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/FAIR-Chem/fairchem
	```
</details>
<details><summary><b><a href="https://github.com/apax-hub/apax">apax</a></b> (🥈18 ·  ⭐ 15) - A flexible and performant framework for training machine learning potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/apax-hub/apax) (👨‍💻 7 · 🔀 1 · 📦 2 · 📋 120 - 11% open · ⏱️ 03.09.2024):

	```
	git clone https://github.com/apax-hub/apax
	```
- [PyPi](https://pypi.org/project/apax) (📥 160 / month · ⏱️ 09.08.2024):
	```
	pip install apax
	```
</details>
<details><summary><b><a href="https://github.com/learningmatter-mit/NeuralForceField">Neural Force Field</a></b> (🥈17 ·  ⭐ 230) - Neural Network Force Field based on PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code></summary>

- [GitHub](https://github.com/learningmatter-mit/NeuralForceField) (👨‍💻 40 · 🔀 46 · 📋 19 - 5% open · ⏱️ 24.07.2024):

	```
	git clone https://github.com/learningmatter-mit/NeuralForceField
	```
</details>
<details><summary><b><a href="https://github.com/libAtoms/workflow">wfl</a></b> (🥈16 ·  ⭐ 31) - Workflow is a Python toolkit for building interatomic potential creation and atomistic simulation workflows. <code><a href="http://bit.ly/2KucAZR">GPL-2.0</a></code> <code>workflows</code> <a href="https://en.wikipedia.org/wiki/High-throughput_computing"><code>HTC</code></a></summary>

- [GitHub](https://github.com/libAtoms/workflow) (👨‍💻 19 · 🔀 18 · 📦 1 · 📋 160 - 42% open · ⏱️ 03.09.2024):

	```
	git clone https://github.com/libAtoms/workflow
	```
</details>
<details><summary><b><a href="https://github.com/uf3/uf3">Ultra-Fast Force Fields (UF3)</a></b> (🥈15 ·  ⭐ 58) - UF3: a python library for generating ultra-fast interatomic potentials. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uf3/uf3) (👨‍💻 10 · 🔀 20 · 📦 1 · 📋 49 - 38% open · ⏱️ 12.07.2024):

	```
	git clone https://github.com/uf3/uf3
	```
- [PyPi](https://pypi.org/project/uf3) (📥 36 / month · ⏱️ 27.10.2023):
	```
	pip install uf3
	```
</details>
<details><summary><b><a href="https://github.com/openkim/kliff">KLIFF</a></b> (🥈15 ·  ⭐ 34) - KIM-based Learning-Integrated Fitting Framework for interatomic potentials. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">LGPL-2.1</a></code> <code>probabilistic</code> <code>workflows</code></summary>

- [GitHub](https://github.com/openkim/kliff) (👨‍💻 9 · 🔀 20 · 📦 3 · 📋 41 - 53% open · ⏱️ 06.07.2024):

	```
	git clone https://github.com/openkim/kliff
	```
- [PyPi](https://pypi.org/project/kliff) (📥 140 / month · ⏱️ 17.12.2023):
	```
	pip install kliff
	```
- [Conda](https://anaconda.org/conda-forge/kliff) (📥 100K · ⏱️ 18.12.2023):
	```
	conda install -c conda-forge kliff
	```
</details>
<details><summary><b><a href="https://github.com/MaterSim/PyXtal_FF">PyXtalFF</a></b> (🥈14 ·  ⭐ 85 · 💤) - Machine Learning Interatomic Potential Predictions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/MaterSim/PyXtal_FF) (👨‍💻 9 · 🔀 23 · 📋 63 - 19% open · ⏱️ 07.01.2024):

	```
	git clone https://github.com/MaterSim/PyXtal_FF
	```
- [PyPi](https://pypi.org/project/pyxtal_ff) (📥 91 / month · ⏱️ 21.12.2022):
	```
	pip install pyxtal_ff
	```
</details>
<details><summary><b><a href="https://github.com/thorben-frank/mlff">So3krates (MLFF)</a></b> (🥈14 ·  ⭐ 74) - Build neural networks for machine learning force fields with JAX. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/thorben-frank/mlff) (👨‍💻 4 · 🔀 15 · 📋 9 - 33% open · ⏱️ 23.08.2024):

	```
	git clone https://github.com/thorben-frank/mlff
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/DMFF">DMFF</a></b> (🥈13 ·  ⭐ 150 · 💤) - DMFF (Differentiable Molecular Force Field) is a Jax-based python package that provides a full differentiable.. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/deepmodeling/DMFF) (👨‍💻 14 · 🔀 41 · 📋 26 - 38% open · ⏱️ 12.01.2024):

	```
	git clone https://github.com/deepmodeling/DMFF
	```
</details>
<details><summary><b><a href="https://github.com/openmm/NNPOps">NNPOps</a></b> (🥈13 ·  ⭐ 81) - High-performance operations for neural network potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>C++</code></summary>

- [GitHub](https://github.com/openmm/NNPOps) (👨‍💻 9 · 🔀 17 · 📋 55 - 38% open · ⏱️ 10.07.2024):

	```
	git clone https://github.com/openmm/NNPOps
	```
- [Conda](https://anaconda.org/conda-forge/nnpops) (📥 210K · ⏱️ 31.05.2024):
	```
	conda install -c conda-forge nnpops
	```
</details>
<details><summary><b><a href="https://github.com/isayev/ASE_ANI">ANI-1</a></b> (🥈12 ·  ⭐ 220) - ANI-1 neural net potential with python interface (ASE). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/isayev/ASE_ANI) (👨‍💻 6 · 🔀 55 · 📋 37 - 43% open · ⏱️ 11.03.2024):

	```
	git clone https://github.com/isayev/ASE_ANI
	```
</details>
<details><summary><b><a href="https://cortner.github.io/ACEweb/software/">Pacemaker</a></b> (🥈12 ·  ⭐ 66) - Python package for fitting atomic cluster expansion (ACE) potentials. <code><a href="https://github.com/ICAMS/python-ace/blob/master/LICENSE.md">Custom</a></code></summary>

- [GitHub](https://github.com/ICAMS/python-ace) (👨‍💻 6 · 🔀 15 · 📋 52 - 28% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/ICAMS/python-ace
	```
- [PyPi](https://pypi.org/project/python-ace) (📥 17 / month · ⏱️ 24.10.2022):
	```
	pip install python-ace
	```
</details>
<details><summary><b><a href="https://github.com/Teoroo-CMC/PiNN">PiNN</a></b> (🥈11 ·  ⭐ 100) - A Python library for building atomic neural networks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Teoroo-CMC/PiNN) (👨‍💻 5 · 🔀 32 · 📋 6 - 16% open · ⏱️ 27.06.2024):

	```
	git clone https://github.com/Teoroo-CMC/PiNN
	```
- [Docker Hub](https://hub.docker.com/r/teoroo/pinn) (📥 240 · ⏱️ 27.06.2024):
	```
	docker pull teoroo/pinn
	```
</details>
<details><summary><b><a href="https://github.com/TinkerTools/tinker-hp">tinker-hp</a></b> (🥈11 ·  ⭐ 78) - Tinker-HP: High-Performance Massively Parallel Evolution of Tinker on CPUs & GPUs. <code><a href="https://github.com/TinkerTools/tinker-hp/blob/master/license-Tinker.pdf">Custom</a></code></summary>

- [GitHub](https://github.com/TinkerTools/tinker-hp) (👨‍💻 12 · 🔀 22 · 📋 20 - 15% open · ⏱️ 05.08.2024):

	```
	git clone https://github.com/TinkerTools/tinker-hp
	```
</details>
<details><summary><b><a href="https://github.com/Teoroo-CMC/CCS">CCS_fit</a></b> (🥈11 ·  ⭐ 8 · 💤) - Curvature Constrained Splines. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code></summary>

- [GitHub](https://github.com/Teoroo-CMC/CCS) (👨‍💻 8 · 🔀 11 · 📥 430 · 📋 14 - 57% open · ⏱️ 16.02.2024):

	```
	git clone https://github.com/Teoroo-CMC/CCS
	```
- [PyPi](https://pypi.org/project/ccs_fit) (📥 380 / month · ⏱️ 16.02.2024):
	```
	pip install ccs_fit
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/ACEfit.jl">ACEfit</a></b> (🥈11 ·  ⭐ 7) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>Julia</code></summary>

- [GitHub](https://github.com/ACEsuit/ACEfit.jl) (👨‍💻 8 · 🔀 6 · 📋 56 - 41% open · ⏱️ 29.08.2024):

	```
	git clone https://github.com/ACEsuit/ACEfit.jl
	```
</details>
<details><summary><b><a href="https://calorine.materialsmodeling.org/">calorine</a></b> (🥉10 ·  ⭐ 12) - A Python package for constructing and sampling neuroevolution potential models. https://doi.org/10.21105/joss.06264. <code><a href="https://gitlab.com/materials-modeling/calorine/-/blob/master/LICENSE">Custom</a></code></summary>

- [PyPi](https://pypi.org/project/calorine) (📥 850 / month · 📦 2 · ⏱️ 26.07.2024):
	```
	pip install calorine
	```
- [GitLab](https://gitlab.com/materials-modeling/calorine) (🔀 4 · 📋 85 - 9% open · ⏱️ 26.07.2024):

	```
	git clone https://gitlab.com/materials-modeling/calorine
	```
</details>
<details><summary><b><a href="https://github.com/gasteigerjo/dimenet">DimeNet</a></b> (🥉9 ·  ⭐ 280 · 💤) - DimeNet and DimeNet++ models, as proposed in Directional Message Passing for Molecular Graphs (ICLR 2020) and Fast and.. <code><a href="https://github.com/gasteigerjo/dimenet/blob/master/LICENSE.md">Custom</a></code></summary>

- [GitHub](https://github.com/gasteigerjo/dimenet) (👨‍💻 2 · 🔀 59 · 📦 1 · 📋 31 - 3% open · ⏱️ 03.10.2023):

	```
	git clone https://github.com/gasteigerjo/dimenet
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/ACE.jl">ACE.jl</a></b> (🥉9 ·  ⭐ 65) - Parameterisation of Equivariant Properties of Particle Systems. <code><a href="https://github.com/ACEsuit/ACE.jl/blob/main/license/mit.md">Custom</a></code> <code>Julia</code></summary>

- [GitHub](https://github.com/ACEsuit/ACE.jl) (👨‍💻 12 · 🔀 15 · 📋 82 - 29% open · ⏱️ 31.08.2024):

	```
	git clone https://github.com/ACEsuit/ACE.jl
	```
</details>
<details><summary><b><a href="https://libatoms.github.io/">GAP</a></b> (🥉9 ·  ⭐ 40) - Gaussian Approximation Potential (GAP). <code><a href="https://github.com/libAtoms/GAP/blob/main/LICENSE.md">Custom</a></code></summary>

- [GitHub](https://github.com/libAtoms/GAP) (👨‍💻 13 · 🔀 20 · ⏱️ 17.08.2024):

	```
	git clone https://github.com/libAtoms/GAP
	```
</details>
<details><summary><b><a href="https://github.com/spozdn/pet">Point Edge Transformer (PET)</a></b> (🥉9 ·  ⭐ 18) - Point Edge Transformer. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a></summary>

- [GitHub](https://github.com/spozdn/pet) (👨‍💻 7 · 🔀 5 · ⏱️ 02.07.2024):

	```
	git clone https://github.com/spozdn/pet
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/mace-jax">MACE-Jax</a></b> (🥉8 ·  ⭐ 59 · 💤) - Equivariant machine learning interatomic potentials in JAX. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ACEsuit/mace-jax) (👨‍💻 2 · 🔀 5 · 📋 6 - 50% open · ⏱️ 04.10.2023):

	```
	git clone https://github.com/ACEsuit/mace-jax
	```
</details>
<details><summary><b><a href="https://github.com/MDIL-SNU/SIMPLE-NN_v2">SIMPLE-NN v2</a></b> (🥉8 ·  ⭐ 40 · 💤) - SIMPLE-NN is an open package that constructs Behler-Parrinello-type neural-network interatomic potentials from ab.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code></summary>

- [GitHub](https://github.com/MDIL-SNU/SIMPLE-NN_v2) (👨‍💻 13 · 🔀 17 · 📋 13 - 30% open · ⏱️ 29.12.2023):

	```
	git clone https://github.com/MDIL-SNU/SIMPLE-NN_v2
	```
</details>
<details><summary><b><a href="https://github.com/lanl/ALF">ALF</a></b> (🥉8 ·  ⭐ 29) - A framework for performing active learning for training machine-learned interatomic potentials. <code><a href="https://github.com/lanl/ALF/blob/main/LICENSE">Custom</a></code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a></summary>

- [GitHub](https://github.com/lanl/ALF) (👨‍💻 5 · 🔀 12 · ⏱️ 08.08.2024):

	```
	git clone https://github.com/lanl/alf
	```
</details>
<details><summary><b><a href="https://acesuit.github.io/">ACE1.jl</a></b> (🥉8 ·  ⭐ 20) - Atomic Cluster Expansion for Modelling Invariant Atomic Properties. <code><a href="https://github.com/ACEsuit/ACE1.jl/blob/main/ASL.md">Custom</a></code> <code>Julia</code></summary>

- [GitHub](https://github.com/ACEsuit/ACE1.jl) (👨‍💻 9 · 🔀 7 · 📋 46 - 47% open · ⏱️ 02.07.2024):

	```
	git clone https://github.com/ACEsuit/ACE1.jl
	```
</details>
<details><summary><b><a href="https://github.com/mcaroba/turbogap">TurboGAP</a></b> (🥉8 ·  ⭐ 16) - The TurboGAP code. <code><a href="https://github.com/mcaroba/turbogap/blob/master/LICENSE.md">Custom</a></code> <code>Fortran</code></summary>

- [GitHub](https://github.com/mcaroba/turbogap) (👨‍💻 8 · 🔀 8 · 📋 9 - 66% open · ⏱️ 09.07.2024):

	```
	git clone https://github.com/mcaroba/turbogap
	```
</details>
<details><summary><b><a href="https://github.com/RowleyGroup/MLXDM">MLXDM</a></b> (🥉8 ·  ⭐ 6) - A Neural Network Potential with Rigorous Treatment of Long-Range Dispersion https://doi.org/10.1039/D2DD00150K. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>long-range</code></summary>

- [GitHub](https://github.com/RowleyGroup/MLXDM) (👨‍💻 7 · 🔀 2 · ⏱️ 15.08.2024):

	```
	git clone https://github.com/RowleyGroup/MLXDM
	```
</details>
<details><summary><b><a href="https://github.com/bigd4/PyNEP">PyNEP</a></b> (🥉7 ·  ⭐ 46) - A python interface of the machine learning potential NEP used in GPUMD. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bigd4/PyNEP) (👨‍💻 7 · 🔀 16 · 📋 11 - 36% open · ⏱️ 01.06.2024):

	```
	git clone https://github.com/bigd4/PyNEP
	```
</details>
<details><summary><b><a href="https://cortner.github.io/ACEweb/software/">TensorPotential</a></b> (🥉6 ·  ⭐ 8 · 📈) - Tensorpotential is a TensorFlow based tool for development, fitting ML interatomic potentials from electronic.. <code><a href="https://github.com/ICAMS/TensorPotential/blob/main/LICENSE.md">Custom</a></code></summary>

- [GitHub](https://github.com/ICAMS/TensorPotential) (👨‍💻 4 · 🔀 4 · ⏱️ 06.09.2024):

	```
	git clone https://github.com/ICAMS/TensorPotential
	```
</details>
<details><summary><b><a href="https://github.com/mariogeiger/nequip-jax">NequIP-JAX</a></b> (🥉5 ·  ⭐ 17 · 💤) - JAX implementation of the NequIP interatomic potential. <code>Unlicensed</code></summary>

- [GitHub](https://github.com/mariogeiger/nequip-jax) (👨‍💻 2 · 🔀 3 · ⏱️ 01.11.2023):

	```
	git clone https://github.com/mariogeiger/nequip-jax
	```
</details>
<details><summary><b><a href="https://github.com/mariogeiger/allegro-jax">Allegro-JAX</a></b> ( ⭐ 17) - JAX implementation of the Allegro interatomic potential. <code>Unlicensed</code></summary>

- [GitHub](https://github.com/mariogeiger/allegro-jax) (👨‍💻 2 · 🔀 2 · 📋 2 - 50% open · ⏱️ 09.04.2024):

	```
	git clone https://github.com/mariogeiger/allegro-jax
	```
</details>
<details><summary>Show 32 hidden projects...</summary>

- <b><a href="https://github.com/materialsvirtuallab/megnet">MEGNet</a></b> (🥇22 ·  ⭐ 500 · 💀) - Graph Networks as a Universal Machine Learning Framework for Molecules and Crystals. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <a href="https://en.wikipedia.org/wiki/Multifidelity_simulation"><code>multifidelity</code></a>
- <b><a href="https://github.com/stefanch/sGDML">sGDML</a></b> (🥈16 ·  ⭐ 140 · 💀) - sGDML - Reference implementation of the Symmetric Gradient Domain Machine Learning model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/CompPhysVienna/n2p2">n2p2</a></b> (🥈13 ·  ⭐ 220 · 💀) - n2p2 - A Neural Network Potential Package. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>C++</code>
- <b><a href="https://github.com/jparkhill/TensorMol">TensorMol</a></b> (🥈12 ·  ⭐ 270 · 💀) - Tensorflow + Molecules = TensorMol. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>single-paper</code>
- <b><a href="https://github.com/MDIL-SNU/SIMPLE-NN">SIMPLE-NN</a></b> (🥈11 ·  ⭐ 47 · 💀) - SIMPLE-NN(SNU Interatomic Machine-learning PotentiaL packagE version Neural Network). <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code>
- <b><a href="https://github.com/mir-group/allegro">Allegro</a></b> (🥉10 ·  ⭐ 320 · 💀) - Allegro is an open-source code for building highly scalable and accurate equivariant deep learning interatomic.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/aimat-lab/NNsForMD">NNsforMD</a></b> (🥉10 ·  ⭐ 10 · 💀) - Neural network class for molecular dynamics to predict potential energy, forces and non-adiabatic couplings. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/atomistic-machine-learning/SchNet">SchNet</a></b> (🥉9 ·  ⭐ 210 · 💀) - SchNet - a deep learning architecture for quantum chemistry. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/TUM-DAML/gemnet_pytorch">GemNet</a></b> (🥉9 ·  ⭐ 180 · 💀) - GemNet model in PyTorch, as proposed in GemNet: Universal Directional Graph Neural Networks for Molecules (NeurIPS.. <code><a href="https://github.com/TUM-DAML/gemnet_pytorch/blob/master/LICENSE">Custom</a></code>
- <b><a href="https://github.com/aiqm/aimnet">AIMNet</a></b> (🥉8 ·  ⭐ 94 · 💀) - Atoms In Molecules Neural Network Potential. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code>
- <b><a href="https://github.com/materialsvirtuallab/snap">SNAP</a></b> (🥉8 ·  ⭐ 36 · 💀) - Repository for spectral neighbor analysis potential (SNAP) model development. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/learningmatter-mit/Atomistic-Adversarial-Attacks">Atomistic Adversarial Attacks</a></b> (🥉8 ·  ⭐ 30 · 💀) - Code for performing adversarial attacks on atomistic systems using NN potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>probabilistic</code>
- <b><a href="https://github.com/HSE-LAMBDA/MEGNetSparse">MEGNetSparse</a></b> (🥉8 ·  ⭐ 1 · 💀) - A library imlementing a graph neural network with sparse representation from Code for Kazeev, N., Al-Maeeni, A.R.,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Crystallographic_defect"><code>material-defect</code></a>
- <b><a href="https://github.com/MMunibas/PhysNet">PhysNet</a></b> (🥉7 ·  ⭐ 88 · 💀) - Code for training PhysNet models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Electrostatics"><code>electrostatics</code></a>
- <b><a href="https://gitlab.com/ashapeev/mlip-3">MLIP-3</a></b> (🥉6 ·  ⭐ 26 · 💀) - MLIP-3: Active learning on atomic environments with Moment Tensor Potentials (MTP). <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code>C++</code>
- <b><a href="https://github.com/libAtoms/testing-framework">testing-framework</a></b> (🥉6 ·  ⭐ 11 · 💀) - The purpose of this repository is to aid the testing of a large number of interatomic potentials for a variety of.. <code>Unlicensed</code> <code>benchmarking</code>
- <b><a href="https://gitlab.com/PANNAdevs/panna">PANNA</a></b> (🥉6 ·  ⭐ 9 · 💀) - A package to train and validate all-to-all connected network models for BP[1] and modified-BP[2] type local atomic.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code>
- <b><a href="https://gitlab.com/zaverkin_v/gmnn">GN-MM</a></b> (🥉5 ·  ⭐ 10 · 💀) - The Gaussian Moment Neural Network (GM-NN) package developed for large-scale atomistic simulations employing atomistic.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <a href="https://en.wikipedia.org/wiki/Feature_engineering"><code>rep-eng</code></a> <code>magnetism</code>
- <b><a href="https://github.com/Luthaf/alchemical-learning">Alchemical learning</a></b> (🥉5 ·  ⭐ 2 · 💀) - Code for the Modeling high-entropy transition metal alloys with alchemical compression article. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ACEsuit/ACE1pack.jl">ACE1Pack.jl</a></b> (🥉5 ·  ⭐ 1 · 💀) - Provides convenience functionality for the usage of ACE1.jl, ACEfit.jl, JuLIP.jl for fitting interatomic potentials.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>Julia</code>
- <b><a href="https://github.com/ibayashi-hikaru/allegro-legato">Allegro-Legato</a></b> (🥉4 ·  ⭐ 19 · 💀) - An extension of Allegro with enhanced robustness and time-to-failure. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a>
- <b><a href="https://github.com/sirmarcel/glp">glp</a></b> (🥉4 ·  ⭐ 17) - tools for graph-based machine-learning potentials in jax. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ACEsuit/ACEworkflows">ACE Workflows</a></b> (🥉4 · 💤) - Workflow Examples for ACE Models. <code>Unlicensed</code> <code>Julia</code> <code>workflows</code>
- <b><a href="https://github.com/AaltoRSE/PeriodicPotentials">PeriodicPotentials</a></b> (🥉4 · 💀) - A Periodic table app that displays potentials based on the selected elements. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>community-resource</code> <a href="https://en.wikipedia.org/wiki/Visualization"><code>viz</code></a> <code>JavaScript</code>
- <b><a href="https://github.com/MMunibas/Asparagus">Asparagus</a></b> (🥉3 ·  ⭐ 4 · 🐣) - Program Package for Sampling, Training and Applying ML-based Potential models https://doi.org/10.48550/arXiv.2407.15175. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>workflows</code> <code>sampling</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a>
- <b><a href="https://gitlab.com/flame-code/PyFLAME">PyFLAME</a></b> (🥉3 · 💀) - An automated approach for developing neural network interatomic potentials with FLAME.. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a> <code>structure-prediction</code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>structure-optimization</code></a> <a href="https://en.wikipedia.org/wiki/Feature_engineering"><code>rep-eng</code></a> <code>Fortran</code>
- <b><a href="https://github.com/lmj1029123/SingleNN">SingleNN</a></b> (🥉2 ·  ⭐ 8 · 💀) - An efficient package for training and executing neural-network interatomic potentials. <code>Unlicensed</code> <code>C++</code>
- <b><a href="https://github.com/loilisxka/AisNet">AisNet</a></b> (🥉2 ·  ⭐ 3 · 💀) - A Universal Interatomic Potential Neural Network with Encoded Local Environment Features.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://www.uni-goettingen.de/de/560580.html">RuNNer</a></b> (🥉2) - The RuNNer Neural Network Energy Representation is a Fortran-based framework for the construction of Behler-.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>Fortran</code>
- <b><a href="https://github.com/jla-gardner/nnp-pre-training">nnp-pre-training</a></b> (🥉1 ·  ⭐ 6 · 💤) - Synthetic pre-training for neural-network interatomic potentials. <code>Unlicensed</code> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a>
- <b><a href="https://github.com/mttrin93/mag-ace">mag-ace</a></b> (🥉1 ·  ⭐ 2 · 💤) - Magnetic ACE potential. FORTRAN interface for LAMMPS SPIN package. <code>Unlicensed</code> <code>magnetism</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>Fortran</code>
- <b><a href="https://github.com/cesmix-mit/MLP">mlp</a></b> (🥉1 ·  ⭐ 1 · 💀) - Proper orthogonal descriptors for efficient and accurate interatomic potentials... <code>Unlicensed</code> <code>Julia</code>
</details>
<br>

## Language Models

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that use (large) language models (LMs, LLMs) or natural language procesing (NLP) techniques for atomistic ML._

<details><summary><b><a href="https://github.com/Future-House/paper-qa">paper-qa</a></b> (🥇26 ·  ⭐ 3.9K) - LLM Chain for answering questions from documents with citations. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://en.wikipedia.org/wiki/Large_language_model#Agency"><code>ai-agent</code></a></summary>

- [GitHub](https://github.com/Future-House/paper-qa) (👨‍💻 18 · 🔀 370 · 📦 68 · 📋 140 - 47% open · ⏱️ 14.08.2024):

	```
	git clone https://github.com/whitead/paper-qa
	```
- [PyPi](https://pypi.org/project/paper-qa) (📥 8K / month · 📦 8 · ⏱️ 29.08.2024):
	```
	pip install paper-qa
	```
</details>
<details><summary><b><a href="https://github.com/OpenBioML/chemnlp">OpenBioML ChemNLP</a></b> (🥇17 ·  ⭐ 150) - ChemNLP project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>datasets</code></summary>

- [GitHub](https://github.com/OpenBioML/chemnlp) (👨‍💻 27 · 🔀 45 · 📋 250 - 44% open · ⏱️ 19.08.2024):

	```
	git clone https://github.com/OpenBioML/chemnlp
	```
- [PyPi](https://pypi.org/project/chemnlp) (📥 76 / month · 📦 1 · ⏱️ 07.08.2023):
	```
	pip install chemnlp
	```
</details>
<details><summary><b><a href="https://github.com/ur-whitelab/chemcrow-public">ChemCrow</a></b> (🥈15 ·  ⭐ 580) - Open source package for the accurate solution of reasoning-intensive chemical tasks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Large_language_model#Agency"><code>ai-agent</code></a></summary>

- [GitHub](https://github.com/ur-whitelab/chemcrow-public) (👨‍💻 3 · 🔀 82 · 📦 5 · 📋 20 - 30% open · ⏱️ 27.03.2024):

	```
	git clone https://github.com/ur-whitelab/chemcrow-public
	```
- [PyPi](https://pypi.org/project/chemcrow) (📥 370 / month · ⏱️ 27.03.2024):
	```
	pip install chemcrow
	```
</details>
<details><summary><b><a href="https://github.com/kjappelbaum/gptchem">gptchem</a></b> (🥈12 ·  ⭐ 220 · 💤) - Use GPT-3 to solve chemistry problems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/kjappelbaum/gptchem) (👨‍💻 4 · 🔀 39 · 📋 21 - 90% open · ⏱️ 04.10.2023):

	```
	git clone https://github.com/kjappelbaum/gptchem
	```
- [PyPi](https://pypi.org/project/gptchem) (📥 49 / month · ⏱️ 04.10.2023):
	```
	pip install gptchem
	```
</details>
<details><summary><b><a href="https://github.com/Yeonghun1675/ChatMOF">ChatMOF</a></b> (🥈12 ·  ⭐ 54) - Predict and Inverse design for metal-organic framework with large-language models (llms). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a></summary>

- [GitHub](https://github.com/Yeonghun1675/ChatMOF) (👨‍💻 1 · 🔀 8 · 📦 2 · ⏱️ 01.07.2024):

	```
	git clone https://github.com/Yeonghun1675/ChatMOF
	```
- [PyPi](https://pypi.org/project/chatmof) (📥 280 / month · ⏱️ 01.07.2024):
	```
	pip install chatmof
	```
</details>
<details><summary><b><a href="https://github.com/usnistgov/atomgpt">AtomGPT</a></b> (🥈12 ·  ⭐ 22) - AtomGPT: Atomistic Generative Pretrained Transformer for Forward and Inverse Materials Design. <code><a href="https://github.com/usnistgov/atomgpt/blob/main/LICENSE.rst">Custom</a></code> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a></summary>

- [GitHub](https://github.com/usnistgov/atomgpt) (👨‍💻 2 · 🔀 3 · 📦 1 · ⏱️ 09.08.2024):

	```
	git clone https://github.com/usnistgov/atomgpt
	```
- [PyPi](https://pypi.org/project/atomgpt) (📥 220 / month · ⏱️ 09.08.2024):
	```
	pip install atomgpt
	```
</details>
<details><summary><b><a href="https://github.com/usnistgov/chemnlp">NIST ChemNLP</a></b> (🥈11 ·  ⭐ 68) - ChemNLP: A Natural Language Processing based Library for Materials Chemistry Text Data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>literature-data</code></summary>

- [GitHub](https://github.com/usnistgov/chemnlp) (👨‍💻 2 · 🔀 16 · 📦 3 · ⏱️ 19.08.2024):

	```
	git clone https://github.com/usnistgov/chemnlp
	```
- [PyPi](https://pypi.org/project/chemnlp) (📥 76 / month · 📦 1 · ⏱️ 07.08.2023):
	```
	pip install chemnlp
	```
</details>
<details><summary><b><a href="https://github.com/chiang-yuan/llamp">LLaMP</a></b> (🥉10 ·  ⭐ 57) - A web app and Python API for multi-modal RAG framework to ground LLMs on high-fidelity materials informatics. An.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a> <a href="https://en.wikipedia.org/wiki/Cheminformatics"><code>cheminformatics</code></a> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <a href="https://en.wikipedia.org/wiki/Multimodal_learning"><code>multimodal</code></a> <a href="https://en.wikipedia.org/wiki/Language_model"><code>language-models</code></a> <code>Python</code> <code>general-tool</code></summary>

- [GitHub](https://github.com/chiang-yuan/llamp) (👨‍💻 5 · 🔀 7 · 📋 25 - 32% open · ⏱️ 01.08.2024):

	```
	git clone https://github.com/chiang-yuan/llamp
	```
</details>
<details><summary><b><a href="https://github.com/IBM/molformer">MoLFormer</a></b> (🥉9 ·  ⭐ 240 · 💤) - Repository for MolFormer. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a></summary>

- [GitHub](https://github.com/IBM/molformer) (👨‍💻 5 · 🔀 41 · 📋 19 - 47% open · ⏱️ 16.10.2023):

	```
	git clone https://github.com/IBM/molformer
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/molskill">MolSkill</a></b> (🥉9 ·  ⭐ 100 · 💤) - Extracting medicinal chemistry intuition via preference machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a> <a href="https://en.wikipedia.org/wiki/Recommender_system"><code>recommender</code></a></summary>

- [GitHub](https://github.com/microsoft/molskill) (👨‍💻 4 · 🔀 9 · 📋 6 - 33% open · ⏱️ 31.10.2023):

	```
	git clone https://github.com/microsoft/molskill
	```
- [Conda](https://anaconda.org/msr-ai4science/molskill) (📥 300 · ⏱️ 18.06.2023):
	```
	conda install -c msr-ai4science molskill
	```
</details>
<details><summary><b><a href="https://github.com/lamalab-org/chemlift">chemlift</a></b> (🥉7 ·  ⭐ 31 · 💤) - Language-interfaced fine-tuning for chemistry. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lamalab-org/chemlift) (👨‍💻 2 · 🔀 3 · 📋 18 - 61% open · ⏱️ 14.10.2023):

	```
	git clone https://github.com/lamalab-org/chemlift
	```
</details>
<details><summary><b><a href="https://github.com/vertaix/LLM-Prop">LLM-Prop</a></b> (🥉7 ·  ⭐ 26) - A repository for the LLM-Prop implementation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vertaix/LLM-Prop) (👨‍💻 6 · 🔀 5 · 📋 2 - 50% open · ⏱️ 26.04.2024):

	```
	git clone https://github.com/vertaix/LLM-Prop
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/crystal-text-llm">crystal-text-llm</a></b> (🥉5 ·  ⭐ 65) - Large language models to generate stable crystals. <code><a href="https://tldrlegal.com/search?q=CC-BY-NC-4.0">CC-BY-NC-4.0</a></code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a></summary>

- [GitHub](https://github.com/facebookresearch/crystal-text-llm) (👨‍💻 3 · 🔀 11 · 📋 9 - 77% open · ⏱️ 18.06.2024):

	```
	git clone https://github.com/facebookresearch/crystal-text-llm
	```
</details>
<details><summary><b><a href="https://github.com/CFN-softbio/SciBot">SciBot</a></b> (🥉5 ·  ⭐ 28) - SciBot is a simple demo of building a domain-specific chatbot for science. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Large_language_model#Agency"><code>ai-agent</code></a></summary>

- [GitHub](https://github.com/CFN-softbio/SciBot) (👨‍💻 1 · 🔀 8 · 📦 1 · ⏱️ 03.09.2024):

	```
	git clone https://github.com/CFN-softbio/SciBot
	```
</details>
<details><summary><b><a href="https://github.com/maykcaldas/MAPI_LLM">MAPI_LLM</a></b> (🥉5 ·  ⭐ 9) - A LLM application developed during the LLM March MADNESS Hackathon https://doi.org/10.1039/D3DD00113J. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Large_language_model#Agency"><code>ai-agent</code></a> <code>dataset</code></summary>

- [GitHub](https://github.com/maykcaldas/MAPI_LLM) (👨‍💻 2 · 🔀 2 · ⏱️ 11.04.2024):

	```
	git clone https://github.com/maykcaldas/MAPI_LLM
	```
</details>
<details><summary><b><a href="https://github.com/lamm-mit/Cephalo">Cephalo</a></b> (🥉5 ·  ⭐ 6 · 🐣) - Multimodal Vision-Language Models for Bio-Inspired Materials Analysis and Design. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a> <a href="https://en.wikipedia.org/wiki/Multimodal_learning"><code>multimodal</code></a> <code>pretrained</code></summary>

- [GitHub](https://github.com/lamm-mit/Cephalo) (🔀 1 · ⏱️ 23.07.2024):

	```
	git clone https://github.com/lamm-mit/Cephalo
	```
</details>
<details><summary>Show 6 hidden projects...</summary>

- <b><a href="https://github.com/mcs07/ChemDataExtractor">ChemDataExtractor</a></b> (🥇16 ·  ⭐ 300 · 💀) - Automatically extract chemical information from scientific documents. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>literature-data</code>
- <b><a href="https://github.com/materialsintelligence/mat2vec">mat2vec</a></b> (🥈12 ·  ⭐ 620 · 💀) - Supplementary Materials for Tshitoyan et al. Unsupervised word embeddings capture latent knowledge from materials.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://github.com/whitead/nlcc">nlcc</a></b> (🥈11 ·  ⭐ 44 · 💀) - Natural language computational chemistry command line interface. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code>
- <b><a href="https://github.com/StefanoSanvitoGroup/BERT-PSIE-TC">BERT-PSIE-TC</a></b> (🥉5 ·  ⭐ 12 · 💀) - A dataset of Curie temperatures automatically extracted from scientific literature with the use of the BERT-PSIE.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>magnetism</code>
- <b><a href="https://github.com/ShuHuang/chemdatawriter">ChemDataWriter</a></b> (🥉4 ·  ⭐ 14 · 💤) - ChemDataWriter is a transformer-based library for automatically generating research books in the chemistry area. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>literature-data</code>
- <b><a href="https://github.com/hoon-ock/CatBERTa">CatBERTa</a></b> (🥉3 ·  ⭐ 19) - Large Language Model for Catalyst Property Prediction. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a> <a href="https://en.wikipedia.org/wiki/Catalysis"><code>catalysis</code></a>
</details>
<br>

## Materials Discovery

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that implement materials discovery methods using atomistic ML._

🔗&nbsp;<b><a href="https://www.microsoft.com/en-us/research/blog/mattergen-property-guided-materials-design/">MatterGen</a></b>  - A generative model for inorganic materials design https://doi.org/10.48550/arXiv.2312.03687. <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a> <a href="https://en.wikipedia.org/wiki/Proprietary_software"><code>proprietary</code></a>

<details><summary><b><a href="https://github.com/CompRhys/aviary">aviary</a></b> (🥇15 ·  ⭐ 47) - The Wren sits on its Roost in the Aviary. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CompRhys/aviary) (👨‍💻 4 · 🔀 11 · 📋 29 - 13% open · ⏱️ 26.08.2024):

	```
	git clone https://github.com/CompRhys/aviary
	```
</details>
<details><summary><b><a href="https://gitlab.com/cest-group/boss">BOSS</a></b> (🥇12 ·  ⭐ 20) - Bayesian Optimization Structure Search (BOSS). <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>probabilistic</code></summary>

- [PyPi](https://pypi.org/project/aalto-boss) (📥 540 / month · ⏱️ 20.07.2024):
	```
	pip install aalto-boss
	```
- [GitLab](https://gitlab.com/cest-group/boss) (🔀 10 · 📋 30 - 3% open · ⏱️ 20.07.2024):

	```
	git clone https://gitlab.com/cest-group/boss
	```
</details>
<details><summary><b><a href="https://github.com/google-deepmind/materials_discovery">Materials Discovery: GNoME</a></b> (🥈9 ·  ⭐ 860) - Graph Networks for Materials Science (GNoME) and dataset of 381,000 novel stable materials. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a> <code>datasets</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Proprietary_software"><code>proprietary</code></a></summary>

- [GitHub](https://github.com/google-deepmind/materials_discovery) (👨‍💻 2 · 🔀 130 · 📋 22 - 81% open · ⏱️ 04.09.2024):

	```
	git clone https://github.com/google-deepmind/materials_discovery
	```
</details>
<details><summary><b><a href="https://agox.gitlab.io/agox/">AGOX</a></b> (🥈9 ·  ⭐ 13) - AGOX is a package for global optimization of atomic system using e.g. the energy calculated from density functional.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>structure-optimization</code></a></summary>

- [PyPi](https://pypi.org/project/agox) (📥 140 / month · ⏱️ 26.08.2024):
	```
	pip install agox
	```
- [GitLab](https://gitlab.com/agox/agox) (🔀 5 · 📋 24 - 62% open · ⏱️ 26.08.2024):

	```
	git clone https://gitlab.com/agox/agox
	```
</details>
<details><summary><b><a href="https://github.com/Minoru938/CSPML">CSPML (crystal structure prediction with machine learning-based element substitution)</a></b> (🥉5 ·  ⭐ 18) - Original implementation of CSPML. <code>Unlicensed</code> <code>structure-prediction</code></summary>

- [GitHub](https://github.com/Minoru938/CSPML) (🔀 8 · 📋 3 - 66% open · ⏱️ 09.07.2024):

	```
	git clone https://github.com/minoru938/cspml
	```
</details>
<details><summary>Show 6 hidden projects...</summary>

- <b><a href="https://github.com/ulissigroup/CAMD">Computational Autonomy for Materials Discovery (CAMD)</a></b> (🥈6 ·  ⭐ 1 · 💀) - Agent-based sequential learning software for materials discovery. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://gitlab.com/bigd4/magus">MAGUS</a></b> (🥉4 ·  ⭐ 57 · 💀) - Machine learning And Graph theory assisted Universal structure Searcher. <code>Unlicensed</code> <code>structure-prediction</code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a>
- <b><a href="https://github.com/MDIL-SNU/SPINNER">SPINNER</a></b> (🥉4 ·  ⭐ 12 · 💀) - SPINNER (Structure Prediction of Inorganic crystals using Neural Network potentials with Evolutionary and Random.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>C++</code> <code>structure-prediction</code>
- <b><a href="https://github.com/takahashi-akira-36m/ml_atomate">ML-atomate</a></b> (🥉4 ·  ⭐ 4 · 💤) - Machine learning-assisted Atomate code for autonomous computational materials screening. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a> <code>workflows</code>
- <b><a href="https://github.com/aced-differentiate/closed-loop-acceleration-benchmarks">closed-loop-acceleration-benchmarks</a></b> (🥉4 · 💀) - Data and scripts in support of the publication By how much can closed-loop frameworks accelerate computational.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a> <code>single-paper</code>
- <b><a href="https://github.com/CitrineInformatics-ERD-public/sl_discovery">sl_discovery</a></b> (🥉3 ·  ⭐ 5 · 💀) - Data processing and models related to Quantifying the performance of machine learning models in materials discovery. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a> <code>single-paper</code>
</details>
<br>

## Mathematical tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that implement mathematical objects used in atomistic machine learning._

<details><summary><b><a href="https://github.com/google-deepmind/kfac-jax">KFAC-JAX</a></b> (🥇19 ·  ⭐ 230) - Second Order Optimization and Curvature Estimation with K-FAC in JAX. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google-deepmind/kfac-jax) (👨‍💻 14 · 🔀 17 · 📦 10 · 📋 18 - 50% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/google-deepmind/kfac-jax
	```
- [PyPi](https://pypi.org/project/kfac-jax) (📥 910 / month · 📦 1 · ⏱️ 04.04.2024):
	```
	pip install kfac-jax
	```
</details>
<details><summary><b><a href="https://github.com/ziatdinovmax/gpax">gpax</a></b> (🥇17 ·  ⭐ 200) - Gaussian Processes for Experimental Sciences. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>probabilistic</code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a></summary>

- [GitHub](https://github.com/ziatdinovmax/gpax) (👨‍💻 6 · 🔀 22 · 📦 2 · 📋 40 - 20% open · ⏱️ 21.05.2024):

	```
	git clone https://github.com/ziatdinovmax/gpax
	```
- [PyPi](https://pypi.org/project/gpax) (📥 220 / month · ⏱️ 20.03.2024):
	```
	pip install gpax
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/sphericart">SpheriCart</a></b> (🥇17 ·  ⭐ 65) - Multi-language library for the calculation of spherical harmonics in Cartesian coordinates. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lab-cosmo/sphericart) (👨‍💻 10 · 🔀 11 · 📥 67 · 📦 3 · 📋 41 - 56% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/lab-cosmo/sphericart
	```
- [PyPi](https://pypi.org/project/sphericart) (📥 530 / month · ⏱️ 04.09.2024):
	```
	pip install sphericart
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/Polynomials4ML.jl">Polynomials4ML.jl</a></b> (🥈14 ·  ⭐ 12) - Polynomials for ML: fast evaluation, batching, differentiation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>Julia</code></summary>

- [GitHub](https://github.com/ACEsuit/Polynomials4ML.jl) (👨‍💻 10 · 🔀 5 · 📋 51 - 33% open · ⏱️ 22.06.2024):

	```
	git clone https://github.com/ACEsuit/Polynomials4ML.jl
	```
</details>
<details><summary><b><a href="https://github.com/risi-kondor/GElib">GElib</a></b> (🥉8 ·  ⭐ 19) - C++/CUDA library for SO(3) equivariant operations. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code>C++</code></summary>

- [GitHub](https://github.com/risi-kondor/GElib) (👨‍💻 4 · 🔀 3 · 📋 8 - 50% open · ⏱️ 27.07.2024):

	```
	git clone https://github.com/risi-kondor/GElib
	```
</details>
<details><summary><b><a href="https://github.com/aced-differentiate/EquivariantOperators.jl">EquivariantOperators.jl</a></b> (🥉6 ·  ⭐ 18 · 💤) - This package is deprecated. Functionalities are migrating to Porcupine.jl. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>Julia</code></summary>

- [GitHub](https://github.com/aced-differentiate/EquivariantOperators.jl) (⏱️ 27.09.2023):

	```
	git clone https://github.com/aced-differentiate/EquivariantOperators.jl
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/toolbox">COSMO Toolbox</a></b> (🥉6 ·  ⭐ 7) - Assorted libraries and utilities for atomistic simulation analysis. <code>Unlicensed</code> <code>C++</code></summary>

- [GitHub](https://github.com/lab-cosmo/toolbox) (👨‍💻 9 · 🔀 6 · ⏱️ 19.03.2024):

	```
	git clone https://github.com/lab-cosmo/toolbox
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/lie-nn/lie-nn">lie-nn</a></b> (🥈9 ·  ⭐ 26 · 💀) - Tools for building equivariant polynomials on reductive Lie groups. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://github.com/risi-kondor/cnine">cnine</a></b> (🥉6 ·  ⭐ 4) - Cnine tensor library. <code>Unlicensed</code> <code>C++</code>
- <b><a href="https://github.com/lab-cosmo/torch_spex">torch_spex</a></b> (🥉3 ·  ⭐ 3) - Spherical expansions in PyTorch. <code>Unlicensed</code>
- <b><a href="https://github.com/lab-cosmo/wigner_kernels">Wigner Kernels</a></b> (🥉2 ·  ⭐ 2 · 💀) - Collection of programs to benchmark Wigner kernels. <code>Unlicensed</code> <code>benchmarking</code>
</details>
<br>

## Molecular Dynamics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that simplify the integration of molecular dynamics and atomistic machine learning._

<details><summary><b><a href="https://github.com/jax-md/jax-md">JAX-MD</a></b> (🥇26 ·  ⭐ 1.2K) - Differentiable, Hardware Accelerated, Molecular Dynamics. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jax-md/jax-md) (👨‍💻 34 · 🔀 190 · 📦 56 · 📋 150 - 45% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/jax-md/jax-md
	```
- [PyPi](https://pypi.org/project/jax-md) (📥 3.6K / month · 📦 3 · ⏱️ 09.08.2023):
	```
	pip install jax-md
	```
</details>
<details><summary><b><a href="https://github.com/luigibonati/mlcolvar">mlcolvar</a></b> (🥈18 ·  ⭐ 91) - A unified framework for machine learning collective variables for enhanced sampling simulations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>sampling</code></summary>

- [GitHub](https://github.com/luigibonati/mlcolvar) (👨‍💻 8 · 🔀 24 · 📦 2 · 📋 70 - 18% open · ⏱️ 14.06.2024):

	```
	git clone https://github.com/luigibonati/mlcolvar
	```
- [PyPi](https://pypi.org/project/mlcolvar) (📥 200 / month · ⏱️ 12.06.2024):
	```
	pip install mlcolvar
	```
</details>
<details><summary><b><a href="https://github.com/FitSNAP/FitSNAP">FitSNAP</a></b> (🥈17 ·  ⭐ 140) - Software for generating SNAP machine-learning interatomic potentials. <code><a href="http://bit.ly/2KucAZR">GPL-2.0</a></code></summary>

- [GitHub](https://github.com/FitSNAP/FitSNAP) (👨‍💻 24 · 🔀 50 · 📥 9 · 📦 2 · 📋 72 - 22% open · ⏱️ 09.08.2024):

	```
	git clone https://github.com/FitSNAP/FitSNAP
	```
- [Conda](https://anaconda.org/conda-forge/fitsnap3) (📥 8.1K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge fitsnap3
	```
</details>
<details><summary><b><a href="https://github.com/openmm/openmm-torch">openmm-torch</a></b> (🥈16 ·  ⭐ 180) - OpenMM plugin to define forces with neural networks. <code><a href="https://github.com/openmm/openmm-torch#license">Custom</a></code> <code>ML-IAP</code> <code>C++</code></summary>

- [GitHub](https://github.com/openmm/openmm-torch) (👨‍💻 8 · 🔀 23 · 📋 91 - 27% open · ⏱️ 23.08.2024):

	```
	git clone https://github.com/openmm/openmm-torch
	```
- [Conda](https://anaconda.org/conda-forge/openmm-torch) (📥 440K · ⏱️ 03.06.2024):
	```
	conda install -c conda-forge openmm-torch
	```
</details>
<details><summary><b><a href="https://github.com/openmm/openmm-ml">OpenMM-ML</a></b> (🥉13 ·  ⭐ 79) - High level API for using machine learning models in OpenMM simulations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>ML-IAP</code></summary>

- [GitHub](https://github.com/openmm/openmm-ml) (👨‍💻 5 · 🔀 19 · 📋 55 - 36% open · ⏱️ 06.08.2024):

	```
	git clone https://github.com/openmm/openmm-ml
	```
- [Conda](https://anaconda.org/conda-forge/openmm-ml) (📥 5K · ⏱️ 07.06.2024):
	```
	conda install -c conda-forge openmm-ml
	```
</details>
<details><summary><b><a href="https://github.com/mir-group/pair_nequip">pair_nequip</a></b> (🥉10 ·  ⭐ 41) - LAMMPS pair style for NequIP. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/mir-group/pair_nequip) (👨‍💻 3 · 🔀 12 · 📋 29 - 31% open · ⏱️ 05.06.2024):

	```
	git clone https://github.com/mir-group/pair_nequip
	```
</details>
<details><summary><b><a href="https://github.com/ICAMS/lammps-user-pace">PACE</a></b> (🥉9 ·  ⭐ 24 · 💤) - The LAMMPS ML-IAP `pair_style pace`, aka Atomic Cluster Expansion (ACE), aka ML-PACE,.. <code><a href="https://github.com/ICAMS/lammps-user-pace/blob/main/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/ICAMS/lammps-user-pace) (👨‍💻 6 · 🔀 10 · 📋 8 - 25% open · ⏱️ 27.11.2023):

	```
	git clone https://github.com/ICAMS/lammps-user-pace
	```
</details>
<details><summary><b><a href="https://github.com/mir-group/pair_allegro">pair_allegro</a></b> (🥉8 ·  ⭐ 34) - LAMMPS pair style for Allegro deep learning interatomic potentials with parallelization support. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/mir-group/pair_allegro) (👨‍💻 2 · 🔀 8 · 📋 30 - 40% open · ⏱️ 05.06.2024):

	```
	git clone https://github.com/mir-group/pair_allegro
	```
</details>
<details><summary><b><a href="https://github.com/initqp/somd">SOMD</a></b> (🥉5 ·  ⭐ 11) - Molecular dynamics package designed for the SIESTA DFT code. <code><a href="http://bit.ly/3pwmjO5">AGPL-3.0</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a></summary>

- [GitHub](https://github.com/initqp/somd) (🔀 2 · ⏱️ 17.08.2024):

	```
	git clone https://github.com/initqp/somd
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://gitlab.com/ivannovikov/interface-lammps-mlip-3">interface-lammps-mlip-3</a></b> (🥉3 ·  ⭐ 5 · 💀) - An interface between LAMMPS and MLIP (version 3). <code><a href="http://bit.ly/2KucAZR">GPL-2.0</a></code>
</details>
<br>

## Reinforcement Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on reinforcement learning for atomistic ML._

<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/isayev/ReLeaSE">ReLeaSE</a></b> (🥇11 ·  ⭐ 350 · 💀) - Deep Reinforcement Learning for de-novo Drug Design. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a>
- <b><a href="https://github.com/ulissigroup/catgym">CatGym</a></b> (🥉6 ·  ⭐ 11 · 💀) - Surface segregation using Deep Reinforcement Learning. <code><a href="https://tldrlegal.com/search?q=GPL">GPL</a></code>
</details>
<br>

## Representation Engineering

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that offer implementations of representations aka descriptors, fingerprints of atomistic systems, and models built with them, aka feature engineering._

<details><summary><b><a href="https://github.com/cdk/cdk">cdk</a></b> (🥇26 ·  ⭐ 480) - The Chemistry Development Kit. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">LGPL-2.1</a></code> <a href="https://en.wikipedia.org/wiki/Cheminformatics"><code>cheminformatics</code></a> <code>Java</code></summary>

- [GitHub](https://github.com/cdk/cdk) (👨‍💻 160 · 🔀 160 · 📥 22K · 📋 290 - 11% open · ⏱️ 03.09.2024):

	```
	git clone https://github.com/cdk/cdk
	```
- [Maven](https://search.maven.org/artifact/org.openscience.cdk/cdk-bundle) (📦 16 · ⏱️ 21.08.2023):
	```
	<dependency>
		<groupId>org.openscience.cdk</groupId>
		<artifactId>cdk-bundle</artifactId>
		<version>[VERSION]</version>
	</dependency>
	```
</details>
<details><summary><b><a href="https://github.com/SINGROUP/dscribe">DScribe</a></b> (🥇25 ·  ⭐ 390) - DScribe is a python package for creating machine learning descriptors for atomistic systems. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/SINGROUP/dscribe) (👨‍💻 18 · 🔀 86 · 📦 200 · 📋 100 - 11% open · ⏱️ 28.05.2024):

	```
	git clone https://github.com/SINGROUP/dscribe
	```
- [PyPi](https://pypi.org/project/dscribe) (📥 20K / month · 📦 35 · ⏱️ 28.05.2024):
	```
	pip install dscribe
	```
- [Conda](https://anaconda.org/conda-forge/dscribe) (📥 130K · ⏱️ 28.05.2024):
	```
	conda install -c conda-forge dscribe
	```
</details>
<details><summary><b><a href="https://github.com/ppdebreuck/modnet">MODNet</a></b> (🥇16 ·  ⭐ 76 · 📈) - MODNet: a framework for machine learning materials properties. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code> <code>small-data</code> <a href="https://en.wikipedia.org/wiki/Transfer_learning"><code>transfer-learning</code></a></summary>

- [GitHub](https://github.com/ppdebreuck/modnet) (👨‍💻 9 · 🔀 32 · 📦 8 · 📋 53 - 49% open · ⏱️ 22.08.2024):

	```
	git clone https://github.com/ppdebreuck/modnet
	```
</details>
<details><summary><b><a href="https://github.com/rouyang2017/SISSO">SISSO</a></b> (🥈14 ·  ⭐ 230) - A data-driven method combining symbolic regression and compressed sensing for accurate & interpretable models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>Fortran</code></summary>

- [GitHub](https://github.com/rouyang2017/SISSO) (👨‍💻 3 · 🔀 77 · 📋 76 - 23% open · ⏱️ 04.09.2024):

	```
	git clone https://github.com/rouyang2017/SISSO
	```
</details>
<details><summary><b><a href="https://github.com/drcassar/glasspy">GlassPy</a></b> (🥈14 ·  ⭐ 26 · 💤) - Python module for scientists working with glass materials. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code></summary>

- [GitHub](https://github.com/drcassar/glasspy) (👨‍💻 1 · 🔀 7 · 📦 5 · 📋 13 - 53% open · ⏱️ 21.01.2024):

	```
	git clone https://github.com/drcassar/glasspy
	```
- [PyPi](https://pypi.org/project/glasspy) (📥 500 / month · ⏱️ 05.09.2024):
	```
	pip install glasspy
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/librascal">Librascal</a></b> (🥈13 ·  ⭐ 80 · 💤) - A scalable and versatile library to generate representations for atomic-scale learning. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/lab-cosmo/librascal) (👨‍💻 30 · 🔀 20 · 📋 250 - 46% open · ⏱️ 30.11.2023):

	```
	git clone https://github.com/lab-cosmo/librascal
	```
</details>
<details><summary><b><a href="https://github.com/Luthaf/rascaline">Rascaline</a></b> (🥈12 ·  ⭐ 44) - Computing representations for atomistic machine learning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>Rust</code> <code>C++</code></summary>

- [GitHub](https://github.com/Luthaf/rascaline) (👨‍💻 14 · 🔀 13 · 📋 67 - 47% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/Luthaf/rascaline
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/nice">NICE</a></b> (🥉7 ·  ⭐ 12) - NICE (N-body Iteratively Contracted Equivariants) is a set of tools designed for the calculation of invariant and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lab-cosmo/nice) (👨‍💻 4 · 🔀 3 · 📋 3 - 66% open · ⏱️ 15.04.2024):

	```
	git clone https://github.com/lab-cosmo/nice
	```
</details>
<details><summary><b><a href="https://github.com/dilkins/TENSOAP">SA-GPR</a></b> (🥉6 ·  ⭐ 19) - Public repository for symmetry-adapted Gaussian Process Regression (SA-GPR). <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>C-lang</code></summary>

- [GitHub](https://github.com/dilkins/TENSOAP) (👨‍💻 5 · 🔀 13 · 📋 7 - 28% open · ⏱️ 23.07.2024):

	```
	git clone https://github.com/dilkins/TENSOAP
	```
</details>
<details><summary><b><a href="https://github.com/muhrin/milad">milad</a></b> (🥉5 ·  ⭐ 30) - Moment Invariants Local Atomic Descriptor. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a></summary>

- [GitHub](https://github.com/muhrin/milad) (👨‍💻 1 · 🔀 1 · 📦 2 · ⏱️ 20.08.2024):

	```
	git clone https://github.com/muhrin/milad
	```
</details>
<details><summary>Show 15 hidden projects...</summary>

- <b><a href="https://github.com/SUNCAT-Center/CatLearn">CatLearn</a></b> (🥈15 ·  ⭐ 100 · 💀) -  <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Surface_science"><code>surface-science</code></a>
- <b><a href="https://github.com/Kaaiian/CBFV">CBFV</a></b> (🥈12 ·  ⭐ 23 · 💀) - Tool to quickly create a composition-based feature vector. <code>Unlicensed</code>
- <b><a href="https://github.com/capoe/benchml">BenchML</a></b> (🥈11 ·  ⭐ 15 · 💀) - ML benchmarking and pipeling framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>benchmarking</code>
- <b><a href="https://github.com/sirmarcel/cmlkit">cmlkit</a></b> (🥉10 ·  ⭐ 34 · 💀) - tools for machine learning in condensed matter physics and quantum chemistry. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code>
- <b><a href="https://github.com/lantunes/skipatom">SkipAtom</a></b> (🥉9 ·  ⭐ 24 · 💀) - Distributed representations of atoms, inspired by the Skip-gram model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/zhuligs/fplib">fplib</a></b> (🥉6 ·  ⭐ 7 · 💀) - a fingerprint library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>C-lang</code> <code>single-paper</code>
- <b><a href="https://github.com/capoe/soapxx">SOAPxx</a></b> (🥉6 ·  ⭐ 7 · 💀) - A SOAP implementation. <code><a href="http://bit.ly/2KucAZR">GPL-2.0</a></code> <code>C++</code>
- <b><a href="https://github.com/libAtoms/soap_turbo">soap_turbo</a></b> (🥉6 ·  ⭐ 4 · 💀) - soap_turbo comprises a series of libraries to be used in combination with QUIP/GAP and TurboGAP. <code><a href="https://github.com/libAtoms/soap_turbo/blob/master/LICENSE.md">Custom</a></code> <code>Fortran</code>
- <b><a href="https://github.com/ceriottm/lode">pyLODE</a></b> (🥉6 ·  ⭐ 3 · 💀) - Pythonic implementation of LOng Distance Equivariants. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://en.wikipedia.org/wiki/Electrostatics"><code>electrostatics</code></a>
- <b><a href="https://bitbucket.org/andrewpeterson/amp/">AMP</a></b> (🥉6 · 💀) - Amp is an open-source package designed to easily bring machine-learning to atomistic calculations. <code>Unlicensed</code>
- <b><a href="https://github.com/cnislab/MXenes4HER">MXenes4HER</a></b> (🥉5 ·  ⭐ 6 · 💀) - Predicting hydrogen evolution (HER) activity over 4500 MXene materials https://doi.org/10.1039/D3TA00344B. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a> <a href="https://en.wikipedia.org/wiki/Catalysis"><code>catalysis</code></a> <code>scikit-learn</code> <code>single-paper</code>
- <b><a href="https://gitlab.com/sissopp_developers/sissopp">SISSO++</a></b> (🥉5 ·  ⭐ 3 · 💀) - C++ Implementation of SISSO with python bindings. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>C++</code>
- <b><a href="https://github.com/mm-tud/automl-materials">automl-materials</a></b> (🥉4 ·  ⭐ 5 · 💀) - AutoML for Regression Tasks on Small Tabular Data in Materials Design. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Automated_machine_learning"><code>autoML</code></a> <code>benchmarking</code> <code>single-paper</code>
- <b><a href="https://github.com/dppant/magnetism-prediction">magnetism-prediction</a></b> (🥉4 ·  ⭐ 1 · 💀) - DFT-aided Machine Learning Search for Magnetism in Fe-based Bimetallic Chalcogenides. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>magnetism</code> <code>single-paper</code>
- <b><a href="https://github.com/msg-byu/ML-for-CurieTemp-Predictions">ML-for-CurieTemp-Predictions</a></b> (🥉3 ·  ⭐ 1 · 💀) - Machine Learning Predictions of High-Curie-Temperature Materials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code> <code>magnetism</code>
</details>
<br>

## Representation Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General models that learn a representations aka embeddings of atomistic systems, such as message-passing neural networks (MPNN)._

<details><summary><b><a href="https://github.com/dmlc/dgl">Deep Graph Library (DGL)</a></b> (🥇39 ·  ⭐ 13K) - Python package built to ease deep learning on graph, on top of existing DL frameworks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dmlc/dgl) (👨‍💻 300 · 🔀 3K · 📦 290 · 📋 2.9K - 18% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/dmlc/dgl
	```
- [PyPi](https://pypi.org/project/dgl) (📥 110K / month · 📦 150 · ⏱️ 13.05.2024):
	```
	pip install dgl
	```
- [Conda](https://anaconda.org/dglteam/dgl) (📥 370K · ⏱️ 03.09.2024):
	```
	conda install -c dglteam dgl
	```
</details>
<details><summary><b><a href="https://github.com/pyg-team/pytorch_geometric/tree/master/torch_geometric/nn/models">PyG Models</a></b> (🥇35 ·  ⭐ 21K) - Representation learning models implemented in PyTorch Geometric. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>general-ml</code></summary>

- [GitHub](https://github.com/pyg-team/pytorch_geometric) (👨‍💻 520 · 🔀 3.6K · 📦 6.4K · 📋 3.7K - 27% open · ⏱️ 03.09.2024):

	```
	git clone https://github.com/pyg-team/pytorch_geometric
	```
</details>
<details><summary><b><a href="https://github.com/e3nn/e3nn">e3nn</a></b> (🥇28 ·  ⭐ 940) - A modular framework for neural networks with Euclidean symmetry. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/e3nn/e3nn) (👨‍💻 31 · 🔀 140 · 📦 290 · 📋 160 - 14% open · ⏱️ 25.08.2024):

	```
	git clone https://github.com/e3nn/e3nn
	```
- [PyPi](https://pypi.org/project/e3nn) (📥 120K / month · 📦 4 · ⏱️ 13.04.2022):
	```
	pip install e3nn
	```
- [Conda](https://anaconda.org/conda-forge/e3nn) (📥 21K · ⏱️ 18.06.2023):
	```
	conda install -c conda-forge e3nn
	```
</details>
<details><summary><b><a href="https://github.com/atomistic-machine-learning/schnetpack">SchNetPack</a></b> (🥇28 ·  ⭐ 770 · 📈) - SchNetPack - Deep Neural Networks for Atomistic Systems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/atomistic-machine-learning/schnetpack) (👨‍💻 35 · 🔀 210 · 📦 89 · 📋 250 - 2% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/atomistic-machine-learning/schnetpack
	```
- [PyPi](https://pypi.org/project/schnetpack) (📥 1.1K / month · 📦 4 · ⏱️ 05.09.2024):
	```
	pip install schnetpack
	```
</details>
<details><summary><b><a href="https://github.com/materialsvirtuallab/matgl">MatGL (Materials Graph Library)</a></b> (🥇23 ·  ⭐ 250) - Graph deep learning library for materials. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <a href="https://en.wikipedia.org/wiki/Multifidelity_simulation"><code>multifidelity</code></a></summary>

- [GitHub](https://github.com/materialsvirtuallab/matgl) (👨‍💻 17 · 🔀 59 · 📦 45 · 📋 95 - 7% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/materialsvirtuallab/matgl
	```
- [PyPi](https://pypi.org/project/m3gnet) (📥 680 / month · 📦 5 · ⏱️ 17.11.2022):
	```
	pip install m3gnet
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/DeepLearningExamples#graph-neural-networks">NVIDIA Deep Learning Examples for Tensor Cores</a></b> (🥈21 ·  ⭐ 13K) - State-of-the-Art Deep Learning scripts organized by models - easy to train and deploy with reproducible accuracy and.. <code><a href="https://github.com/NVIDIA/DeepLearningExamples/blob/master/DGLPyTorch/DrugDiscovery/SE3Transformer/LICENSE">Custom</a></code> <code>educational</code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a></summary>

- [GitHub](https://github.com/NVIDIA/DeepLearningExamples) (👨‍💻 120 · 🔀 3.1K · 📋 880 - 35% open · ⏱️ 04.04.2024):

	```
	git clone https://github.com/NVIDIA/DeepLearningExamples
	```
</details>
<details><summary><b><a href="https://github.com/divelab/DIG">DIG: Dive into Graphs</a></b> (🥈21 ·  ⭐ 1.8K · 💤) - A library for graph deep learning research. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code></summary>

- [GitHub](https://github.com/divelab/DIG) (👨‍💻 50 · 🔀 280 · 📋 210 - 16% open · ⏱️ 04.02.2024):

	```
	git clone https://github.com/divelab/DIG
	```
- [PyPi](https://pypi.org/project/dive-into-graphs) (📥 440 / month · ⏱️ 27.06.2022):
	```
	pip install dive-into-graphs
	```
</details>
<details><summary><b><a href="https://github.com/usnistgov/alignn">ALIGNN</a></b> (🥈21 ·  ⭐ 210) - Atomistic Line Graph Neural Network https://scholar.google.com/citations?user=9Q-tNnwAAAAJ&hl=en. <code><a href="https://github.com/usnistgov/alignn/blob/main/LICENSE.rst">Custom</a></code></summary>

- [GitHub](https://github.com/usnistgov/alignn) (👨‍💻 7 · 🔀 79 · 📦 14 · 📋 63 - 61% open · ⏱️ 29.08.2024):

	```
	git clone https://github.com/usnistgov/alignn
	```
- [PyPi](https://pypi.org/project/alignn) (📥 1.6K / month · 📦 6 · ⏱️ 30.08.2024):
	```
	pip install alignn
	```
</details>
<details><summary><b><a href="https://github.com/e3nn/e3nn-jax">e3nn-jax</a></b> (🥈21 ·  ⭐ 170) - jax library for E3 Equivariant Neural Networks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/e3nn/e3nn-jax) (👨‍💻 7 · 🔀 18 · 📦 38 · 📋 20 - 5% open · ⏱️ 14.08.2024):

	```
	git clone https://github.com/e3nn/e3nn-jax
	```
- [PyPi](https://pypi.org/project/e3nn-jax) (📥 3.1K / month · 📦 13 · ⏱️ 14.08.2024):
	```
	pip install e3nn-jax
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/Uni-Mol">Uni-Mol</a></b> (🥈18 ·  ⭐ 650) - Official Repository for the Uni-Mol Series Methods. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code></summary>

- [GitHub](https://github.com/deepmodeling/Uni-Mol) (👨‍💻 16 · 🔀 120 · 📥 15K · 📋 150 - 42% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/deepmodeling/Uni-Mol
	```
</details>
<details><summary><b><a href="https://github.com/aimat-lab/gcnn_keras">kgcnn</a></b> (🥈18 ·  ⭐ 100) - Graph convolutions in Keras with TensorFlow, PyTorch or Jax. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aimat-lab/gcnn_keras) (👨‍💻 7 · 🔀 29 · 📦 18 · 📋 86 - 13% open · ⏱️ 06.05.2024):

	```
	git clone https://github.com/aimat-lab/gcnn_keras
	```
- [PyPi](https://pypi.org/project/kgcnn) (📥 350 / month · 📦 3 · ⏱️ 27.02.2024):
	```
	pip install kgcnn
	```
</details>
<details><summary><b><a href="https://github.com/IntelLabs/matsciml">matsciml</a></b> (🥈17 ·  ⭐ 140) - Open MatSci ML Toolkit is a framework for prototyping and scaling out deep learning models for materials discovery.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>workflows</code> <code>benchmarking</code></summary>

- [GitHub](https://github.com/IntelLabs/matsciml) (👨‍💻 12 · 🔀 18 · 📋 57 - 36% open · ⏱️ 26.08.2024):

	```
	git clone https://github.com/IntelLabs/matsciml
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/Graphormer">Graphormer</a></b> (🥈16 ·  ⭐ 2.1K) - Graphormer is a general-purpose deep learning backbone for molecular modeling. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a> <code>pretrained</code></summary>

- [GitHub](https://github.com/microsoft/Graphormer) (👨‍💻 14 · 🔀 330 · 📋 160 - 58% open · ⏱️ 28.05.2024):

	```
	git clone https://github.com/microsoft/Graphormer
	```
</details>
<details><summary><b><a href="https://github.com/QUVA-Lab/escnn">escnn</a></b> (🥈16 ·  ⭐ 340 · 💤) - Equivariant Steerable CNNs Library for Pytorch https://quva-lab.github.io/escnn/. <code><a href="https://github.com/QUVA-Lab/escnn/blob/master/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/QUVA-Lab/escnn) (👨‍💻 10 · 🔀 43 · 📋 75 - 50% open · ⏱️ 17.10.2023):

	```
	git clone https://github.com/QUVA-Lab/escnn
	```
- [PyPi](https://pypi.org/project/escnn) (📥 500 / month · 📦 6 · ⏱️ 01.04.2022):
	```
	pip install escnn
	```
</details>
<details><summary><b><a href="https://github.com/ORNL/HydraGNN">HydraGNN</a></b> (🥈14 ·  ⭐ 58) - Distributed PyTorch implementation of multi-headed graph convolutional neural networks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ORNL/HydraGNN) (👨‍💻 13 · 🔀 23 · 📦 1 · 📋 49 - 34% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/ORNL/HydraGNN
	```
</details>
<details><summary><b><a href="https://github.com/lanl/hippynn">hippynn</a></b> (🥈12 ·  ⭐ 65) - python library for atomistic machine learning. <code><a href="https://github.com/lanl/hippynn/blob/main/LICENSE.txt">Custom</a></code> <code>workflows</code></summary>

- [GitHub](https://github.com/lanl/hippynn) (👨‍💻 14 · 🔀 23 · 📦 1 · 📋 18 - 38% open · ⏱️ 03.09.2024):

	```
	git clone https://github.com/lanl/hippynn
	```
</details>
<details><summary><b><a href="https://github.com/idocx/Atom2Vec">Atom2Vec</a></b> (🥈10 ·  ⭐ 32 · 💤) - Atom2Vec: a simple way to describe atoms for machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/idocx/Atom2Vec) (👨‍💻 1 · 🔀 9 · 📦 2 · 📋 3 - 66% open · ⏱️ 23.02.2024):

	```
	git clone https://github.com/idocx/Atom2Vec
	```
- [PyPi](https://pypi.org/project/atom2vec) (📥 79 / month · ⏱️ 23.02.2024):
	```
	pip install atom2vec
	```
</details>
<details><summary><b><a href="https://github.com/vict0rsch/faenet">FAENet</a></b> (🥈10 ·  ⭐ 26 · 💤) - Frame Averaging Equivariant GNN for materials modeling. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vict0rsch/faenet) (👨‍💻 3 · 🔀 2 · 📦 2 · ⏱️ 12.10.2023):

	```
	git clone https://github.com/vict0rsch/faenet
	```
- [PyPi](https://pypi.org/project/faenet) (📥 87 / month · ⏱️ 14.09.2023):
	```
	pip install faenet
	```
</details>
<details><summary><b><a href="https://github.com/atomicarchitects/equiformer">Equiformer</a></b> (🥉9 ·  ⭐ 190) - [ICLR23 Spotlight] Equiformer: Equivariant Graph Attention Transformer for 3D Atomistic Graphs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a></summary>

- [GitHub](https://github.com/atomicarchitects/equiformer) (👨‍💻 2 · 🔀 36 · 📋 14 - 42% open · ⏱️ 18.07.2024):

	```
	git clone https://github.com/atomicarchitects/equiformer
	```
</details>
<details><summary><b><a href="https://github.com/HSE-LAMBDA/ai4material_design">ai4material_design</a></b> (🥉9 ·  ⭐ 6 · 💤) - Code for Kazeev, N., Al-Maeeni, A.R., Romanov, I. et al. Sparse representation for machine learning the properties of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Crystallographic_defect"><code>material-defect</code></a></summary>

- [GitHub](https://github.com/HSE-LAMBDA/ai4material_design) (👨‍💻 11 · 🔀 3 · ⏱️ 21.11.2023):

	```
	git clone https://github.com/HSE-LAMBDA/ai4material_design
	```
</details>
<details><summary><b><a href="https://github.com/atomicarchitects/equiformer_v2">EquiformerV2</a></b> (🥉8 ·  ⭐ 190) - [ICLR24] EquiformerV2: Improved Equivariant Transformer for Scaling to Higher-Degree Representations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/atomicarchitects/equiformer_v2) (👨‍💻 2 · 🔀 25 · 📋 18 - 88% open · ⏱️ 16.07.2024):

	```
	git clone https://github.com/atomicarchitects/equiformer_v2
	```
</details>
<details><summary><b><a href="https://github.com/LLNL/graphite">graphite</a></b> (🥉8 ·  ⭐ 55) - A repository for implementing graph network models based on atomic structures. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/LLNL/graphite) (👨‍💻 2 · 🔀 9 · 📦 11 · 📋 4 - 75% open · ⏱️ 08.08.2024):

	```
	git clone https://github.com/llnl/graphite
	```
</details>
<details><summary><b><a href="https://github.com/usccolumbia/deeperGATGNN">DeeperGATGNN</a></b> (🥉8 ·  ⭐ 46 · 💤) - Scalable graph neural networks for materials property prediction. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/usccolumbia/deeperGATGNN) (👨‍💻 3 · 🔀 8 · 📋 12 - 33% open · ⏱️ 19.01.2024):

	```
	git clone https://github.com/usccolumbia/deeperGATGNN
	```
</details>
<details><summary>Show 35 hidden projects...</summary>

- <b><a href="https://github.com/awslabs/dgl-lifesci">dgl-lifesci</a></b> (🥇23 ·  ⭐ 710 · 💀) - Python package for graph neural networks in chemistry and biology. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/graphdeeplearning/benchmarking-gnns">benchmarking-gnns</a></b> (🥈14 ·  ⭐ 2.5K · 💀) - Repository for benchmarking graph neural networks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code> <code>benchmarking</code>
- <b><a href="https://github.com/txie-93/cgcnn">Crystal Graph Convolutional Neural Networks (CGCNN)</a></b> (🥈12 ·  ⭐ 630 · 💀) - Crystal graph convolutional neural networks for predicting material properties. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/NREL/nfp">Neural fingerprint (nfp)</a></b> (🥈12 ·  ⭐ 57 · 💀) - Keras layers for end-to-end learning with rdkit and pymatgen. <code><a href="https://github.com/NREL/nfp/blob/master/LICENSE">Custom</a></code>
- <b><a href="https://github.com/sparks-baird/CrabNet">Compositionally-Restricted Attention-Based Network (CrabNet)</a></b> (🥈12 ·  ⭐ 12 · 💀) - Predict materials properties using only the composition information!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/snap-stanford/pretrain-gnns">pretrained-gnns</a></b> (🥈10 ·  ⭐ 960 · 💀) - Strategies for Pre-training Graph Neural Networks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code>
- <b><a href="https://github.com/gasteigerjo/gdc">GDC</a></b> (🥈10 ·  ⭐ 260 · 💀) - Graph Diffusion Convolution, as proposed in Diffusion Improves Graph Learning (NeurIPS 2019). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a>
- <b><a href="https://github.com/FabianFuchsML/se3-transformer-public">SE(3)-Transformers</a></b> (🥉9 ·  ⭐ 480 · 💀) - code for the SE3 Transformers paper: https://arxiv.org/abs/2006.10503. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a>
- <b><a href="https://github.com/superlouis/GATGNN">GATGNN: Global Attention Graph Neural Network</a></b> (🥉9 ·  ⭐ 68 · 💀) - Pytorch Repository for our work: Graph convolutional neural networks with global attention for improved materials.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/learningmatter-mit/uvvisml">UVVisML</a></b> (🥉9 ·  ⭐ 21 · 💀) - Predict optical properties of molecules with machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Optical_properties"><code>optical-properties</code></a> <code>single-paper</code> <code>probabilistic</code>
- <b><a href="https://github.com/masashitsubaki/molecularGNN_smiles">molecularGNN_smiles</a></b> (🥉8 ·  ⭐ 290 · 💀) - The code of a graph neural network (GNN) for molecules, which is based on learning representations of r-radius.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/hyllios/CGAT">CGAT</a></b> (🥉8 ·  ⭐ 25 · 💀) - Crystal graph attention neural networks for materials prediction. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Hongyu-yu/T-e3nn">T-e3nn</a></b> (🥉8 ·  ⭐ 8 · 💀) - Time-reversal Euclidean neural networks based on e3nn. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>magnetism</code>
- <b><a href="https://github.com/tensorfieldnetworks/tensorfieldnetworks">tensorfieldnetworks</a></b> (🥉7 ·  ⭐ 150 · 💀) - Rotation- and translation-equivariant neural networks for 3D point clouds. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/atomistic-machine-learning/dtnn">DTNN</a></b> (🥉7 ·  ⭐ 76 · 💀) - Deep Tensor Neural Network. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/risilab/cormorant">Cormorant</a></b> (🥉7 ·  ⭐ 59 · 💀) - Codebase for Cormorant Neural Networks. <code><a href="https://github.com/risilab/cormorant/blob/master/LICENSE">Custom</a></code>
- <b><a href="https://github.com/Open-Catalyst-Project/AdsorbML">AdsorbML</a></b> (🥉7 ·  ⭐ 35 · 💀) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Surface_science"><code>surface-science</code></a> <code>single-paper</code>
- <b><a href="https://github.com/emilemathieu/escnn_jax">escnn_jax</a></b> (🥉7 ·  ⭐ 26 · 💀) - Equivariant Steerable CNNs Library for Pytorch https://quva-lab.github.io/escnn/. <code><a href="https://github.com/emilemathieu/escnn_jax/blob/master/LICENSE">Custom</a></code>
- <b><a href="https://github.com/aimat-lab/ML4pXRDs">ML4pXRDs</a></b> (🥉7 · 💀) - Contains code to train neural networks based on simulated powder XRDs from synthetic crystals. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/X-ray_crystallography"><code>XRD</code></a> <code>single-paper</code>
- <b><a href="https://github.com/ACEsuit/mace-layer">MACE-Layer</a></b> (🥉6 ·  ⭐ 33 · 💀) - Higher order equivariant graph neural networks for 3D point clouds. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pfnet-research/charge_transfer_nnp">charge_transfer_nnp</a></b> (🥉6 ·  ⭐ 29 · 💀) - Graph neural network potential with charge transfer. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Electrostatics"><code>electrostatics</code></a>
- <b><a href="https://github.com/learningmatter-mit/GLAMOUR">GLAMOUR</a></b> (🥉6 ·  ⭐ 20 · 💀) - Graph Learning over Macromolecule Representations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code>
- <b><a href="https://github.com/risilab/Autobahn">Autobahn</a></b> (🥉5 ·  ⭐ 30 · 💀) - Repository for Autobahn: Automorphism Based Graph Neural Networks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/atomistic-machine-learning/field_schnet">FieldSchNet</a></b> (🥉5 ·  ⭐ 16 · 💀) - Deep neural network for molecules in external fields. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/andy90/SCFNN">SCFNN</a></b> (🥉5 ·  ⭐ 15 · 💀) - Self-consistent determination of long-range electrostatics in neural network potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>C++</code> <a href="https://en.wikipedia.org/wiki/Electrostatics"><code>electrostatics</code></a> <code>single-paper</code>
- <b><a href="https://github.com/lantunes/CraTENet">CraTENet</a></b> (🥉5 ·  ⭐ 13 · 💀) - An attention-based deep neural network for thermoelectric transport properties. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Transport_phenomena"><code>transport-phenomena</code></a>
- <b><a href="https://github.com/M3RG-IITD/MDBENCHGNN">EGraFFBench</a></b> (🥉5 ·  ⭐ 8 · 💤) -  <code>Unlicensed</code> <code>single-paper</code> <code>benchmarking</code> <code>ML-IAP</code>
- <b><a href="https://github.com/learningmatter-mit/per-site_cgcnn">Per-Site CGCNN</a></b> (🥉5 ·  ⭐ 1 · 💀) - Crystal graph convolutional neural networks for predicting material properties. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code> <code>single-paper</code>
- <b><a href="https://github.com/learningmatter-mit/per-site_painn">Per-site PAiNN</a></b> (🥉5 ·  ⭐ 1 · 💀) - Fork of PaiNN for PerovskiteOrderingGCNNs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>probabilistic</code> <code>pretrained</code> <code>single-paper</code>
- <b><a href="https://github.com/gasteigerjo/gtn">Graph Transport Network</a></b> (🥉4 ·  ⭐ 16 · 💀) - Graph transport network (GTN), as proposed in Scalable Optimal Transport in High Dimensions for Graph Distances,.. <code><a href="https://github.com/gasteigerjo/gtn/blob/main/LICENSE.md">Custom</a></code> <a href="https://en.wikipedia.org/wiki/Transport_phenomena"><code>transport-phenomena</code></a>
- <b><a href="https://github.com/sirmarcel/gkx">gkx: Green-Kubo Method in JAX</a></b> (🥉4 ·  ⭐ 3) - Green-Kubo + JAX + MLPs = Anharmonic Thermal Conductivities Done Fast. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Transport_phenomena"><code>transport-phenomena</code></a>
- <b><a href="https://github.com/learningmatter-mit/atom_by_atom">atom_by_atom</a></b> (🥉3 ·  ⭐ 6 · 💤) - Atom-by-atom design of metal oxide catalysts for the oxygen evolution reaction with Machine Learning. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Surface_science"><code>surface-science</code></a> <code>single-paper</code>
- <b><a href="https://github.com/jeherr/element-encoder">Element encoder</a></b> (🥉3 ·  ⭐ 6 · 💀) - Autoencoder neural network to compress properties of atomic species into a vector representation. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>single-paper</code>
- <b><a href="https://zenodo.org/record/7967079">Point Edge Transformer</a></b> (🥉2) - Smooth, exact rotational symmetrization for deep learning on point clouds. <code><a href="https://tldrlegal.com/search?q=CC-BY-4.0">CC-BY-4.0</a></code>
- <b><a href="https://github.com/risilab/SphericalNet">SphericalNet</a></b> (🥉1 ·  ⭐ 3 · 💀) - Implementation of Clebsch-Gordan Networks (CGnet: https://arxiv.org/pdf/1806.09231.pdf) by GElib & cnine libraries in.. <code>Unlicensed</code>
</details>
<br>

## Universal Potentials

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Machine-learned interatomic potentials (ML-IAP) that have been trained on large, chemically and structural diverse datasets. For materials, this means e.g. datasets that include a majority of the periodic table._

🔗&nbsp;<b><a href="https://doi.org/10.24433/CO.0749085.v1">TeaNet</a></b>  - Universal neural network interatomic potential inspired by iterative electronic relaxations.. <code>ML-IAP</code>

🔗&nbsp;<b><a href="https://www.nature.com/articles/s41467-022-30687-9#code-availability">PreFerred Potential (PFP)</a></b>  - Universal neural network potential for material discovery https://doi.org/10.1038/s41467-022-30687-9. <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Proprietary_software"><code>proprietary</code></a>

🔗&nbsp;<b><a href="https://www.microsoft.com/en-us/research/blog/mattersim-a-deep-learning-model-for-materials-under-real-world-conditions/">MatterSim</a></b>  - A Deep Learning Atomistic Model Across Elements, Temperatures and Pressures https://doi.org/10.48550/arXiv.2405.04967. <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a> <a href="https://en.wikipedia.org/wiki/Proprietary_software"><code>proprietary</code></a>

<details><summary><b><a href="https://github.com/deepmodeling/deepmd-kit">DPA-2</a></b> (🥇24 ·  ⭐ 1.4K · 📉) - Towards a universal large atomic model for molecular and material simulation https://doi.org/10.48550/arXiv.2312.15492. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>ML-IAP</code> <code>pretrained</code> <code>workflows</code> <code>datasets</code></summary>

- [GitHub](https://github.com/deepmodeling/deepmd-kit) (👨‍💻 69 · 🔀 490 · 📥 39K · 📋 760 - 11% open · ⏱️ 06.07.2024):

	```
	git clone https://github.com/deepmodeling/deepmd-kit
	```
</details>
<details><summary><b><a href="https://github.com/CederGroupHub/chgnet">CHGNet</a></b> (🥈23 ·  ⭐ 220) - Pretrained universal neural network potential for charge-informed atomistic modeling https://chgnet.lbl.gov. <code><a href="https://github.com/CederGroupHub/chgnet/blob/main/LICENSE">Custom</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Electrostatics"><code>electrostatics</code></a> <code>magnetism</code> <code>structure-relaxation</code></summary>

- [GitHub](https://github.com/CederGroupHub/chgnet) (👨‍💻 8 · 🔀 61 · 📦 31 · 📋 55 - 10% open · ⏱️ 31.08.2024):

	```
	git clone https://github.com/CederGroupHub/chgnet
	```
- [PyPi](https://pypi.org/project/chgnet) (📥 29K / month · 📦 19 · ⏱️ 05.06.2024):
	```
	pip install chgnet
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/mace-mp">MACE-MP</a></b> (🥈19 ·  ⭐ 460) - Pretrained foundation models for materials chemistry. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>ML-IAP</code> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a></summary>

- [GitHub](https://github.com/ACEsuit/mace-mp) (👨‍💻 2 · 🔀 170 · 📥 24K · 📋 8 - 12% open · ⏱️ 24.04.2024):

	```
	git clone https://github.com/ACEsuit/mace-mp
	```
- [PyPi](https://pypi.org/project/mace-torch) (📥 7.4K / month · 📦 14 · ⏱️ 16.07.2024):
	```
	pip install mace-torch
	```
</details>
<details><summary><b><a href="https://github.com/MDIL-SNU/SevenNet">SevenNet</a></b> (🥉15 ·  ⭐ 100) - SevenNet (Scalable EquiVariance Enabled Neural Network) is a graph neural network interatomic potential package that.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>pretrained</code></summary>

- [GitHub](https://github.com/MDIL-SNU/SevenNet) (👨‍💻 9 · 🔀 12 · 📦 3 · 📋 13 - 30% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/MDIL-SNU/SevenNet
	```
</details>
<details><summary><b><a href="https://github.com/orbital-materials/orb-models">Orb Models</a></b> (🥉11 ·  ⭐ 95 · 🐣) - ORB forcefield models from Orbital Materials. <code><a href="https://github.com/orbital-materials/orb-models/blob/main/LICENSE">Custom</a></code> <code>ML-IAP</code> <code>pretrained</code></summary>

- [GitHub](https://github.com/orbital-materials/orb-models) (👨‍💻 5 · 🔀 11 · 📋 5 - 40% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/orbital-materials/orb-models
	```
- [PyPi](https://pypi.org/project/orb-models) (📥 470 / month · ⏱️ 02.09.2024):
	```
	pip install orb-models
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/JMP">Joint Multidomain Pre-Training (JMP)</a></b> (🥉5 ·  ⭐ 33 · 🐣) - Code for From Molecules to Materials Pre-training Large Generalizable Models for Atomic Property Prediction. <code><a href="https://tldrlegal.com/search?q=CC-BY-NC-4.0">CC-BY-NC-4.0</a></code> <code>pretrained</code> <code>ML-IAP</code> <code>general-tool</code></summary>

- [GitHub](https://github.com/facebookresearch/JMP) (👨‍💻 1 · 🔀 5 · ⏱️ 07.05.2024):

	```
	git clone https://github.com/facebookresearch/JMP
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/materialsvirtuallab/m3gnet">M3GNet</a></b> (🥉17 ·  ⭐ 230 · 💀) - Materials graph network with 3-body interactions featuring a DFT surrogate crystal relaxer and a state-of-the-art.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>ML-IAP</code> <code>pretrained</code>
</details>
<br>

## Unsupervised Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on unsupervised learning (USL) for atomistic ML, such as dimensionality reduction, clustering and visualization._

<details><summary><b><a href="https://github.com/sissa-data-science/DADApy">DADApy</a></b> (🥇17 ·  ⭐ 100) - Distance-based Analysis of DAta-manifolds in python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/sissa-data-science/DADApy) (👨‍💻 19 · 🔀 17 · 📦 8 · 📋 36 - 25% open · ⏱️ 02.09.2024):

	```
	git clone https://github.com/sissa-data-science/DADApy
	```
- [PyPi](https://pypi.org/project/dadapy) (📥 120 / month · ⏱️ 02.07.2024):
	```
	pip install dadapy
	```
</details>
<details><summary><b><a href="https://github.com/BingqingCheng/ASAP">ASAP</a></b> (🥈11 ·  ⭐ 140) - ASAP is a package that can quickly analyze and visualize datasets of crystal or molecular structures. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/BingqingCheng/ASAP) (👨‍💻 6 · 🔀 28 · 📦 6 · 📋 25 - 24% open · ⏱️ 27.06.2024):

	```
	git clone https://github.com/BingqingCheng/ASAP
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/lab-cosmo/sketchmap">Sketchmap</a></b> (🥈8 ·  ⭐ 44 · 💀) - Suite of programs to perform non-linear dimensionality reduction -- sketch-map in particular. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>C++</code>
- <b><a href="https://github.com/learningmatter-mit/Coarse-Graining-Auto-encoders">Coarse-Graining-Auto-encoders</a></b> (🥉5 ·  ⭐ 21 · 💀) - Implementation of coarse-graining Autoencoders. <code>Unlicensed</code> <code>single-paper</code>
- <b><a href="https://github.com/mathsphy/paper-ml-robustness-material-property">paper-ml-robustness-material-property</a></b> (🥉5 ·  ⭐ 4 · 💀) - A critical examination of robustness and generalizability of machine learning prediction of materials properties. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>datasets</code> <code>single-paper</code>
- <b><a href="https://github.com/Minoru938/KmdPlus">KmdPlus</a></b> (🥉2 ·  ⭐ 3 · 💤) - This module contains a class for treating kernel mean descriptor (KMD), and a function for generating descriptors with.. <code>Unlicensed</code>
- <b><a href="https://gitlab.mpcdf.mpg.de/klai/decaf">Descriptor Embedding and Clustering for Atomisitic-environment Framework (DECAF)</a></b> ( ⭐ 2) - Provides a workflow to obtain clustering of local environments in dataset of structures. <code>Unlicensed</code>
</details>
<br>

## Visualization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on visualization (viz.) for atomistic ML._

<details><summary><b><a href="https://github.com/janosh/pymatviz">pymatviz</a></b> (🥇22 ·  ⭐ 150) - A toolkit for visualizations in materials informatics. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>general-tool</code> <code>probabilistic</code></summary>

- [GitHub](https://github.com/janosh/pymatviz) (👨‍💻 7 · 🔀 13 · 📦 8 · 📋 43 - 23% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/janosh/pymatviz
	```
- [PyPi](https://pypi.org/project/pymatviz) (📥 2.6K / month · 📦 2 · ⏱️ 01.09.2024):
	```
	pip install pymatviz
	```
</details>
<details><summary><b><a href="https://github.com/materialsproject/crystaltoolkit">Crystal Toolkit</a></b> (🥇22 ·  ⭐ 140) - Crystal Toolkit is a framework for building web apps for materials science and is currently powering the new Materials.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/materialsproject/crystaltoolkit) (👨‍💻 28 · 🔀 56 · 📦 38 · 📋 110 - 47% open · ⏱️ 04.09.2024):

	```
	git clone https://github.com/materialsproject/crystaltoolkit
	```
- [PyPi](https://pypi.org/project/crystal-toolkit) (📥 1.1K / month · 📦 8 · ⏱️ 04.09.2024):
	```
	pip install crystal-toolkit
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/chemiscope">Chemiscope</a></b> (🥈19 ·  ⭐ 130) - An interactive structure/property explorer for materials and molecules. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>JavaScript</code></summary>

- [GitHub](https://github.com/lab-cosmo/chemiscope) (👨‍💻 22 · 🔀 30 · 📥 260 · 📦 6 · 📋 120 - 29% open · ⏱️ 03.09.2024):

	```
	git clone https://github.com/lab-cosmo/chemiscope
	```
- [npm](https://www.npmjs.com/package/chemiscope) (📥 17 / month · 📦 3 · ⏱️ 15.03.2023):
	```
	npm install chemiscope
	```
</details>
<details><summary><b><a href="https://github.com/zincware/ZnDraw">ZnDraw</a></b> (🥉18 ·  ⭐ 30) - A powerful tool for visualizing, modifying, and analysing atomistic systems. <code><a href="http://bit.ly/2M0xmjV">EPL-2.0</a></code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a> <code>JavaScript</code></summary>

- [GitHub](https://github.com/zincware/ZnDraw) (👨‍💻 7 · 🔀 2 · 📦 3 · 📋 320 - 31% open · ⏱️ 28.08.2024):

	```
	git clone https://github.com/zincware/ZnDraw
	```
- [PyPi](https://pypi.org/project/zndraw) (📥 900 / month · 📦 2 · ⏱️ 26.08.2024):
	```
	pip install zndraw
	```
</details>
<details><summary><b><a href="https://github.com/janosh/elementari">Elementari</a></b> (🥉13 ·  ⭐ 130) - Interactive browser visualizations for materials science: periodic tables, 3d crystal structures, Bohr atoms, nuclei,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>JavaScript</code></summary>

- [GitHub](https://github.com/janosh/elementari) (👨‍💻 2 · 🔀 12 · 📦 3 · 📋 7 - 28% open · ⏱️ 19.07.2024):

	```
	git clone https://github.com/janosh/elementari
	```
- [npm](https://www.npmjs.com/package/elementari) (📥 110 / month · 📦 1 · ⏱️ 15.01.2024):
	```
	npm install elementari
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/usnistgov/atomvision">Atomvision</a></b> (🥉11 ·  ⭐ 29 · 💀) - Deep learning framework for atomistic image data. <code><a href="https://github.com/usnistgov/atomvision/blob/master/LICENSE.md">Custom</a></code> <a href="https://en.wikipedia.org/wiki/Computer_vision"><code>computer-vision</code></a> <a href="https://en.wikipedia.org/wiki/Experimental_physics"><code>experimental-data</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
</details>
<br>

## Wavefunction methods (ML-WFT)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects and models that focus on quantities of wavefunction theory methods, such as Monte Carlo techniques like deep learning variational Monte Carlo (DL-VMC), quantum chemistry methods, etc._

<details><summary><b><a href="https://github.com/deepqmc/deepqmc">DeepQMC</a></b> (🥇18 ·  ⭐ 340 · 📈) - Deep learning quantum Monte Carlo for electrons in real space. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/deepqmc/deepqmc) (👨‍💻 13 · 🔀 58 · 📦 2 · 📋 45 - 11% open · ⏱️ 14.08.2024):

	```
	git clone https://github.com/deepqmc/deepqmc
	```
- [PyPi](https://pypi.org/project/deepqmc) (📥 150 / month · ⏱️ 20.11.2023):
	```
	pip install deepqmc
	```
</details>
<details><summary><b><a href="https://github.com/google-deepmind/ferminet">FermiNet</a></b> (🥈15 ·  ⭐ 710) - An implementation of the Fermionic Neural Network for ab-initio electronic structure calculations. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a></summary>

- [GitHub](https://github.com/google-deepmind/ferminet) (👨‍💻 18 · 🔀 120 · 📋 48 - 2% open · ⏱️ 22.08.2024):

	```
	git clone https://github.com/google-deepmind/ferminet
	```
</details>
<details><summary><b><a href="https://github.com/mdsunivie/deeperwin">DeepErwin</a></b> (🥉9 ·  ⭐ 47) - DeepErwin is a python 3.8+ package that implements and optimizes JAX 2.x wave function models for numerical solutions.. <code><a href="https://github.com/mdsunivie/deeperwin/blob/master/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/mdsunivie/deeperwin) (👨‍💻 7 · 🔀 6 · 📥 9 · ⏱️ 07.06.2024):

	```
	git clone https://github.com/mdsunivie/deeperwin
	```
- [PyPi](https://pypi.org/project/deeperwin) (📥 53 / month · ⏱️ 14.12.2021):
	```
	pip install deeperwin
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/ACEsuit/ACEpsi.jl">ACEpsi.jl</a></b> (🥉6 ·  ⭐ 2 · 💤) - ACE wave function parameterizations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_engineering"><code>rep-eng</code></a> <code>Julia</code>
- <b><a href="https://github.com/atomistic-machine-learning/SchNOrb">SchNOrb</a></b> (🥉5 ·  ⭐ 58 · 💀) - Unifying machine learning and quantum chemistry with a deep neural network for molecular wavefunctions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary>Show 1 hidden projects...</summary>


</details>

---

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
