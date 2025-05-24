# Literatures and Resources
A list of resources for getting started, blogs, newsletters, and podcasts, python tools, and databases for materials informatics. If you think there's a great resource missing, read the contribution guide and open a pull request or create an issue and I'll be happy to add it. This list is in no way comprehensive, it's simply a collection of resources I've found extremely helpful in my own research. This field is rapidly evolving and I've tried to focus on materials-specific resources, rather than cover the constantly changing cutting-edge of data science tools. I have included some foundational tools that are prerequisites for most of the other resources. There is also a list of materials informatics research groups. This list is inspired by Pat Walters' excellent list of resources for cheminformatics. Chemistry, the so-called "central science," is in many ways leading the charge when it comes to applying machine learning to science, so it doesn't hurt to be familiar with the progress in the field.

# Getting started
What is materials informatics? - This blog post from Citrine does a really nice job summarizing what materials informatics is and why it's worth doing.

# Machine Learning for Materials Scientists: 
An Introductory Guide toward Best Practices - There are too many reviews and perspectives on ML for materials science to count; I like this one because it includes example code and notebooks and plenty of helpful tables with references to databases and work in the field. If you read this paper and work through the examples, you'll have a solid foundation for doing materials informatics research.

# Matminer Tutorials -
The Matminer tutorial series uses interactive Jupyter notebooks to walk through the basic steps of materials informatics: data retrieval, featurization, machine learning, and data evaluation/visualization.

# Materials Project Workshop - 
This fantastic three day workshop offered annually by the wonderful folks at the Materials Project covers introductions to Python, Jupyter notebooks for data science, MongoDB for databases, and using the full stack of Materials Project software for computational materials science. There are lecture videos and interactive notebooks accompanying each lesson. Appropriate for anyone with an interest in computational materials, no need to be a Python wizard.

# Materials Informatics Lectures by Taylor Sparks - 
If you enjoy a good lecture, this online course is an amazing resource in an area where many universities do not yet have great courses developed. If you aren't comfortable with Python or need a refresher, Taylor has another great online course on Python Programming for Materials Engineers.

# Blogs, newsletters, and podcasts

Citrine Blog - There are some good posts here about challenges in the field, as well as specific case studies and white papers

Citrine Newsletters - A great way to stay up to date with papers in the field, the weekly research newsletter includes reader contributions of relevant papers and job openings.

Citrine Podcast - There are only a few episodes, but they include some great insights from folks in academia, industry, and even government.

Materialism Podcast - Materialism is a great podcast about general topics in materials science. Check out episode #20 for an informatics focus. Caveat that I strongly disagree with their intro 😅

ML4Sci - A newsletter that covers all applications of machine learning to applied science, including materials.

# Python Tools
Jupyter - Project Jupyter is the de facto standard for doing data science in an interactive, web-based interface. A common theme among these resources is that the best ones will always be accompanied by example code and Jupyter notebooks. Advantages: great for rapid iteration and experimentation (science). Disadvantages: not great for reproducibility, deployment in production, and robustness (engineering).

nbQA - A fantastic tool for cleaning up messy notebooks. Appreciated by anyone who is trying to understand your prototyping work, including your future self.

Deepnote - There are lots of new notebook environments popping up trying to address the disadvantages of Jupyter. Deepnote allows real-time collaboration and runs in the cloud. Google Colab, CoCalc, and Paperspace Gradient are other cloud-based notebook environments for ML.

Gradio - Lightweight application for building and sharing web interfaces to your ML models.

Computational materials workflow libraries
Pymatgen - All-purpose code for representing materials structures, interfacing with electronic structure codes, and analyzing materials data.

MP Infrastructure - Built on pymatgen, custodian, fireworks, and atomate, these codes enable automated, high-throughput calculations and analysis of materials.

AiiDA - Automated computational materials science workflows with robust tracking of data provenance.

ASE - Simulation environment for materials and molecules.

pytopomat - Workflows for high-throughput band topology calculations.

# Materials informatics libraries
Matminer and Automatminer - Automated generation of descriptors from material structures and compositions, as well as ML model training and evaluation.

PUMML - Semi-supervised materials machine learning (e.g. to predict synthetic accessibility)

MAML - All-purpose library for materials ML.

MEGNet - Graph networks for molecules and crystals.

DeepChem - Deep learning for the sciences. Support for PyTorch and TensorFlow, focused on chemical and life sciences with increasing support for materials science.

# Visualization, data sharing and discovery
Crystal Toolkit - Interactive web app for visualizing materials science data.

SUMO - Plotting tools for electronic structure calculation data.

MPContribs - Contribute theoretical and experimental datasets directly to the Materials Project, sharing your data with 100,000+ users and making it easily accessible through the web interface and API.

MDF - A way to publish your own materials datasets with an API for accessing them.

Matscholar - AI assistant using natural language processing to parse materials science literature.

# Databases
Materials Project - Over 130,000 inorganic compounds and 49,000 molecules and counting, with calculated phase diagrams, structural, thermodynamic, electronic, magnetic, and topological properties.

OQMD - 815,000+ materials with calculated thermodynamic and structural properties.

ICSD - 210,000+ inorganic crystal structures from literature. Requires a subscription.

JARVIS - Includes calculated materials properties, 2D materials, and tools for ML and high-throughput tight-binding.

C2DB - Calculated properties for thousands of 2D materials.

AFLOW - Millions of materials and calculated properties, focusing on alloys.

Materials Cloud - A collection of databases curated by the Marzari group at EPFL.

NOMAD - Repository for materials data following the FAIR principles.

Citrination - Contributed and curated datasets from Citrine.

MPDS - An initiative to scrape data from literature and make it machine readable.
