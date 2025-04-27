# Project Introduction: FullSnack

## Overview

FullSnack is a food delivery web application (similar to Uber Eats) that serves as our case study throughout the course. The project is based on a real-world application to provide practical context and examples.

### Project Purpose

- Illustrate architectural concepts and techniques
- Provide practical examples for exercises
- Demonstrate real-world application of architectural principles
- Serve as a reference for feature implementation

## Project Specification

The complete project specification can be found in the [Project Spec Document](https://github.com/Charca/frontend-architecture-workshop/blob/main/documents/project-spec.md).

### Key Project Details

- **Team Size**: 4 frontend engineers (expected to triple in 12 months)
- **Project Goal**: Design architecture for customer-facing web application
- **Architect's Role**:
  - Gather requirements
  - Design architecture
  - Support team during implementation

## System Context

### System Users

1. **Customer**

   - Purchases food through the app
   - Uses the Customer Web App

2. **Restaurant**

   - Restaurant owners and employees
   - Manages incoming orders
   - Updates menu options

3. **Driver**
   - Delivery personnel
   - Collects and delivers orders

### External Systems

1. **Third-party Payment System**

   - Manages payments and refunds
   - Handles credit card information
   - Example: Stripe

2. **FullSnack Admin System**
   - Managed by a different team
   - Separate from the main system
   - Different purpose and scope

## System Components

### Core Applications

1. **Customer Web App**

   - Web application for customers
   - Used for browsing and ordering food
   - Our primary focus for architecture design

2. **Restaurant Web App**

   - React SPA
   - Order management
   - Menu updates

3. **Driver Mobile App**
   - Native iOS and Android
   - Order collection and delivery

### Backend Services

1. **Core API**

   - Java Spring Boot
   - REST API
   - Gateway to external systems
   - Manages customer data, orders, and menu items

2. **Core Database**

   - MySQL
   - Main data store
   - Accessed by Core API

3. **WebSockets Server**
   - Socket.io
   - Real-time event communication
   - Order status updates
   - Driver location tracking

## Key Features

### Customer Web App Features

- Restaurant and food browsing
- Search and filtering
- Shopping cart functionality
- Order placement and tracking
- Payment processing
- User authentication
- Favorites and recommendations
- Ratings and reviews
