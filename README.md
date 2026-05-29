# GizmoNomical – Bret Elliott | Software Developer

Software developer specializing in multiplayer systems, backend logic, and performance-optimized solutions.

Experience designing and maintaining systems for live multiplayer environments, with a strong emphasis on reliability, synchronization, performance, and real-time state-driven behavior.

---

## Core Focus Areas
- Client-server architecture
- Multiplayer synchronization
- Event-driven systems
- State persistence and data handling
- Performance optimization

---

## Featured Projects & Systems

### GN84-WNDR Core Platform (Private / Proprietary)
Primary backend and systems platform powering a live multiplayer server environment, supporting gameplay infrastructure, economy systems, admin tooling, and performance-optimized real-time systems.

Actively used and tested in a live multiplayer server with persistent player progression, economy systems, and world state.

**Key Features:**
- Client-server synchronization with server-authoritative state handling  
- Lock-state and timeout logic to manage shared multiplayer interactions  
- Persistent world and object data using ModData  
- Recycler system with anti-desync safeguards and concurrency protection  
- Persistent audio emitter system with recovery and distance-based cleanup  
- Dual-currency economy with bank balances, itemized currency, and shop workflows  
- Money Clip system for deposits, withdrawals, balance tracking, and stack consolidation  
- Admin tools for economy control, token management, and configuration workflows  

**Technical Highlights:**
- Designed for reliability and consistency in live multiplayer environments  
- Event-driven architecture to reduce unnecessary polling and improve performance  
- Solves synchronization, ownership, and shared-state challenges across clients  
- Integrates gameplay systems, UI workflows, economy infrastructure, and admin tooling into a unified core platform  

*Core implementation remains private due to proprietary server systems.*

---

### Taxov (C# Application / SaaS Platform)
Large-scale C# application and SaaS platform focused on reverse-engineering and modeling Escape from Tarkov market tax systems.

**Key Features:**
- Reverse engineered complex in-game tax calculations into accurate, reusable logic models  
- Developed interactive tools for pricing analysis and decision-making workflows  
- Designed and implemented backend logic for calculation processing and data handling  
- Integrated Stripe-based authentication and recurring subscription systems  
- Built user-facing interfaces using HTML, CSS, and dynamic content rendering  

**Technical Highlights:**
- Combines backend computation, business logic, and user interface design into a cohesive application  
- Implements real-world payment workflows and subscription management  
- Handles dynamic input, calculation pipelines, and result visualization  
- Designed for practical use with active users, supporting real-time pricing decisions and live data interaction  

Demonstrates full application development, backend logic design, data processing, and real-world system integration.

---

### Zombie Whisperer (Real-Time Admin Control System)
Advanced real-time control tool designed for live multiplayer environments, enabling precise manipulation of zombie behavior and world state.

Includes unique capability to locate and interact with reanimated player entities, solving a previously unaddressed gameplay limitation in multiplayer environments.

**Key Features:**
- Radius-based zombie attraction, spawning, and removal using mouse-targeted input  
- Adjustable power and range controls for fine-tuned interaction  
- Real-time visual feedback with annotated area markers  
- One-click cell-wide zombie cleanup functionality  
- Ability to locate, track, and interact with reanimated player entities in the world  
- Optional command-based control to summon reanimated player entities directly to the admin  

**Technical Highlights:**
- Custom UI built using ISPanel with interactive controls and state toggling  
- Client-server command integration for multiplayer-safe execution  
- Dynamic world interaction using spatial calculations and grid targeting  
- Event-driven input handling with minimal performance overhead  

Demonstrates real-time system control, multiplayer command architecture, and advanced entity interaction.

---

### Blood Moon System (Dynamic Event Engine)
State-driven real-time event system designed to deliver scalable, high-intensity gameplay experiences.

**Key Features:**
- Finite State Machine managing event lifecycle (growth, peak, eye, decay, etc.)  
- Dynamic environment manipulation including lighting, fog, rain, wind, and desaturation  
- Intensity scaling based on moon phase and configurable parameters  
- Real-time player and AI interaction (panic, stress, zombie attraction)  
- Fully adjustable event progression, visibility, and tick-rate controls  
- Integrated messaging and audio systems for immersive feedback  

**Technical Highlights:**
- State-driven architecture managing complex event transitions and progression  
- Runtime environment control using climate and lighting systems  
- Event-driven updates with configurable scaling and overrides  
- Custom admin UI for live control, monitoring, and system interaction  

Demonstrates state machine design, real-time system orchestration, and dynamic environment simulation, while creating high-impact emergent gameplay through controlled environmental and behavioral systems.

*Core implementation remains private due to proprietary server systems.*

---

### Fatigue & Sleep Deprivation System (GN84-FDB)
Custom gameplay system designed to track player behavior and enforce fatigue mechanics over time.

**Key Features:**
- Tracks time since last sleep and applies progressive penalties  
- Implements escalating debuffs and health impacts  
- Integrates with existing gameplay systems while preventing exploitation  
- Supports recovery logic based on sleep duration  

Demonstrates state tracking, progression systems, and rule-based logic design.

---

### Admin Tools & Debug Systems (GN84-WDT)
Utility systems designed to improve server administration and debugging workflows.

**Key Features:**
- Provides targeted debug functionality without requiring full debug mode  
- Enhances administrative control and visibility  
- Streamlines troubleshooting and system interaction  

Demonstrates tooling development, workflow optimization, and system-level visibility design.

---

## Concepts Demonstrated
- Systems Design
- Client-Server Architecture
- Multiplayer Synchronization
- Concurrency Control
- Event-Driven Design
- State Persistence
- Real-Time Systems

## Development Approach
- Focus on event-driven design to minimize performance overhead  
- Prefer server-authoritative systems for consistency and synchronization  
- Emphasis on scalable, reusable architecture and maintainable systems  

---

## Tech Stack
Lua (Kahlua), C#, Java, Git

---

## Contact
LinkedIn: https://www.linkedin.com/in/bret-elliott-192b913a7
