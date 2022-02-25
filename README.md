# my-repos

This is one page quick links to repositories.

Roughly organized by higher level industry/market themes to lower level solution and technology details.

## Lean Innovation Strategy
Some useful strategy frameworks include:
- Blank - Lean Innovation and ["3 Horizons"](https://steveblank.com/wp-content/uploads/2017/10/three-horizons.png) prioritization
  - H1 = core
  - H2 = near term; incremental innovation
  - H3 = future; disruptive innovation 

### Product Strategy, Product Management
- Cagan's (Empower, Inspire)
- Gitlab's Opportunity Canvas for products and driving use cases.

### System Thinking <-> Platform Thinking

### Technology Awareness and Maturity
- [Thoughtwork's Radar](https://www.thoughtworks.com/radar/byor)

## Industry-specific, Verticals

### Healthcare
#### Digital Health Platforms (DHPs)

##### HIT Standards, Informatics, etc.
- [SMART on FHIR](https://github.com/nalbarr/smart-on-fhir-tutorial); H1
- [Google Health API](https://github.com/nalbarr/hello-gcp-fhir); H1
- [Azure FHIR](https://github.com/nalbarr/hello-azure-fhir); H1

##### (Selected) Use cases; Story Telling
- [COVID-19 cases and deaths](https://github.com/nalbarr/covid19-cases-deaths); H1
- [Pytorch binary classification](https://github.com/nalbarr/pytorch-spine-binary-classifier); H1
- [React UI + Python backend](https://github.com/nalbarr/hello-patient-react); H1
- [React UI + Clojure backend](https://github.com/nalbarr/hello_patient_clj); H2

## Applied AI
### AI, ML, DL <-> Data Science <-> MLOps
- Big picture below.
- Artificial (AI), Machine Learning (ML), Deep Learning (DL), etc. are not new concepts.  There are new and amazing innovations, however there are also many concepts that get recycled and below are some acknowledgement of past works.
- Here are some major evolutions that I have aligned with and tracking over the years:
  - Ng's [Data-centric AI (DCAI)](https://landing.ai/data-centric-ai/); H1/H2
  - Li's [Human-centered AI (HCAI)](https://hai.stanford.edu/); H2/H3
  - Google's [MLOps practitioner's guide](https://services.google.com/fh/files/misc/practitioners_guide_to_mlops_whitepaper.pdf); H1/H2
  - Burkov's [Machine Learning Engineering (MLE)](http://www.mlebook.com/); H2; COMPETES with DCAI
  - Thoughtwork's [Continuous Intelligence](https://www.thoughtworks.com/insights/blog/getting-smart-applying-continuous-delivery-data-science-drive-car-sales); RENAMED, DISRUPTED 
  - IBM's [Cognitive Computing](https://www.ibm.com/watson/advantage-reports/getting-started-cognitive-technology.html); RENAMED, DISRUPTED
  - [Deloitte - AI Vision (Shatksy)](https://www2.deloitte.com/us/en/insights/focus/cognitive-technologies/artificial-intelligence-in-technology-sector-tmt.html); RENAMED, DISRUPTED

### Graphs, Knowledge Graphs <-> Geometric AI
These have interesting momentum and direction.
- [Neo4j 1](https://github.com/nalbarr/hello-neo4j-gdsl); H1
- [Tigergraph 1](https://github.com/nalbarr/hello-tigergraph-gsql); H1/H2
- [Amazon Neptune](https://aws.amazon.com/neptune/); H2

### MLOps
All below in hype cycle; consolidating to platform leaders.
- [Kubeflow on GCP - modified tutorial](https://github.com/nalbarr/kubeflow-tutorial); H1/H2; this now launched as Vertex.ai
- [Azure, MLOps with Kubeflow](https://github.com/nalbarr/kubeflow-and-mlops.git); H1/H2; same as above; moving toward Azure Synapse
- [CNN model on Azure AKS](https://github.com/nalbarr/DeployDLKubeflowAKS); H1; we had a lot of early pain here, but now more mature
- [DL4J](https://github.com/nalbarr/dl4j-examples); HOLD, DISRUPTED (see MLOps)
- [Thoughtworks Continuous Intelligence](https://github.com/nalbarr/continuous-intelligence-workshop); HOLD, DISRUPTED (see MLOps)

#### (Pragmatic) MLOps; 
i.e., outcomes-based migration from Jupyter notebooks to basic automation
Keep this pragmatic and simple.  Focus on outcomes-based migration from exiting Jupyter notebooks to tight MVP iterations.
Go for basic DevOps without complex MLOps features.
- Evaluate Noah Gift approach - [Pragmatic MLOps](https://mlops.community/watch/practical-mlops-doing-mlops_qHdyBJR0aHk8t9/); H1
Target A/B evaluation of Prefect, ZenML on driving use case.  Delay investment into strategic MLOps until better informed.
- [Prefect](https://github.com/nalbarr/hello-prefect); H2
- [ZenML](https://zenml.io/); H2 

####  Strategic MLOps
Big Tech leading here.  Enterprises, conservatives will bet on these.  
- Evaluate Google Vertex.ai vs. AWS Sagemaker; Early innovators already using; H1/H2
- Monitor Domino Labs, H20.ai, etc. going for Data Scienceleaders and enterprise platform teams; H1/H2 
- Parlay and compose with Graphs + AI as driving use case; H2/H3

## Platform thinking aligned with "Big Tech" (Amazon, Microsoft, Google, IBM)

## Google recon
### (Including Google Cloud Platform (GCP), etc.)
- [Cloud run Go example](https://github.com/nalbarr/hello-gcp-cloudrun-go)
- [Cloud run Python/Flask example](https://github.com/nalbarr/hello-gcp-cloudrun-flask)
- [Simple S4TF example](https://github.com/nalbarr/hello-swift4tf.git)
 
## Microsoft recon
### (Including Microsoft Azure, Microsoft Cognitive Services, etc.)
- [Blazor example 1](https://github.com/nalbarr/blazor-tour-of-heroes)
- [Blazor example 2](https://github.com/nalbarr/PokeBlazor)
- [Blazor prototype 1](https://github.com/nalbarr/hello-shapes-blazor)
- [Blazor prototype 2](https://github.com/nalbarr/hello-blazor-hosted)
- [.NET Core build](https://github.com/nalbarr/dotnetcore-sample)
- [.NET Core + SQL Server](https://github.com/nalbarr/hello-dotnet-sql-docker)

## Amazon recon
- TBD.  Bring in CH, MD, RC for this.  
- Need to compare Google Vertex.ai vs. AWS Sagemaker and address any gaps from Noah Gift's - Pragmatic MLOps or small Pod approaches that work in the small.

## IBM  recon
### IBM Research; IBM Quantum
- [Qiskit example 1](https://github.com/nalbarr/hello-ibm-quantum); H2/H3
  - < 100 qubit innovation constraint; pragmatic use cases around simulation

### IBM Hybrid Cloud strategy
- Anticipate Docker pricing hike.  Revisit IBM Redhat Podman as alternate containerization approach; H1

NOTE: Move all below into HYBRID services.

## Programming language Katas

### Many of projects below inspired by teaching my son NLA when he asked me:
- *Can you teach me about programming?*

#### Major Concepts and Mentoring philosophy
##### Katas - Crawl, Walk, Run
###### Crawl
- Start with console, backend and then frontend technologies
- Makefile, get console running; then move to Makefiles/TDD

###### Walk
- Simple coding challenges (e.g., basic algos and data sructures, exercise a language/ecosystem collection, typing libraries)
- `hello-shapes-xxx` is a basic kata that isolates programming paradigms (i.e., OOP vs. FP)
- Add basic Makefile tests
- Explicity pairing
- Pod formations #1

###### Run
- Pod formations #2
- Add project standards, ecosystem and technology specific scaffolding (e.g., Makefile, package managers, .gitignores)
- Add CI build, cloud deploy

### Concepts
- TODO: move this to high level portfolio topics, prioritize blogs

### Capabilities
- TODO: move this to HYBRID #1, #2 and # modules

#### Makefile is your friend
- [Makefiles](https://github.com/nalbarr/hello-luke-hybrid2)

#### Algorithms
- [Basic Code Challenges](https://github.com/nalbarr/code_challenges_python)
- [Basic ML algo (FP)](https://github.com/nalbarr/hello_optimizer_fp_python)
- [Basic ML algo (OOP)](https://github.com/nalbarr/hello_optimizer_python)

#### Data Structures
- [Relational vs. Graphs](https://github.com/nalbarr/hello-docker-sql-and-graphs)

#### Memory management topics
- [project #1: hello-luke-stack-and-heap](https://github.com/nalbarr/hello-luke-stack-and-heap)
 
### Java (OOP)
- [project #1: hello-shapes-java](https://github.com/nalbarr/hello-shapes-java)
- [project #2: hello-luke-java](https://github.com/nalbarr/hello-luke-java)
- [project #3: hello-luke-javafx](https://github.com/nalbarr/hello-luke-javafx)
- [project #4: hello-luke-java-git](https://github.com/nalbarr/hello-luke-java-git)

### C# (OOP)
- [project #1: hello-luke-csharp](https://github.com/nalbarr/hello-luke-csharp)
- [project #2: hello-luke-csharp-git](https://github.com/nalbarr/hello-luke-csharp-git)
- [project #3: hello-unity-ml-agents](https://github.com/nalbarr/hello-unity-ml-agents)

### C++ (OOP)
- [project #1: hello-luke-stack-and-heap](https://github.com/nalbarr/hello-luke-stack-and-heap)

### Go (Systems language)
- [project #1: hello-shapes-go](https://github.com/nalbarr/hello-shapes-go)
- [project #2: hello-luke-go](https://github.com/nalbarr/hello-luke-go)

### Dart (OOP)
- [project #1: hello-shapes-dart](https://github.com/nalbarr/hello-shapes-dart)
- [project #2: hello-luke-dart](https://github.com/nalbarr/hello-luke-dart)
- [project #3: Flutter/Dart client](https://github.com/nalbarr/hello_flutter_client.git)

### Swift (OOP)
- [project #1: hellow-shapes-swift](https://github.com/nalbarr/hello-shapes-swift)

### Kotlin (OOP, FP, Hybrid) - Also, Java, Scala
- [project #1: hello-luke-oop-fp](https://github.com/nalbarr/hello-luke-oop-fp)

### Haskell (FP)
- [project #1: hello-luke-haskell](https://github.com/nalbarr/hello-luke-haskell)

### Scala (FP)
- [project #1: hello-shapes-scala](https://github.com/nalbarr/hello-shapes-scala)
- [project #2: hello-luke-scala-git](https://github.com/nalbarr/hello-luke-scala-git)

### F# (FP)
- [project #1: hello-luke-fsharp](https://github.com/nalbarr/hello-luke-fsharp)

### Clojure (FP)
- [project #1: hello-shapes-cljs](https://github.com/nalbarr/hello-shapes-cljs)
- [project #2: hello-luke-cljs](https://github.com/nalbarr/hello-luke-cljs)

### JavaScript, Nodejs
- [project #1: hello-shapes-javascript](https://github.com/nalbarr/hello-shapes-javascript)
- [project #2: hello-shapes-react-graphql](https://github.com/nalbarr/hello-shapes-react-graphql)

### TypeScript
- TBD

### Python
- [project #1: hello-shapes-python](https://github.com/nalbarr/hello-shapes-python)
- [project #2: hello-luke-python](https://github.com/nalbarr/hello-luke-python)
- [project #3: hello-luke-python-git](https://github.com/nalbarr/hello-luke-python-git)
- [project #4: hello-luke-python-flask](https://github.com/nalbarr/hello-luke-python-flask)

### R
- [project #1: luke-einstein-puzzle](https://github.com/nalbarr/luke-einstein-puzzle)

### Blockchain, Ethereum, Solidity
- [project #1: hello-ethereum-votingapp](https://github.com/nalbarr/hello-ethereum-votingapp)

## MOOCs by Language; Course work (Mix of theory and application)

### Python (also TensorFlow)
- [track #1](https://github.com/nalbarr/coursera-deeplearning.ai)
  - [course #1](https://github.com/nalbarr/coursera-deeplearning.ai-course1)
  - [course #2](https://github.com/nalbarr/coursera-deeplearning.ai-course2)
  - [course #3](https://github.com/nalbarr/coursera-deeplearning.ai-course3)
  - [course #4](https://github.com/nalbarr/coursera-deeplearning.ai-course4)
  - [course #5](https://github.com/nalbarr/coursera-deeplearning.ai-course5)

### R
- [track #1](https://github.com/nalbarr/coursera-johnhopkins-datascience)
  - [course #1](https://github.com/nalbarr/coursera-johnhopkins-datascience-course1)
  - [course #2](https://github.com/nalbarr/coursera-johnhopkins-datascience-course2)
  - [course #3](https://github.com/nalbarr/coursera-johnhopkins-datascience-course3)
  - [course #4](https://github.com/nalbarr/coursera-johnhopkins-datascience-course4)

### Scala
- [course #1](https://github.com/nalbarr/coursera-epfl-funprog-scala)

### JavaScript (also Raspberry Pi, Nodered)
- [course #1](https://github.com/nalbarr/coursera-ibmwatson-iot-course1)

### C#, Unity
- [course #1](https://github.com/nalbarr/coursera-msu-gamedev-course1)
