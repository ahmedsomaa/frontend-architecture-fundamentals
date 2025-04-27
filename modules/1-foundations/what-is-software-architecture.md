# What is Software Architecture?

> **Software Architecture** is "the set of significant design decisions about how a system is organized to promote desired quality attributes and other properties."

\- (Michael Keeling, _Design It!_)

## Core Concepts

### 1. Understanding Architecture Through Analogies

#### House Architecture Analogy

- Similar to how a house has a foundation, walls, and rooms
- Software architecture defines the underlying structure for all components
- Provides the framework on which all software components are built

#### Video Game Character Analogy

- Helps visualize the four dimensions of architecture
- Each dimension maps to a character attribute:
  - Class → Architectural Style
  - Stats → Characteristics
  - Background Story → Architectural Decisions
  - Skills → Logical Components

### 2. Evolution of Architecture Definitions

1. **Initial Definition**

   - Focus on system structure
   - Similar to physical architecture

2. **Decision-Based Definition**

   - "Decisions you wish you could get right early in a project"
   - Emphasizes the importance of early architectural decisions
   - Highlights the difficulty of changing these decisions later

3. **"Important Stuff" Definition**

   - Architecture is about the "important stuff"
   - Raises questions about what constitutes "important"

4. **Comprehensive Definition** (Michael Keeling)
   - Combines all previous definitions
   - Focuses on:
     - Significant decisions
     - System organization
     - Quality attributes
     - Other properties

## The Four Dimensions of Architecture

### 1. Architectural Style

- **Definition:** Overall structure and pattern of the system
- **Examples:**
  - Microservices
  - Layered architecture
  - Monolithic
  - Event-driven
- **Analogy:** Character's class (e.g., warrior, mage, archer)

### 2. Characteristics (Quality Attributes)

- **Definition:** System properties that determine its capabilities
- **Examples:**
  - Performance
  - Scalability
  - Reliability
  - Deployability
  - Agility
- **Key Point:** Cannot maximize all characteristics simultaneously
- **Analogy:** Character's stats (strength, speed, dexterity)

### 3. Architectural Decisions

- **Definition:** Rules and guidelines for system implementation
- **Examples:**
  - Service communication protocols (REST, gRPC)
  - Database choices
  - Message protocols
- **Purpose:** Helps teams navigate implementation complexities
- **Analogy:** Character's background story

### 4. Logical Components

- **Definition:** Actual building blocks of the system
- **Examples:**
  - Modules
  - UI components
  - Classes
  - Functions
  - Design systems
- **Analogy:** Character's skills and abilities

## Key Takeaways

1. Architecture is fundamentally about **decisions** that are:

   - Significant
   - Hard to change
   - Impact system organization
   - Promote desired qualities

2. Complete architecture description requires all four dimensions:

   - Style sets the overall pattern
   - Characteristics define system capabilities
   - Decisions provide implementation guidance
   - Components are the actual building blocks

3. Trade-offs are inherent in architecture:
   - Cannot optimize all characteristics simultaneously
   - Must prioritize based on system requirements

## References

- **Article**: [Who Needs an Architect?](https://martinfowler.com/ieeeSoftware/whoNeedsArchitect.pdf) by Martin Fowler
- **Book**: _Design It!_ by Michael Keeling
- **Book**: _Head First Software Architecture_ by Raju Gandhi, Mark Richards, Neal Ford
