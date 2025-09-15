# Modelling that simulates or proxy nonhuman perspectives.

## Score 4: Actionable Mechanisms

### IMPLEMENTATION AND METRICS

#### D4C25: Design for Environmental Conservation (Toolkit)

- **Organisation**: None
- **Production Mode**: Single-Expert-Author
- **Author Disciplines**: Design/Engineering

**Evidence:**

This scores 4 because the book provides concrete modelling tools that simulate/proxy nonhuman perspectives (non-human personas, system maps including nonhuman flows, impact canvases, service blueprints involving ecosystem actors), with explicit guidance and examples. 

- Proxy models for nonhumans: “Non-Human Personas… include scientific or common names, habitats, needs, and specific vulnerabilities, helping teams integrate a multispecies approach… team members can be their advocates.” (Ch.7)

- System modelling with nonhuman flows: “Contextual System Map… Stakeholders: people, organizations, or even non-human elements… draw arrows… flows could be labor, information, materials, energy, or money.” (Ch.10)

- Process models and delivery: “Service Delivery Blueprint… map the user journey, frontstage, backstage processes… capture the user experience with emojis… check back to see if your plan effectively addresses the core conservation goals.” (Ch.8)

- Evaluative models and indicators: “Sustainability Radar… Impact Planning Canvas… Unintended Impacts Canvas: Anticipate and address potential ripple effects.” (Ch.9)

---

#### DBIO23: Integrating biodiversity in urban development

- **Organisation**: None
- **Production Mode**: Small-Expert-Team
- **Author Disciplines**: Interdisciplinary

**Evidence:**

This scores 4 because the paper catalogs and recommends specific modelling and decision-support tools (ecological modelling, least-cost corridors, building information systems, indices) that simulate or proxy nonhuman movement, habitat needs, and outcomes, and shows how designers can integrate them into stages of the design process. 

- Modelling tools specified: “ecological modelling tools to predict the long-term impact resulting from development... least-cost modelling and other economic metrics to gauge and balance conflicting priorities... building information systems to visualise and evaluate design opportunities.” (3.2)

- Design-stage integration: “Three key stages of impact include ‘biodiversity assessments’ during the site analysis... evaluation of the potential impact of design alternatives during the conceptual design stage... and ongoing biodiversity monitoring during the post-occupancy stage.” (3.2)

- Framing as proxies for nonhuman needs: The tools are used to “listen” to biodiversity and “transform... literature into parameters to inform design,” enabling urban form to respond to species’ requirements. (3.1.1)

---

### TECHNICAL ASSESSMENTS AND EVIDENCE REVIEWS

#### EUECOLOPES25: ECOlogical Building enveLOPES: A Game-Changing Design Approach for Regenerative Urban Ecosystems

- **Organisation**: Ludwig
- **Production Mode**: Large-Expert-Team
- **Author Disciplines**: Interdisciplinary

**Evidence:**

This scores 4 because simulation/modelling of nonhuman needs is central and is operationalized via plant and animal models, KPI-driven evaluations, and a deployable plugin integrated into existing CAD workflows — providing concrete mechanisms to proxy nonhuman perspectives in design and decision-making.

- Context/synthesis: The project builds ecological models (plant and animal) and integrates them into a CAD front-end to simulate habitat performance on 3D envelopes. 

> McNeel’s new tool seamlessly integrates with an external C++ open-source ecological plant model developed by SAAD to enable ecological simulations of 3D building envelopes... Early testing involving... the joint model of soil, plants, and animals... demonstrated at the Consortium Meeting in Vienna
>
> *(WP3)*


- Context/synthesis: The modelling framework includes an ECOLOPES Voxel & Computational model and an EIM ontology to encode abiotic-biotic interactions and drive generative outputs. 

> The ontology-aided generative computational design process serves the purpose of generating an informed variety of design outputs... ECOLOPES Voxel Model, the EIM Ontologies, and the ECOLOPES Computational Model, with specific focus on their integration and interoperability.
>
> *(WP5)*


- Context/synthesis: Multi-criteria decision-making (MCDM) is used to evaluate trade-offs among species, with stakeholder-specific KPIs including nonhumans; this explicitly simulates nonhuman criteria in negotiation. 

> The hybrid MCDM model was tested... and implemented... for optimization and performance evaluation... KPIs were categorized into three strategic groups: common KPIs... stakeholder-specific KPIs, and spatially-explicit KPIs.
>
> *(WP6)*


- Context/synthesis: The modelling anticipates development over time (succession), projecting nonhuman habitat evolution and persistence. 

> ECOLOPES considers the ecolope as a dynamic system... modelling also includes the projection of ecolope development after initial building completion. This includes ecological succession...
>
> *(Description of expertise and methodology)*


- Context/synthesis: The Knowledge Generation Framework (KGF) and ML pipeline make nonhuman response-prediction scalable and practical for design iterations. 

> KGF... supports the continuous generation of knowledge about the relationships between ecological performance, local-specific environmental aspects and 3D form... integrating advanced analytical tools such as a new machine learning pipeline.
>
> *(WP3)*



---

#### EUECOSERVG2021: Ecosystem services accounting – part III

- **Organisation**: JRC, EC
- **Production Mode**: Large-Expert-Synthesis
- **Author Disciplines**: Interdisciplinary

**Evidence:**

This scores 4 because the report develops and deploys multiple spatial-biophysical models that explicitly represent and proxy nonhuman needs, capacities, and limits (e.g., ecological demand by ecosystems, habitat suitability for species, species hotspot modelling, sustainability thresholds for ecosystem sinks), and it integrates these models into accounting mechanisms and policy-relevant indicators.

- Proxying nonhuman conditions and needs: modelling ecological condition, habitat suitability, and species hotspots to capture species’ requirements and ecosystem state: 

> The biophysical assessment for this ES includes the mapping of suitable ecological conditions (or suitable habitats) required to support species populations and mapping of the presence of species, considered in terms of species hotspots... We focused on birds ... EBBA2 provides ... species distribution models for 219 native species at a resolution of 10 × 10 km2...
>
> *(Chapter 3.2)*


- Ecosystem demand as a formal modelled actor: soil retention demand by ecosystems under worst-case scenarios and potential/actual/unmet flows: 

> All terrestrial ecosystems benefit from the protective role of vegetation... ES D is understood as the need for soil retention by ecosystems to reduce the risk of erosion... it is quantified as the total amount of soil lost when ecosystem protection is not provided; this is calculated using the lowest ecosystem potential...
>
> *(Chapter 4.1.5)*


- Ecosystem absorption thresholds (sustainability) for sinks, linking ecological limits to overuse metrics: 

> As pollutants increase, ES demand may be higher than the ecosystem absorption rate. In this respect, ES actual flow does not provide a measurement of ES overuse; that requires the setting of a sustainability threshold.
>
> *(Chapter 3, summary; detailed in Chapter 5.1.2)*


- Concrete model (GREEN) translating diffuse and point sources, basin/river retention, and denitrification processes into service flows: 

> The geospatial regression equation for European nutrient losses (GREEN) is a statistical model developed to estimate nitrogen and phosphorus fluxes in surface water in large river basins... For every catchment, the model estimates the nitrogen load at the catchment outlet and the nitrogen retention...
>
> *(Chapter 5.1.1)*


- Accounting integration and indicators/outcomes: model outputs drive SUTs, overuse, unmet demand, and missed flows used as policy targets (restoration, pollution reduction): 

> Sustainability analysis is required to assess not only the ES actual flow, but also the ES overuse... changing the sustainability threshold from 2 mgN/l ... to 1 mgN/l ... generates ... a change in the ES overuse from about 22% to 52%.
>
> *(Chapter 5.4.2)*


- Methodological consequences (solutions/problems) across domains: vertical/horizontal double-counting solutions, allocation methods, and boundary conditions—showing how modelling choices resolve technical and governance implications: 

> No ESs can be defined as intermediate by default... We identified two cases, which we named ‘vertical’ and ‘horizontal’... By using soil retention and water purification services as examples, an attempt is made to illustrate that no ES is intermediate by default; rather, this depends on the assessment technique that is used.
>
> *(Chapter 2.4)*


- Negotiation strategies/goals/criteria (higher-rung relevance): explicit criteria like thresholds, habitat–species co-location, and indicators for global society contribution establish goals and tracking metrics: 

> When a service is allocated to global society, this implies the impossibility of geographically mapping the demand... The missed ES monetary flow is that which people would be willing to pay if more ecosystem features ... were available... Information concerning both ES actual and missed flows can help policymakers pursue restoration targets...
>
> *(Chapter 3.5.4)*



---

#### IPBESMODELS46: Report of the IPBES task force on scenarios and models – Nature Futures Scenarios

- **Organisation**: IPBES
- **Production Mode**: Large-Team-With-Workshops/Delphi
- **Author Disciplines**: Interdisciplinary

**Evidence:**

This scores 4 because the report operationalizes modelling to proxy nonhuman perspectives as a core mechanism (Nature Futures Framework), with concrete, actionable steps (narrative-to-indicator-to-model pipeline), proposed case studies, tool integration, governance/behaviour modules, and a community of practice to implement modelling in assessments.

- Foundational mechanism: the NFF explicitly structures modelling around nature’s states and values to represent nonhuman interests: “The task force explain ed how the NFF value perspectives could be translated into illustrative narratives and into quantitative or qualitative scenarios of desirable futures for nature and people. The illustrative narratives stem med from thinking about diverse values and the kind of world that would embody those values.” (III.A)

- Concrete steps and tooling for implementation: “A three -step approach to identifying indicators and variables for building scenarios using the NFF was presented: (1) Developing narratives (future visualisations) to describe each scenario, including social-ecological feedbacks; (2) Capturing these in conceptual diagrams to identify essential indicators…; (3) Building a quantitative and/or qualitative analysis for these features with models, by identifying essential variables, indicators and model types in conceptual diagrams.” (III.C)

- Integration across models to simulate nonhuman perspectives at multiple scales: “Many participants agreed that models and methods already exist that could be used in applying the NFF, and that combining and applying these existing tools presents a ‘low-hanging fruit’… Examples include… ecosystem -based modelling; Integrated Assessment Models adapted to fit the purpose of the NFF; conceptual models… qualitative networks.” (II.b)

- Governance/behaviour modules to capture nonhuman-relevant drivers: “Representing values and their relationship to norms was raised as an important challenge in modelling the NFF… models of institutional behaviour and policy were lacking. Better translation of the relationships between direct and indirect drivers… was deemed necessary, including representation of human behaviour that underpins decisions on resource use.” (IV)

- Outcomes and indicators for assessment use: “Participants suggested multiple options… including engagement with the task force to generate quantitative values across the value perspectives of the Nature Futures Framework and initiating a community of practice where modelling teams interact and share intermediate outcomes… producing publications on how to use the NFF in different contexts, including visualisations such as a flow chart of possible modelling steps.” (Executive summary)

- Negotiation strategies/goals/criteria: “It was considered important to recogn ize trade-offs between value perspectives… explore how optimal actions would differ between two value perspectives, and whether there is a middle ground which would allow the achievement of both… Depending on the trade-offs, there may be different ‘winners’ and ‘losers’ across sectors of society.” (II.c)

---

### POLICY, LEGAL AND GOVERNANCE PROPOSALS

#### UKHYDRO22: Written evidence (LUE0078) to the Land Use in England Committee inquiry

- **Organisation**: UKCEH
- **Production Mode**: Single-Expert-Author
- **Author Disciplines**: STEM

**Evidence:**

This scores 4 because the submission explicitly proposes and evidences the use of process-based biodiversity models, decision-support tools, and species-level simulations to proxy nonhuman perspectives for planning and policy, with concrete mechanisms and applications (ASSET tool, species distribution models, BNG assessment critiques).

- It calls for model-based governance to anticipate ecosystem and species responses to land-use change: 

> Validated models predicting how ecosystem services and biodiversity respond to these changes in land use are required to inform policy decisions.
>
> *(Q8 Response)*


- It specifies an operational tool integrating multiple ecosystem services and biodiversity (birds, pollinators, pest control) for scenario testing: 

> [We] have produced the ASSET decision support tool which allows policy makers and other stakeholders to explore scenarios of land use and land management change on farm incomes, food production, carbon storage, water supply and quality, amenity value of landscapes, and biodiversity (birds, pollinators, pest control).
>
> *(Q8 Response)*


- It recommends process-based species modelling to replace inadequate metrics, directly simulating species’ landscape use: 

> Capturing the effects of land-use changes requires process-based biodiversity models that simulate how species with different habitat requirements and levels of mobility use landscapes. UKCEH has developed such models... validating them against observational datasets...
>
> *(Q7 Response)*


- It links modelling to specific policy contexts (Local Nature Recovery Strategies; Biodiversity Net Gain), detailing practical data challenges, workflow, and governance implications: 

> Local Nature Recovery Strategies... are attempting to incorporate both local habitat mapping data and on-the-ground species records. However, many such partnerships are struggling to account for the observational biases inherent... This requires significant expertise and must be done at national level... UKCEH has extensive experience of this and would be in a position to assist.
>
> *(Q7 Response)*



---

### ROADMAPS AND ACTION PLANS

#### ICNATUREPOS24: Blueprint for a Nature-Positive Adelaide

- **Organisation**: Interdisciplinary Conservation Science Group
- **Production Mode**: Large-Team-With-Workshops/Delphi
- **Author Disciplines**: Interdisciplinary

**Evidence:**

This scores 4 because the report prescribes and applies modelling (PVA and ecological connectivity) to simulate nonhuman movement, persistence, and needs, and uses these outputs to decide design interventions and spatial priorities, providing explicit, actionable methods for representing nonhuman voices in planning.

- The methods are defined and embedded within evaluation: 

> Species persistence: a measure of the probability that a species will persist in an area... Species persistence can be assessed using formal population viability analyses (PVA)... For example, Garrard et al. (2018) used PVA to demonstrate that policies for cat containment would significantly decrease the likelihood of extinction of striped legless lizards...
>
> *(Section 4.2.4 Evaluate BSUD)*


- Connectivity modelling is set out with tools and use to choose locations and linkages: 

> Ecological connectivity: the ability of a species to move through a landscape... Kirk et al. (2021) used ecological connectivity modelling to evaluate BSUD for Superb fairy wrens and Growling grass frog at Fishermans Bend... Planning for connectivity can be as simple as identifying key elements... There are many methods for more formally measuring ecological connectivity such as ‘effective mesh size’ and including free tools such as Circuitscape or Linkage Mapper.
>
> *(Section 4.2.4; Box 1)*


- The report shows these models determining design interventions in a live precinct: 

> Final designs for the precinct development were informed by the effectiveness of different interventions to meet the requirements of four target species: blue-tongued lizards, growling grass frogs, superb fairy wrens and blue banded bees.

 and maps the recommended BSUD actions like green bridges to cross a freeway based on connectivity analyses. (Table 6; Appendix D: Melbourne case study 1)

- It links modelling outputs to indicators and prioritization, creating decision-support: 

> Evaluating BSUD is important for identifying and distinguishing those design solutions that are critical for achieving objectives, monitoring progress and demonstrating success...

 and shows how connectivity mapping in the City of Knox can highlight relative contributions. (Section 4.2.4 Evaluate BSUD; Figure 11)

---

## Score 3: Core Conceptual Device / Implications Explored

### TECHNICAL ASSESSMENTS AND EVIDENCE REVIEWS

#### UNPLANETBOUND22: Thematic study: planetary boundaries

- **Organisation**: UNDRR
- **Production Mode**: Small-Expert-Team
- **Author Disciplines**: Interdisciplinary

**Evidence:**

This scores 3 because the report prescribes the use of Earth System models and biosphysical mapping as proxies for nonhuman processes in decision-making, with explicit support actions for governments, but it stops short of detailed model governance protocols. - It prescribes modelling Earth-system dynamics: 

> Support governments in mapping, monitoring and projecting the biosphysical dimension of planetary boundaries in order to bridge global to local scales. Equally, Earth System models that combine physical climate, vegetation dynamics, ocean biochemistry and hydrological processes can help to understand coupled Earth system processes.
>
> *(Part 2.3.2, Priority for Action 1, Message 1.2)*

 - It calls for open methods and metrics: 

> An open-source method to develop climate risk assessment should be combined with a framework to identify opportunities for key stakeholders... Implement Planetary Boundaries as metrics to monitor environmental health and sustainability progress to aid decision making.
>
> *(Part 2.3.2, Priority for Action 1, Messages 1.2 and 1.4)*

 - It connects modelling to outcomes and targets: 

> Governments are supported in translating planetary boundary processes to the scales needed for implementation... National level transgression... should be used as a starting point to define rigorous national policy targets and disaster risk reduction objectives.
>
> *(Part 2.3.2, Priority for Action 1, Message 1.2)*



---

### SCENARIOS AND FUTURES EXPLORATION

#### PBLNATUREPOS22: Exploring nature-positive pathways: contribution to CBD Post-2020 GBF

- **Organisation**: PBL Netherlands EA
- **Production Mode**: Large-Expert-Team
- **Author Disciplines**: Interdisciplinary

**Evidence:**

This scores 3 because the report employs quantitative, model-based scenario analysis explicitly evaluating biodiversity outcomes (e.g., Mean Species Abundance) and ecosystem trajectories, thereby proxying nonhuman conditions to inform human decisions; it develops implications for policy mixes but does not create a legal institution for nonhuman representation.

- Clear use of model-based analysis to simulate biodiversity states and needs: “A quantitative analysis of solution-oriented scenarios shows that ambitious conservation efforts alone will not be enough to bend the curve of biodiversity loss… the necessity of combining strong conservation with broader sustainability measures.” (p. 17–19)

- Indicators and outcomes for nonhuman systems are discussed and tied to policy choices: “This package of measures includes… dietary changes… and changes in agricultural production… Particularly, consumption change and demand side management are key to avoid trade-offs for nature.” (p. 19)

- Figures and time series (e.g., Mean Species Abundance; biodiversity curves) are used to guide decision strategies and evaluation criteria: “Figure MF.1 Pathways to a nature-positive future… Mean Species Abundance…” (p. 15)

---

## Score 2: Theoretical Treatment

### TECHNICAL ASSESSMENTS AND EVIDENCE REVIEWS

#### EUSTI50: S&T&I for 2050: science, technology and innovation for ecosystem performance – accelerating sustainability transitions

- **Organisation**: EC DG R&I
- **Production Mode**: Large-Team-With-Workshops/Delphi
- **Author Disciplines**: Interdisciplinary

**Evidence:**

This scores 2 because the Data-as-Representation case explores how data and modelling mediate nonhuman entities and proposes implications for STI policy, but it largely frames models for human decision systems rather than explicitly simulating nonhuman perspectives as political actors.

- Context/synthesis followed by supporting quote: 

> In building these alternative scenarios the authors start from the most promising STI directions in Data science & statistics... and differentiate the scenarios based on... the way data is interpreted in relation with reality, specifically as objective, as species‑dependent, or as a molder of reality.
>
> *(4.6.1 Introduction)*


- Context/synthesis followed by supporting quote: 

> Full integration of AI modelling and digital twins in decision‑making... what sealed the fate of the general adoption... was their success – at least according to some proponents – in the prevention and mitigation of several disaster events...
>
> *(4.6.4 To the maxx – Scenario P1)*


- Context/synthesis followed by supporting quote: 

> Biocentric scientists... their proposed models are worldviews, not just simplifications of reality... decisions supported by this new generation of scientists are not so much the operational, immediate ones, but paradigmatic changes in the embedding systems...
>
> *(4.6.4 We, the life – Scenario P3)*



---

#### EUHORIZON23: Horizon Europe strategic plan 2025–2027 analysis

- **Organisation**: European Commission
- **Production Mode**: Large-Expert-Synthesis
- **Author Disciplines**: Interdisciplinary

**Evidence:**

This scores 2 because the document proposes integrated modelling and digital twins (e.g., a Digital Twin of the Ocean) that explicitly combine Earth system, ecosystems and social systems to guide decisions for oceans and biodiversity—thereby proxying nonhuman system needs—yet it remains at the level of R&I agenda-setting without detailed structures for embedding such models as representation mechanisms in governance.

- The ocean and cryosphere section calls for integrated prediction systems joining ecological and social models: 

> Responding to this intertwined crisis necessitates a shared, systemic and multidisciplinary scientific understanding of the problem, and the design of appropriate, fit-for-purpose solutions and innovations... through observation, monitoring, risk-based assessment and forecasting capacities, integrated prediction systems that combine the Earth’s system, ecosystem and social system models, and the sustainable and circular management of natural resources at sea... including the development of a digital twin of the ocean in collaboration with the Destination Earth initiative of the European strategy for data.
>
> *(Section 3.2.2 – Seas, oceans and inland waters)*


- The modelling ambitions are directly linked to protecting ecosystems and improving biodiversity outcomes: 

> Enhancing ecosystems and biodiversity in the ocean and the marine environment is paramount for the integrity and resilience of the Earth’s system and continued delivery of the vital ecosystem services on which humanity depends.
>
> *(Section 3.2.2)*


- While these modelling approaches effectively serve as proxies for nonhuman system dynamics in decision support, the text does not outline institutional roles granting these models formal representational standing in negotiation forums; therefore, it remains practice-oriented but not governance-embedded.

---

## Score 1: Token Acknowledgement

*No sources at this score level*

## Framework Metadata

- **Code**: MTHMODELLING
- **Number**: 4.3.2
- **Type**: Method/Practice
- **Ladder Rung**: Conviviality
- **Topic Cluster**: Negotiation

## Navigation

- [[output.populated-ladder.conviviality.negotiation]] - Back to Negotiation
- [[output.populated-ladder.conviviality]] - Back to Conviviality
- [[output.populated-ladder]] - Back to Framework Analysis
- [[output]] - Back to Analysis Results
- [[root]] - Back to Root

## Tags

#framework #mthmodelling #rung/conviviality
