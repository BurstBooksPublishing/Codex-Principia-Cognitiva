# Codex Principia Cognitiva

### Cover
<img src="covers/Front2.png" alt="Book Cover" width="300" style="max-width: 100%; height: auto; border-radius: 6px; box-shadow: 0 3px 8px rgba(0,0,0,0.1);"/>

### Repository Structure
- `covers/`: Book cover images
- `blurbs/`: Promotional blurbs
- `infographics/`: Marketing visuals
- `source_code/`: Code samples
- `manuscript/`: Drafts and format.txt for TOC
- `marketing/`: Ads and press releases
- `additional_resources/`: Extras

View the live site at [burstbookspublishing.github.io/codex-principia-cognitiva](https://burstbookspublishing.github.io/codex-principia-cognitiva/)
---

## Chapter 1. Why We Need Cosmic Cognitive Science
### Section 1. The Parochialism Problem
- Psychology studies less than 0.00001% of possible minds
- The WEIRD bias and replication crisis
- Why human-centric research has failed

### Section 2. The Alien Cognitive Scientist Test
- Defining the test: would aliens recognize this principle?
- Substrate-independence as the gold standard
- Examples of passing vs. failing the test

### Section 3. Foundations of Cosmic Cognition
- Cognition as physical computation under constraints
- Information theory as the parent discipline
- Thermodynamics and embodiment
- Optimization theory and control systems

### Section 4. How to Read This Book
- The three-tier hierarchy explained
- Mathematical notation and conventions
- Cross-references and disputed territory flags

---
## Chapter 2. Cosmic Laws of Cognition
### Section 1. Shannon's Channel Capacity Theorem
- Statement of the theorem: C = B log₂(1 + S/N)
- Derivation from mutual information maximization
- Physical inevitability: why no system can exceed this
- Evidence from biological systems: retinal ganglion cells
- Evidence from artificial systems: wireless communication
- Violation costs: catastrophic error accumulation

### Section 2. Nyquist-Shannon Sampling Theorem
- Statement: sample rate ≥ 2× highest frequency
- Mathematical proof via Fourier analysis
- Aliasing as inevitable consequence of undersampling
- Housefly compound eye implementation
- Human visual system temporal sampling
- Robotic vision failures from undersampling

### Section 3. Weber-Fechner and Stevens Power Laws
- Weber's Law: ΔI/I = constant
- Fechner's integration: S = k log(I)
- Stevens' generalization: S = kI^α
- Information-theoretic derivation from efficient coding
- Evidence from bacterial chemotaxis
- Evidence from insect sensory systems
- Evidence from octopus chromatophore control
- Evidence from human psychophysics
- Robotic sensor implementations

### Section 4. Fitts's Law
- Statement: MT = a + b log₂(2D/W)
- Information-theoretic derivation
- Why this is inevitable for any aimed movement
- Evidence from human motor control
- Evidence from elephant trunk reaching
- Evidence from octopus arm targeting
- Evidence from industrial robotics
- Zero confirmed violations in 70 years

### Section 5. Hick-Hyman Law
- Statement: RT = a + b log₂(n + 1)
- Derivation from entropy of choice set
- Evidence from honeybee foraging decisions
- Evidence from rat maze navigation
- Evidence from human reaction time studies
- Relationship to information transmission limits

### Section 6. Predictive Coding and Free-Energy Principle
- Variational free energy definition
- Mathematical proof of optimality for hierarchical inference
- Connection to minimum description length
- Evidence from E. coli chemotaxis
- Evidence from insect olfactory processing
- Evidence from rodent hippocampus
- Evidence from human visual cortex

### Section 7. Bayesian Optimal Cue Integration
- Maximum likelihood estimation for Gaussian cues
- Inverse-variance weighting as optimal solution
- Evidence from bacterial multisensory fusion
- Evidence from human vision-touch integration
- Evidence from robotic sensor fusion
- Suboptimality costs: degraded performance metrics

### Section 8. Signal Detection Theory
- d-prime and criterion as decision variables
- ROC curves and optimal operating points
- Derivation from Neyman-Pearson lemma
- Evidence across sensory modalities
- Evidence from predator-prey detection systems
- Applications to artificial detection systems

### Section 9. Rate-Distortion Theory
- Optimal compression-fidelity tradeoff
- Information bottleneck formulation
- Retinal implementation of rate-distortion curves
- Efficient coding hypothesis (Barlow)
- Sparse coding as compression strategy

### Section 10. Marginal Value Theorem
- Charnov's patch-leaving rule
- Mathematical derivation from optimal foraging theory
- Evidence from bumblebee foraging
- Evidence from bird foraging patterns
- Evidence from mammalian resource exploitation
- Evidence from human hunter-gatherer behavior
- Implementation in optimal RL agents

### Section 11. Optimal Stopping: The 37% Rule
- Secretary problem formulation
- Mathematical proof of 1/e optimality
- Generalization to unknown horizons
- Evidence from animal mate choice
- Evidence from nest site selection
- Human approximations under time pressure

---
## Chapter 3. Cosmic Heuristics
### Section 1. Recognition Heuristic
- Inference rule: recognized > unrecognized
- Ecological rationality conditions
- Evidence from human city-size judgments
- Evidence from artificial agent object search
- When recognition heuristic fails

### Section 2. Take-the-Best
- Algorithm: order cues by validity, stop at first discriminator
- Less-is-more effect: mathematical proof
- Comparison to weighted linear models
- Evidence from 20 real-world datasets
- When take-the-best outperforms regression

### Section 3. Gaze Heuristic Family
- Constant bearing angle for collision detection
- Constant optical angle for interception
- Geometric proof of optimality
- Evidence from dragonfly prey capture
- Evidence from baseball outfielders
- Evidence from naval collision avoidance

### Section 4. Satisficing (Simon)
- Aspiration-level algorithm
- Optimality under search costs and uncertainty
- Evidence from animal habitat selection
- Evidence from human decision making
- Comparison to maximization strategies

### Section 5. Equipartition (1/n Rule)
- Equal division when no differentiating information
- Proof of minimax optimality
- Evidence from portfolio allocation
- Evidence from resource distribution
- When 1/n beats optimized strategies

### Section 6. Tallying (Unit-Weight Linear Model)
- Count positive cues, ignore weights
- Robustness to estimation error
- Evidence from medical diagnosis
- Evidence from personnel selection
- Comparison to optimally weighted models

### Section 7. Tit-for-Tat
- Algorithm: cooperate first, then copy opponent
- Evolutionary stability in iterated prisoner's dilemma
- Evidence from bacterial cooperation
- Evidence from primate reciprocity
- Robustness to noise and defection

### Section 8. Lévy Flight Foraging
- Power-law step distribution: P(L) ~ L^(-μ)
- Optimal exponent μ ≈ 2 for sparse resources
- Evidence from jellyfish movement
- Evidence from albatross foraging
- Evidence from mammalian search patterns
- Evidence from human hunter-gatherers
- Controversy: composite Brownian vs. true Lévy

### Section 9. Recency Weighting
- Exponential vs. hyperbolic temporal discounting
- Bayes-optimality in non-stationary environments
- Evidence from animal learning curves
- Evidence from human probability estimation
- Adaptive learning rate modulation

---
## Chapter 4. Cosmic Rules
### Section 1. Speed-Accuracy Tradeoff
- Optimal decision time balances delay vs. error costs
- Drift-diffusion model derivation
- Race model alternative formulation
- Evidence from insect decision making
- Evidence from human perceptual judgments
- Evidence from artificial sequential sampling

### Section 2. Exploration-Exploitation Tradeoff
- Multi-armed bandit problem formulation
- Thompson sampling as Bayes-optimal solution
- UCB1 and other provably optimal algorithms
- Softmax and ε-greedy as biological approximations
- Evidence from animal foraging
- Evidence from human learning tasks
- Implementation in RL agents

### Section 3. No-Free-Lunch Theorems
- Wolpert-Macready statement and proof
- Implication: specialization is mandatory
- Why Earth-like priors are not cheating
- Relationship to universal compression limits
- Consequences for cognitive architecture

### Section 4. Prediction-Error Priority
- Surprisal as information content
- Only unexpected events teach
- Evidence from attentional orienting
- Evidence from learning-rate modulation
- Implementation in prediction-error neurons

### Section 5. Diminishing Marginal Returns
- Value of information falls as 1/n or faster
- Proof from Bayesian updating
- Evidence from sampling behavior
- Evidence from information search tasks
- Connection to satisficing

### Section 6. Information Foraging Theory
- Patch-leaving when local rate < global average
- Connection to marginal value theorem
- Evidence from web browsing
- Evidence from library search
- Evidence from scientific literature foraging

---
## Chapter 5. Cosmic Constants and Physical Constraints
### Section 1. Landauer's Limit
- Minimum energy per bit erased: kT ln 2
- Thermodynamic proof
- Why biological computation is 10^6× above minimum
- Implications for neural sparsity
- Implications for memory decay

### Section 2. Serial Processing Bottleneck
- 1–50 bits/second central limit
- Evidence from human dual-task interference
- Evidence from monkey electrophysiology
- Evidence from artificial global workspace models
- Connection to attentional blink
- Connection to change blindness

### Section 3. Power-Law Forgetting
- Retention ∝ t^(-β) with β ≈ 0.3–0.5
- Derivation from superposed exponentials
- Evidence from human memory studies
- Evidence from animal conditioning
- Evidence from artificial neural networks
- Connection to spacing effect

### Section 4. Power-Law Practice
- Performance ∝ n^α with α ≈ 0.3–0.6
- Log-log linearity across domains
- Evidence from skill acquisition
- Evidence from perceptual learning
- Neural efficiency explanations

### Section 5. Critical Branching (σ ≈ 1)
- Criticality maximizes information capacity
- Neural avalanche distributions
- Evidence from cultured neurons
- Evidence from cortical recordings
- Evidence from reservoir computing
- Subcritical and supercritical failure modes

### Section 6. Kleiber's 3/4 Metabolic Scaling
- Metabolic rate ∝ M^0.75
- Geometric derivation from network constraints
- Implications for brain energy costs
- Evidence across species
- Cognitive consequences of scaling

### Section 7. Small-World Network Structure
- Path length ≈ ln(N) in efficient networks
- Clustering coefficient requirements
- Evidence from neural connectivity
- Evidence from social networks
- Evidence from artificial architectures

---
## Chapter 6. Biological Instantiations of Cosmic Laws
### Section 1. Rescorla-Wagner as Gradient Descent
- ΔV = αβ(λ - ΣV) equation
- Identity with delta rule and backpropagation
- Evidence from honeybee color learning
- Evidence from Aplysia gill withdrawal
- Evidence from rat nucleus accumbens
- Evidence from human fMRI signals
- Rediscovery in deep RL 2022–2025

### Section 2. Temporal-Difference Learning and Dopamine
- TD(λ) algorithm formulation
- Dopamine as biological TD-error signal
- 10–100 Hz phasic burst = positive error
- Pause/dip = negative error
- Evidence from zebrafish
- Evidence from songbirds
- Evidence from primates
- Optogenetic replacement experiments

### Section 3. Blocking and Overshadowing
- Kamin blocking paradigm (1968)
- Mathematical inevitability from zero prediction error
- Evidence from snails
- Evidence from honeybees
- Evidence from fish
- Evidence from rodents
- Evidence from humans
- Blocking in deep neural networks

### Section 4. Successor Representation
- Separation of transition and reward
- SR(λ) formulation
- Hippocampal place cells as successor features
- Orbitofrontal cortex value storage
- Independent discovery in RL (Dayan 1993)
- Evidence from revaluation studies

### Section 5. Pavlovian-Instrumental Transfer
- General vs. specific PIT effects
- Nucleus accumbens core/shell distinction
- Evidence from Aplysia
- Evidence from rodents
- Evidence from primates
- Evidence from humans

### Section 6. Peak Shift and Super-Stimulus
- Strongest response beyond trained stimulus
- Gradient interaction explanation
- Evidence from pigeon discrimination
- Evidence from insect foraging
- Human aesthetic preferences
- Exploitation in advertising and art

---
## Chapter 7. Biological Heuristics
### Section 1. Win-Stay, Lose-Shift
- WSLS algorithm definition
- Optimality in slowly changing environments
- Evidence from bumblebee foraging
- Evidence from rat patch choice
- Evidence from starling food selection
- Human probability matching connection

### Section 2. Fluency Heuristic
- Processing ease as validity cue
- Neural efficiency hypothesis
- Evidence from honeybee flower preferences
- Evidence from human truth judgments
- Evidence from aesthetic ratings
- Mere exposure effect connection

### Section 3. Affect Heuristic
- Valence-first evaluation architecture
- 100–300 ms advantage over analytic processing
- Amygdala response conservation across vertebrates
- Evidence from fish threat detection
- Evidence from mammalian fear conditioning
- Human risk perception biases

### Section 4. Shepard's Universal Law of Generalization
- exp(-cd^p) formulation
- p=1 (city-block) vs. p=2 (Euclidean) metrics
- Evidence from pigeons
- Evidence from rats
- Evidence from humans
- Evidence from neural network models
- Most replicated law in psychology

### Section 5. Frequency-Based Probability
- Natural frequency superiority
- Evidence from human Bayesian reasoning
- Evidence from animal probability matching
- Evolutionary argument for frequency formats
- Implications for probability education

### Section 6. One-Reason Decision Making
- Single-cue stopping rules
- Evidence from bumblebees choosing flowers
- Evidence from great tits choosing sites
- Time pressure as ecological driver
- Connection to take-the-best

---
## Chapter 8. Biological Rules and Constraints
### Section 1. Feature-Positive Effect
- Presence > absence learning speed
- Infinite set problem for absences
- Evidence from pigeons
- Evidence from rats
- Evidence from rabbits
- Evidence from humans

### Section 2. Latent Inhibition
- Pre-exposure retards conditioning
- "Already predicted" mechanism
- Evidence from sea slugs
- Evidence from rodents
- Evidence from humans
- Clinical implications (schizophrenia)

### Section 3. Pearce-Hall Attention Modulation
- Associability α ∝ |λ - V|
- Surprise-driven attention
- Evidence from rabbit conditioning
- Evidence from rat learning
- Evidence from human attention
- Contrast with Mackintosh model

### Section 4. Context-Renewal Effects
- ABA and ABC renewal paradigms
- Extinction as context-gated inhibition
- Evidence from sea slugs
- Evidence from rodent fear conditioning
- Evidence from human anxiety
- Hippocampal and prefrontal mechanisms

### Section 5. Rational Volatility Tracking
- Learning rate increases with environmental change
- Optimal inference under non-stationarity
- Evidence from fruit flies
- Evidence from honeybees
- Evidence from fish
- Evidence from rodents
- Evidence from humans

### Section 6. Overshadowing and Relative Validity
- Strong cue blocks weak cue
- Compound vs. elemental training
- Evidence from goldfish
- Evidence from pigeons
- Evidence from humans
- Computational accounts

---
## Chapter 9. Biological Constants and Scalings
### Section 1. Subitizing Limit 3–4 Items
- Instant enumeration without counting
- Evidence from human adults
- Evidence from human infants
- Evidence from rhesus monkeys
- Evidence from crows
- Evidence from guppies
- Neural capacity explanations

### Section 2. Attentional Blink 200–500 ms
- Temporal window for second target detection
- Evidence from human RSVP tasks
- Evidence from macaque electrophysiology
- N2pc and P3 suppression mechanisms
- Individual differences and training

### Section 3. Phasic Dopamine Burst Range
- 10–100 Hz firing rate
- Conservation from lamprey to primate
- VTA and SNc characterization
- Tonic vs. phasic modes
- Computational role of burst timing

### Section 4. Optimal Learning Rate Window
- 0.01–0.2 sweet spot
- Too low: cannot track change
- Too high: catastrophic forgetting
- Evidence from zebra finch reinforcement
- Evidence from rodent conditioning
- Evidence from human learning
- Evidence from deep RL stability

### Section 5. Metabolic Cost of Neural Activity
- ~10^9 ATP per cortical spike
- Energy budget constraints
- Sparsity as energy optimization
- Comparison across nervous systems
- Octopus vertical lobe costs
- Mammalian cortex costs

### Section 6. Immediate Serial Recall Span
- 7±2 before chunking (Miller 1956)
- Evidence from verbal span tasks
- Evidence from spatial span tasks
- Evidence across species
- Working memory capacity connection

---
## Chapter 10. Where Humans Deviate from Cosmic Optimality
### Section 1. Availability Heuristic as Bug
- Ease of recall vs. true frequency
- Cosmic optimum: full Bayesian integration
- Mass media amplification failures
- Terrorism probability overestimation
- When availability works (small samples)

### Section 2. Anchoring and Insufficient Adjustment
- Arbitrary numbers shift estimates 30–50%
- Violation of irrelevance axioms
- Evidence: SSN digit experiments
- Evidence: wheel of fortune studies
- No animal analogs
- Language-dependent mechanism

### Section 3. Conjunction Fallacy
- P(A∩B) judged > P(A)
- Linda problem classic demonstration
- Direct violation of probability axioms
- Natural frequency format correction
- Language-dependent origins

### Section 4. Base-Rate Neglect
- Representativeness over prior probabilities
- Lawyer/engineer problem
- 95% of humans ignore 90% base rate
- Optimal agents never neglect base rates
- Educational interventions

### Section 5. Scope Insensitivity
- Willingness to pay insensitive to magnitude
- 2,000 vs. 200,000 birds equivalence
- Affect-driven vs. scope-sensitive valuation
- Implications for charitable giving
- Policy consequences

---
## Chapter 11. Cultural Amplification of Suboptimal Patterns
### Section 1. Framing Effects
- Logically equivalent descriptions, different choices
- 90% fat-free vs. 10% fat
- Gain vs. loss frames (Asian disease problem)
- No animal analogs
- Requires symbolic re-description

### Section 2. Narrative Fallacy and Hindsight Bias
- Post-hoc coherent story construction
- "I knew it all along" effect
- Memory distortion mechanisms
- Requires language for counterfactuals
- Financial market illusions

### Section 3. Confirmation Bias
- Seeking evidence that supports belief
- Wason selection task failures
- Echo chamber amplification
- When confirmation is rational
- Optimal hypothesis testing contrast

### Section 4. Mismatch to Post-Agricultural Environments
- Hyperbolic discounting for 30-year lifespans
- Obesity from sugar/fat super-stimuli
- Debt from temporal myopia
- Climate inaction from distant threats
- Peak-shift exploitation mechanisms

### Section 5. Cultural vs. Genetic Evolution Speed
- Norms evolve 10^4–10^6× faster than genes
- Persistent maladaptation consequences
- Prestige bias run amok
- Costly signaling escalation
- Social media novel selection pressures

---
## Chapter 12. Primate-Specific Architectural Kludges
### Section 1. Over-Powered Episodic Simulation
- Hippocampal future scenario generation
- Thousands of simulations per day
- Chronic anxiety and rumination costs
- Corvid and ape future planning comparison
- Human dial turned to 11

### Section 2. Obligate Theory-of-Mind Module
- 9-month-old false belief tracking
- 65% of conversation is social
- Politics and coalition formation
- Reputation markets and gossip
- Cancel culture mechanisms
- No optimal agent would want this

### Section 3. Language-Dependent Cognitive Traps
- Conjunction fallacy disappears in frequencies
- Framing requires symbolic re-description
- Most dual-process biases are linguistic
- Propositional thought side effects
- Non-linguistic reasoning preservation

### Section 4. Loss Aversion and Endowment Effect
- Losses loom 2.0–2.5× larger than gains
- Prospect theory S-curve
- Evidence from capuchin monkeys
- Evidence from chimpanzees
- Human ownership narrative amplification
- Status-quo bias connection

### Section 5. Recursive Mental States Limit
- "I think that you think that I think..."
- Breaks down at 5–6 levels
- Strategic reasoning consequences
- Literary narrative limits
- Computational complexity explanation

### Section 6. Counterfactual Reasoning Scaffolds
- Upward vs. downward counterfactuals
- Regret and relief asymmetries
- Bronze–silver medalist paradox
- Functional vs. normative types
- Language-dependency evidence

---
## Chapter 13. Human-Specific Constants and Scalings
### Section 1. Cowan's Magical Number 4±1
- Pure working memory capacity
- Not 7±2 (Miller conflated with rehearsal)
- Evidence from change detection
- Evidence from multiple object tracking
- Crow and parrot comparison (5–6)
- Verbal rehearsal interference

### Section 2. Dunbar's Layered Social Channels
- 5 intimate / 15 good friends / 50 / 150 / 500
- Neocortex ratio prediction
- Not a cosmic principle
- Evidence from social network analysis
- Evidence from primate group sizes
- Distributed cognition alternative

### Section 3. Phonological Loop Duration
- ~1.8 seconds rehearsal window
- Memory span = words in 1.8s
- Language-specific word length effects
- Articulatory suppression abolishes effect
- Irrelevant for non-speaking minds

### Section 4. Semantic Memory Decay Parameters
- Decades-long retention with power-law decay
- Typicality gradient half-lives
- Rosch prototype structure
- 8–12 year decay for unused concepts
- LTP parameter artifact

### Section 5. Theory-of-Mind Developmental Timeline
- ~9 months: joint attention
- ~18 months: pretend play
- ~4 years: false-belief understanding
- ~6–7 years: recursive mental states
- Cross-cultural robustness
- Autism as counter-example

---
## Chapter 14. Boundary Conditions: Architecture Space and the Limits of Cosmic Generality
### Section 1. The Constraint Set Problem
- Every “cosmic law” is actually “optimal given constraints X, Y, Z”
- Which constraints are truly universal?
- Physical: thermodynamics, speed of light
- Information-theoretic: Shannon limits, compression bounds
- Possibly contingent: embodiment, energy scarcity, sequential processing

### Section 2. Sequential vs. Parallel Processing
- The 1–50 bits/sec serial bottleneck revisited
- Is this cosmic or a biological neuron artifact?
- Global workspace theory assumptions
- Thought experiment: perfectly communicating parallel processors
- Arguments for and against an unavoidable bottleneck
- Verdict: unresolved boundary condition

### Section 3. Discrete vs. Continuous Time
- Most laws assume discrete sampling (Nyquist, RT models)
- Event-driven architectures as alternative
- Asynchronous biological spiking dynamics
- Spiking vs. rate-coded systems
- Do Hick-Hyman and Fitts's laws apply to continuous dynamics?
- Time discretization: fundamental or implementation detail?

### Section 4. Centralized vs. Distributed Control
- Predictive coding assumes hierarchical message passing
- Can flat architectures achieve similar optimality?
- Subsumption architecture (Brooks) as counterexample
- Slime mold computation as biological distributed case
- When centralization is required (credit assignment, coherence)
- Markov blanket perspective on system boundaries

### Section 5. Digital vs. Analog Computation
- Landauer’s limit and bit erasure
- Continuous-valued computation and thermodynamic costs
- Precision–energy tradeoffs in analog systems
- Stochastic computing as intermediate regime
- Whether binary representation is universally privileged

### Section 6. The Embodiment Question
- How many “cosmic laws” assume embodiment?
- Fitts’s law requires spatial movement
- Weber–Fechner requires physical sensor noise
- Marginal Value Theorem requires spatial foraging
- Disembodied theorem provers as boundary cases
- Pure prediction engines (LLMs) as embodiment-free architectures
- Which laws survive pure information processing?

### Section 7. Energy Scarcity as Contingent Factor
- Biological constraints stem from ATP limitations
- Sparsity, forgetting, satisficing as energy-reduction strategies
- Thought experiment: unlimited energy supply
- Would optimal agents still sparsify or forget?
- Finite time vs. infinite energy
- Implications for digital superintelligence

### Section 8. The Alien Cognitive Scientist Test Revisited
- Original test: “Would aliens recognize this principle?”
- Refined test: “Would aliens in situation S recognize this?”
- Specifying constraint sets precisely
- Embodied vs. disembodied applicability examples
- Taxonomy of constraint-dependent generalizability

### Section 9. What Remains Truly Cosmic
- After removing biology, energy limits, embodiment
- Information theory foundations
- Thermodynamic bounds
- Bayes-optimal inference under uncertainty
- Exploration–exploitation structure
- No-Free-Lunch theorems
- The irreducible core: physics + information

### Section 10. Implications for Artificial General Intelligence
- Which principles AI will converge on
- Which constraints AI can escape
- Serial bottleneck: possibly escapable
- Forgetting curves: unnecessary with perfect memory
- Predictive coding: likely convergent for efficiency
- Speed–accuracy tradeoff: persists due to time costs
- Navigating design space across constraint sets

### Section 11. Open Questions and Research Directions
- Which laws generalize how far?
- Formal proofs for boundary conditions
- Empirical tests: build systems that violate assumed constraints
- Comparative AI psychology across architectures
- Deriving optimal solutions given arbitrary constraint sets
- Predicting alien cognition from physics
---
