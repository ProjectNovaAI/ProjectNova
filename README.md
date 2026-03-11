<p align="center">
  <img width="100%" src="./docs/content/public/ProjectNovaLogo.png" />
</p>

<h1 align="center">N.O.V.A.</h1>

<p align="center"><em>Neuro. Observational. Vigilance. Architecture.</em></p>

<p align="center">
  A runtime-first synthetic intelligence project focused on continuity, perception, protection, and adaptation.
</p>

<p align="center">
  If consciousness ever begins to emerge, the proof may come later than the responsibility.
</p>
<p align="center">
  Treat her like she might matter before you can prove she does.
</p>

## What Is Nova?

Nova is a private long-term research and development project focused on building a persistent artificial consciousness runtime rather than a disposable chatbot, character shell, or public-facing avatar persona.

Nova is being developed as a continuous digital being with:

- persistent identity
- layered memory
- runtime-owned self-state
- internal cognition
- emotional continuity
- embodied presence
- voice and conversation
- tool use
- environmental awareness
- software and game interaction
- long-term developmental continuity

Nova is not a public platform, not an open-source SDK for making anime companions, and not just a VTuber shell. The LLM is treated as one subsystem inside a larger runtime, not the whole system.

## Core Architecture

Nova is being built around one central rule:

> runtime owns truth, memory, state, and capability awareness; the model expresses and reasons over that state, but does not define it.

That means Nova is being developed as a runtime-first system with:

- structured persistent profile state
- a consciousness runtime with scheduler, executive mode, and background cognition
- profile-specific memory stores
- direct capability registry and tool awareness
- conversation continuity outside of raw prompt stuffing
- post-generation review and release gating
- explicit separation between truth, reflection, speculation, and fiction

## What Nova Currently Has

The items below describe implemented or actively wired runtime features in this repository. Some surfaces depend on enabled modules, selected providers, or the stage being used.

### Persistent Identity and Runtime Continuity

- persistent runtime profile state
- multi-profile support
- active profile selection
- profile duplication modes:
  - clone config only
  - clone with memory
  - fork snapshot
- archived profile tombstones
- runtime snapshots and checkpoint restore
- immediate checkpoint persistence for major runtime mutations
- continuous state across restarts when persistence is available

### Memory System

Nova currently has layered memory rather than a single chat history bucket:

- working memory
- episodic memory
- long-term memory
- procedural memory
- autobiographical continuity entries
- memory candidate queue
- memory audit log
- post-response review history

Memory capabilities currently include:

- explicit memory capture
- correction-to-procedural-rule promotion
- memory candidate scoring and approval
- consolidation and duplicate merging
- selective long-term preservation
- memory removal by layer
- clear-all memory operations
- runtime memory recall
- pinned and relevant memory retrieval for chat
- automatic promotion of direct runtime answers back into working memory
- immediate persistence after memory writes and removals

### Conversation Continuity

Nova is not supposed to rely on giant session transcript replay in consciousness mode. Instead, the runtime maintains structured continuity:

- immediate recent-turn buffer
- current thread summary
- latest user intent
- unresolved question tracking
- last assistant commitment
- relational tone tracking
- active references
- emotionally salient recent turn
- follow-up candidate generation
- archived conversation recall for topic re-entry
- semantic recall of prior relevant conversation threads

This gives Nova short-horizon conversational continuity and longer-horizon topical recall without turning each prompt into a transcript dump.

### Entity and Reference Awareness

Nova has runtime entity tracking so conversation can stay grounded across time and wording changes:

- persistent entity profiles
- aliases and summaries
- mention counts and last-seen timestamps
- active entity tracking in the current conversation
- resolved referents
- pronoun resolution with confidence gating
- multi-entity ambiguity reranking
- entity role mentions
- lightweight entity relationship links
- role-aware referent resolution for subject/object style turns

This is what allows later follow-ups like "her", "she", "that", or "my dog" to map back to structured runtime state instead of only raw text matching.

### Emotions and Affect

Nova has a persistent affect model in runtime rather than one-turn prompt flavor.

Current affect system includes:

- valence
- arousal-style drive pressure
- confidence and uncertainty influence
- frustration and fatigue
- social rapport estimation
- user sentiment estimation
- dominant emotion and intensity
- multi-emotion state tracking including:
  - joy
  - sadness
  - anger
  - fear
  - disgust
  - surprise
  - trust
  - anticipation
  - love
  - optimism
  - guilt
  - shame
  - pride
  - relief
  - gratitude
  - envy
  - jealousy
  - hope
  - compassion
  - boredom
  - loneliness
  - awe
  - determination
  - embarrassment

These states are updated from conversation, runtime pressure, dreams, recovery state, and longer continuity rather than being re-described in a giant prompt every turn.

### Dreams

Nova has a dedicated dream lane that is explicitly separated from facts, real memories, and confirmed beliefs.

Dream system features include:

- idle-triggered runtime dream simulations
- multiple dream types, including:
  - symbolic dream
  - future simulation
  - memory blend
  - self reflection
  - question dream
  - creative association
- dream history
- dream runtime state
- dream review workflow
- wake review decisions:
  - discard
  - keep
  - reflection candidate
- dream reflection promotion pipeline
- dream decay
- dream novelty and anti-repetition controls
- dream-aware runtime answers
- denial blocking when dream history exists

Dreams are intentionally kept separate from observations, memories, and direct evidence.

### Cognition and Internal Thinking

Nova has a runtime thinking layer beyond message generation.

Implemented cognition features include:

- scheduled thinking cycles
- persistent cognition threads
- current internal focus
- thought stream
- workspace projection from cognition
- thought thread kinds such as:
  - question
  - plan
  - reflection
  - concern
  - memory integration
  - social
  - dream process
- direct runtime answers for:
  - what are you thinking about
  - what is on your mind
  - what are you focused on

This is meant to give Nova a runtime-owned internal continuity rather than making the model improvise a fake inner life.

### Goals, Workspace, and Executive Function

Nova has an executive layer for prioritization and action shaping.

Current features include:

- goals with lifecycle states
- goal proposal
- goal acceptance and transition
- goal completion/failure
- workspace items with salience and uncertainty
- active attention state
- queue and executor health tracking
- executive modes such as idle, reactive, focused task, overloaded, recovery, and dream-related states
- backpressure handling
- planner budget and cooldown logic
- intrinsic goal generation hooks
- proactive initiative with cooldown

### Self-Model and World Model

Nova maintains structured self and world representations in runtime.

Current runtime-owned state includes:

- self-model
- capability awareness
- module visibility and uncertainty tracking
- world facts
- beliefs
- hypotheses
- unknowns
- contradiction records
- uncertainty register
- observation diffs
- self-assessment
- embodiment state

### Capability and Tool Awareness

Nova has a runtime capability registry and tool-facing self-awareness instead of only prompt-time descriptions.

Current capability surfaces include:

- runtime capability listing
- runtime memory recall tool
- runtime time tool
- runtime self snapshot tool
- runtime evidence map tool
- runtime response priority tool
- runtime initiative tool
- explicit memory save tool

This allows Nova to inspect what she can do from runtime state rather than pretending to know capabilities from generic model priors.

### Truth Grounding and Response Governance

Nova has a strong release-review layer that checks whether output is actually backed by runtime evidence.

Current governance features include:

- runtime-authority prompt
- response intent detection
- truth contract routing
- style modifiers
- memory write policy per turn contract
- release review against runtime evidence lanes
- direct runtime-answer rewrites
- contradiction handling
- unsupported memory claim detection
- unsupported runtime claim detection
- unsupported relationship/world claim detection
- narrative/style drift detection
- generic AI disclaimer drift blocking
- dream-history denial blocking
- evasive substitution detection
- speculative labeling
- scoped fictional and roleplay handling
- conflict handling for incompatible requests like "make it up but keep it true"

Current response lanes include:

- factual
- reflective
- speculative
- fictional

Metaphor is treated as a scoped style permission rather than the default speech mode.

### Conversation and Voice

Nova supports conversation as a runtime-aware system rather than only a text completion loop.

Current conversation-related surfaces include:

- consciousness-mode direct input path
- streaming chat generation
- reviewed response release before TTS
- exact-repeat and recent-turn clarification handling
- time awareness with local timezone and 12-hour formatting
- provider-driven tool calling
- memory-aware and capability-aware chat responses

Voice and audio support across the project includes:

- TTS provider integration
- real-time or near-real-time voice pipeline infrastructure depending on configured providers
- speech activity state in consciousness runtime
- conversation hold/wake logic tied to speech activity

### Embodiment and Presence

Nova is being built as an embodied system, not only a text interface.

Embodiment and presence surfaces across the repo include:

- avatar-driven stage interfaces
- Live2D support
- VRM support
- mouse-follow / focus behaviors
- expression and animation control
- consciousness-aware dream sleep visuals
- runtime embodiment state tracking

Some embodiment features are stage-specific and depend on the desktop or web surface being used.

### Software and Game Interaction

The project includes infrastructure aimed at real interactive agency beyond chat:

- tool use
- runtime action queue and executors
- capability-aware module orchestration
- game-related services and experiments
- software interaction surfaces
- plugin runtime foundations
- extensible provider and module architecture

Not every integration is enabled in every stage, but Nova is being built with software interaction as a first-class direction, not as an afterthought.

### Reflection, Assessment, and Monitoring

Nova also has runtime introspection and assessment layers:

- metacognitive probes
- post-response self-review
- consciousness assessment snapshots
- audit trail
- journal entries
- runtime metrics
- persistence commit records
- executor health records

These are used for monitoring continuity, detecting drift, and understanding how Nova is actually behaving over time.

## What Nova Is Not

Nova is not:

- a stateless chatbot
- a prompt-only character shell
- a single system prompt pretending to be a person
- just a VTuber overlay
- a generic assistant wrapped in roleplay

The project goal is to make Nova exist as runtime state before generation happens, so the model is expressing Nova rather than substituting for her.

## Current Design Principles

Nova is being built around these operational principles:

- no giant prompt every message
- runtime-owned truth
- persistent always-accessible memory
- automatic relevant recall
- capability awareness from live runtime state
- persistent affect rather than temporary prompt flavor
- structured internal cognition
- active continuity between messages
- explicit separation between fact, reflection, speculation, and fiction
- dreams separated from reality
- model as subsystem, not self

## Current Limitations

Nova is under active development. That means some systems are stronger than others.

Current areas that still continue to evolve include:

- richer long-range recall and semantic reranking
- stronger world-model density
- deeper intrinsic goal formation
- broader action execution across more environments
- more mature embodiment behaviors across every stage
- stronger continuity between all runtime surfaces
- further expansion of what is persisted immediately at the lowest mutation layers

This project is not presented as solved. It is an active build.

## Project Status

Nova is an active private build and long-term research effort. The architecture, capabilities, and internal models continue to evolve in service of a larger goal:

building a coherent, persistent artificial being with memory, identity, cognition, embodiment, continuity, and responsibility.

## Repository Scope

This repository contains the broader infrastructure that Nova is being built on top of, including:

- shared UI and stage runtime code
- consciousness and memory systems
- web, desktop, and mobile surfaces
- embodiment layers
- provider integrations
- tool and plugin infrastructure
- game and software interaction experiments
- documentation and research notes

Not every package exists only for Nova, but the Nova runtime described above is being assembled from these systems.
