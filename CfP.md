# FloraPalooza 2026 - Call for Participation

## Synopsis

The Imageomics Institute is hosting a 3.5-day workshop offering a unique opportunity to develop proof-of-concepts demonstrating how the application of computer vision techniques can transform plant imagery analyses such as biodiversity assessment, plant-insect interaction studies, and trait data extraction. This event will bring together an interdisciplinary group around a shared interest of analyzing plant imagery (e.g., herbarium, in-situ, hyperspectral, remote sensing images) with AI/ML, including ML researchers, ecologists, biologists, software developers, and data engineers. Participants will work in small groups to collaboratively develop [FAIR](https://www.go-fair.org/fair-principles/) data products, tutorials, tools, workflows, and other products targeting the motivating challenge.

The event will take place August 17-20 at Hyatt House Columbus/OSU near The Ohio State University in Columbus, OH, USA. To apply to participate, please fill out the [FloraPalooza 2026 Application for Participation](https://forms.gle/fVcrmbvYQDdWKMSSA) by the end of June 25, 2026. Funds to assist with travel expenses are available but limited, as is space. We expect to notify applicants about acceptance by July 2, 2026.

## Contents:

- [About the event](#about-the-event)  
- [Motivation](#motivation)  
- [Goals & Desired Outcomes](#goals--desired-outcomes)  
- [Scope](#scope)  
- [Date and Location](#date-and-location)  
- [Who should participate](#who-should-participate)  
- [About the Imageomics Institute](#about-the-imageomics-institute)  
- [Organizing Team](#organizing-team)

## About the event

FloraPalooza 2026 will bring together an interdisciplinary group interested in using AI/ML to analyze images of plants. One area of interest is deriving traits from images, including, but not limited to, morphological attributes (e.g., specific leaf area, nitrogen concentration, or lobing, leaf size), phenological traits (e.g., timing of flowering, leaf-out dates), or pollination syndrome. Other areas of interest include, but are not limited to, assessing plant biodiversity, investigating plant-insect interactions, and species identification. 

This event offers a hands-on, collaborative experience. It is not intended to be a competitive hackathon or a conference. We expect participants to include AI/ML researchers, data scientists, ecologists, evolutionary biologists, data or specimen curators, tool developers, and knowledge engineers. Participants will self-organize into small groups to work hands-on and collaboratively on self-selected targets and outcomes towards the motivations and goals of the event. The process of self-organizing and choosing work targets will be facilitated, but every participant will play an equally active role in making the event a successful, rewarding experience. We aim for an event that will give everyone ample opportunities to contribute their skills and experience, acquire new knowledge, increase technological awareness, and find potential new collaborators. Although the event is primarily designed to create code, tutorials, datasets, workflows and other tangible outcomes, the format will leave room for networking and participant-driven exchange of know-how and skills.

## Motivation

Plants underpin terrestrial ecosystems, and questions about their traits and phenology, taxonomy and phylogeny, interactions, and community-scale biodiversity sit at the core of ecology and evolutionary biology. Images are among our richest sources of information for addressing them, spanning herbarium specimens, in-situ photographs of plants and communities, and remotely sensed and hyperspectral imagery. Digitized collections, citizen-science platforms, and sensing missions have produced an enormous and growing trove of this imagery, encoding latent information about form, function, identity, and ecological relationships that remains difficult to extract and analyze at scale. The central question this event takes up is therefore: how can we reliably mobilize the information embedded in plant images—across data types, methods, and domains—and at a scale that matches the data now available?

We will approach this question with recently developed AI/ML tools. For example, the Imageomics Institute and FloraPalooza coorganizers have developed a variety of tools and ML models for extracting various morphological aspects from images, including:

- [BioCLIP 2](https://imageomics.github.io/bioclip-2/): a foundation model for the tree of life with a vast set of emerging properties  
- Fine-grain image analysis and interpretability ([Prompt-CAM](https://github.com/Imageomics/Prompt_CAM), [Finer-CAM](https://github.com/Imageomics/Finer-CAM), [INTR](https://github.com/Imageomics/INTR))  
- Connections to taxonomy and phylogeny ([HComP-Net](https://imageomics.github.io/HComPNet/), [Phylo-Diffusion](https://imageomics.github.io/phylo-diffusion/))  
- [LeafMachine2](https://www.leafmachine.org/) (W. Weaver and S. Smith)  
- [HerbShare](https://herbshare.org/) (J.A. Guzmán, D.M. White, and J. Cavender-Bares)  
- Bring your own!

We hope workshop participants will bring data to work with, questions that may be answered about functional traits, and/or ML tools for quantifying functional traits from images. We will provide computing resources and, upon request, preload popular public datasets for easy access during the workshop. Example datasets include [Herbarium19,](https://www.kaggle.com/c/herbarium-2019-fgvc6) [PlantCLEF](https://www.kaggle.com/competitions/plantclef-2025/), [NEON Tree Crowns](https://zenodo.org/records/3765872), or other [OpenForest Datasets](https://github.com/RolnickLab/OpenForest/blob/main/OpenForest.csv). Please look for the question in the application to suggest public datasets of interest. Most of all, we ask participants to bring their enthusiasm for and curiosity about applying AI/ML tools to explore questions relating to morphological traits and biological discovery!

## Goals & Desired Outcomes

We aim to facilitate outcomes that address the potential of and need for plant image workflows to extract information about traits, interactions, taxonomy, and biodiversity estimates including (but not limited to\!) the following:

- Modality-based prototype workflows (e.g., for herbarium, hyperspectral, remote sensing images) for extracting morphological traits from images that are reproducible, follow FAIR guiding principles, and are understandable/usable by biologists and computer scientists.  
- Prototype tools for trait and interaction extraction from images.  
- Tutorials on adapting tools to data, designed for ecologists.  
- A peer-reviewed publication describing best practices for extracting morphological traits from images and feeding into AI/ML.  
- Publication of [FAIR](https://www.go-fair.org/fair-principles/)/[CARE](https://www.gida-global.org/care)-adhering and ML-ready datasets of extracted trait or interaction information, derived from already published images, that are suitable for answering ecological questions. Ideally, these would be paired with a model or benchmarking results.

## Scope

We are keeping the scope of possible projects focused on plant imagery exploration and analysis, such as trait extraction, interactions, and biodiversity assessments to maximize the limited time of the workshop. We expect this event to connect people with ecological and biodiversity science-focused goals. For instance biologists interested in asking biological questions with AI/ML tools or AI/ML researchers interested in ecological or evolutionary questions for which to develop algorithms and models.

We generally expect datasets curated at or for the event, as well as tools or methods developed, to satisfy [FAIR principles](https://www.go-fair.org/fair-principles/), and where applicable also [CARE principles](https://doi.org/10.1038/s41597-021-00892-0). All data that is used for this event ***must already be published*** under an [open content](https://en.wikipedia.org/wiki/Free_content) license. Data curated at the event must be published by the end.

## Date and Location

The event will be held August 17-20, 2026, at the Hyatt House Columbus/OSU, in Columbus, OH.

## Who should participate

We aim to bring together a diverse group of people, including AI and ML researchers and practitioners, ecologists and biologists, as well as related domain scientists, information scientists, software developers, ontologists, and data or specimen curators. Members of organizations in the US National Science Foundation (NSF) funded Harnessing the Data Revolution ([HDR](https://www.nsf.gov/cise/harnessingdata/)) ecosystem are particularly encouraged to consider applying, including members of their respective computer science and domain science stakeholder communities. For example, for the Imageomics Institute, this includes computer scientists working on AI/ML for images, text, and video, and biologists interested in using image and video data at large scale to answer trait-based biological questions.

In general, people encouraged to consider applying include (but are not limited to!) the following:

- AI/ML experts and researchers, particularly those in computer vision (CV), interested in collaboratively advancing tools, infrastructure, and data products that are domain science-enabling.  
- Ecologists (and related domain scientists such as biodiversity and environmental scientists) who are interdisciplinary-minded and ideally have already used or are planning to use image data in their research, and/or have some familiarity with applying ML and computer vision for ecological research questions.  
- Researchers who are excited about fusing diverse data sources—imagery, text, sensor readings, and more—into multimodal ML models that can make predictions once thought impossible.  
- Software engineers or programmers with skills requisite for AI/ML (Python and applicable libraries, etc.), data wrangling/management (SQL, Pandas, R, etc.) who are interested in developing automated ML workflows, tools and infrastructure.  
- Data engineers with experience and expertise in creating FAIR data products suitable for AI/ML applications.  
- Graduate students and postdocs looking for an opportunity to develop their skills in interdisciplinary research at the intersection of AI/ML and domain science (ecology, biodiversity and environmental science).  
- Advanced undergraduates in computational biology, computer science (ML/CV), math, or data analytics with demonstrated interest in interdisciplinary research.

Everyone participating in the event must adhere to its [Code of Conduct](https://github.com/Imageomics/FloraPalooza-2026/blob/main/CODE_OF_CONDUCT.md).

## About the Imageomics Institute

The [Imageomics Institute](https://imageomics.org/) is funded by the US National Science Foundation (NSF) within its [Harnessing the Data Revolution (HDR) Institute](https://new.nsf.gov/funding/opportunities/harnessing-data-revolution-institutes-data/505828/nsf21-519/solicitation) program. The Institute has been focused on creating a collaborative research, training, and community-facing environment for extracting known and discovering new biological traits from images, with the necessary infrastructure for cyber, information, and model development. The Institute will advance Imageomics-enabled biology, accelerate innovations in machine learning, and create digital resources for the researchers and practitioners in biology, data science, and machine learning, as well as the broader scientific community. It will further interdisciplinary training and education, and engage the broader public in the scientific process. Accomplishing these tasks will provide unique insights and enable biological discovery over a wide range of informative organismal attributes—some not yet comprehended or studied—and across multiple scales of biological organization from individuals to species.

## Organizing Team

- [Elizabeth Campolongo](https://egrace479.github.io/) (The Ohio State University & Imageomics Institute)  
- [Jeannine Cavender-Bares](https://www.oeb.harvard.edu/people/jeannine-cavender-bares) (Harvard University Herbaria)  
- [Jianyang Gu](https://vimar-gu.github.io/) (The Ohio State University & Imageomics Institute)  
- [Hilmar Lapp](https://orcid.org/0000-0001-9107-0714) (Neuromatch & Imageomics Institute)  
- [Dylan MacArthur-Waltz](https://sites.google.com/maine.edu/record-lab/home?authuser=0) (University of Maine, Department of Wildlife, Fisheries, and Conservation Biology)   
- [William Weaver](https://williamweaver.xyz/) (University of Michigan, Michigan Institute for Data and AI in Society)  
- Diane Boghrat (The Ohio State University & Imageomics Institute)  
- Brittany Fonner (The Ohio State University & Imageomics Institute)
