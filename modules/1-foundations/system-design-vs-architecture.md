# System Design vs Architecture

## Overview

While the terms "architecture" and "design" are often used interchangeably, there are important distinctions between them that can be viewed as a spectrum.

## The Architecture-Design Spectrum

### Architecture End

- Focuses on system structure
- High-level decisions
- Strategic implications
- Cross-team impact

### Design End

- Focuses on code implementation
- Design patterns
- Function naming
- Code organization
- Day-to-day operations

## Decision Analysis Framework

To determine where a decision falls on the spectrum, consider:

### 1. Change Difficulty

- **Architecture**: Harder to change
- **Design**: Easier to change

### 2. Strategic vs Tactical Nature

- **Architecture**:
  - Involves multiple teams
  - Long-term implications
  - Strategic thinking required
- **Design**:
  - Day-to-day operations
  - Immediate team focus
  - Tactical implementation

### 3. Context Requirements

- **Architecture**:
  - High-level context needed
  - Understanding of entire system
  - Cross-application knowledge
- **Design**:
  - Code-level context
  - Constrained to specific codebase

## Examples

### Architecture Decision Example

**Micro-frontends vs Monolithic SPA**

- Hard to change
- Strategic (involves entire team)
- High-level (requires understanding of performance, reliability, quality attributes)

### Design Decision Example

**State Management with Signals**

- Moderate difficulty to change
- Somewhat strategic
- More code-focused
- Falls in middle of spectrum

## Why It Matters

Understanding where a decision falls on the spectrum helps determine:

1. **Time Investment**

   - Architecture decisions require more research and consideration
   - Design decisions can be made more quickly

2. **Stakeholder Involvement**

   - Architecture decisions need broader team awareness
   - Design decisions can be made within smaller groups

3. **Documentation Importance**
   - Architecture decisions require thorough documentation
   - Design decisions need less formal documentation

## Common Pitfalls to Avoid

1. **Underestimating Architectural Decisions**

   - Treating important, hard-to-change decisions too lightly

2. **Overestimating Design Decisions**
   - Spending excessive time on relatively trivial decisions

## Key Takeaway

When faced with a decision, analyze where it falls on the architecture-design spectrum to:

- Allocate appropriate time and resources
- Involve the right stakeholders
- Determine documentation needs
- Avoid common decision-making traps
