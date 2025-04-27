# What is Frontend Architecture?

## Definition

Frontend architecture is the discipline of designing and organizing the client-side of web applications, focusing on the structure, components, and interactions that create the user experience.

### Core Definition

Frontend architecture can be defined as:

- A set of decisions about how we organize our frontend layer to promote higher quality attributes
- The important frontend stuff (in Ralph Johnson's terms)

## The Frontend-Backend Spectrum

The traditional clear separation between frontend and backend has evolved into a spectrum:

### Frontend Side

- HTML
- CSS
- Client-side JavaScript

### Middle Ground

- Modern frameworks with client and server components (Next.js, Nuxt)
- React Server Components
- Hybrid approaches

### Backend Side

- Databases
- APIs
- Infrastructure (e.g., Kubernetes)

## Architecture Dimensions

Frontend architecture can be analyzed through four key dimensions:

| Architecture Dimension      | Example 1: Micro-Frontends                                                          | Example 2: Monolithic React Server Components                       |
| --------------------------- | ----------------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| **Style**                   | Micro-Frontends                                                                     | Monolithic React Server Components                                  |
| **Quality Attributes**      | • Scalability<br>• Deployability<br>• Maintainability                               | • Performance<br>• Agility<br>• Reliability                         |
| **Architectural Decisions** | • Global state sharing with signals<br>• Client-side composition of micro-frontends | • State sharing with store<br>• Data mutation using server actions  |
| **Building Blocks**         | • Models<br>• Collections<br>• Views<br>• Templates<br>• Classes                    | • Client components<br>• Server components<br>• Hooks<br>• Services |

## Key Insight

The same application can be built using different architectures that may look identical to end users but have fundamentally different underlying structures. The choice of architecture depends on various factors including team size, project requirements, and desired quality attributes.
