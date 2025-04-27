# What is Software Architecture?

> **Software architecture** is the set of **significant design decisions** about how a system is organized to **promote desired quality attributes** and other important properties.

\- Michael Keeling, _Design It!_

## How to Think About Architecture

- **Structure of a System**:  
   Just like a house has an underlying structure (foundation, walls, rooms), software architecture defines the structure on which all software components are built.
- **Key Early Decisions**:  
   Architecture includes decisions you _wish you could get right_ early, because they are hard to change later.
- **Things Hard to Change**:  
   Anything considered difficult to modify once built is part of the architecture.
- **The Important Stuff**:  
   Architecture covers the "important stuff" — the parts that have the biggest impact on the system's success and flexibility.

## A Clearer Definition

Michael Keeling's definition (from _Design It!_) ties it all together:

- **Set of Decisions**: Architecture is about the _decisions_ made.
- **Significant**: These decisions are **important** because they impact qualities like performance, scalability, and maintainability.
- **Organization**: It defines _how_ the system is structured.
- **Promotes Qualities**: It aims to support desired outcomes like scalability, performance, security, etc.

## The Four Dimensions of Architecture

To fully describe a software architecture, we can think in terms of these **four dimensions**:

### 1. Architectural Style

- Defines the **overall structure and pattern**.
- Examples:
  - Micro-services
  - Layered architecture
  - Monolithic
  - Event-driven  
     _(Like a character's "class" in a video game — warrior, mage, archer.)_

### 2. Characteristics

- Also called **quality attributes**.
- Examples:
  - Performance
  - Scalability
  - Reliability
  - Deploy-ability
  - Agility  
     _(Like a character's "stats" — strength, speed, dexterity.)_

> You can't maximize all characteristics at once. Trade-offs must be made depending on priorities or architectural style.

### 3. Architectural Decisions

- **Rules and guidelines** made during design.
- Examples:
  - How services communicate (e.g., REST, gRPC)
  - Database choices
  - Message protocols  
     _(Like a character's "background story" — the experiences and beliefs that define them.)_

### 4. Logical Components

- The **actual building blocks** of the system.
- Examples:
  - Modules
  - Classes
  - Functions
  - UI components  
     _(Like a character's "skills" — what they can actually do.)_

## References

- **Article**: [Who Needs an Architect?](https://martinfowler.com/ieeeSoftware/whoNeedsArchitect.pdf) by Martin Fowler
- **Book**: _Design It!_ by Michael Keeling
- **Book**: _Head First Software Architecture_ by Raju Gandhi, Mark Richards, Neal Ford
