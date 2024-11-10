# Gardening Chat Bot Knowledge Base

This repository contains a PDF document that details the design and development of a Knowledge Base (KB) for a gardening chat bot aimed at helping beginner gardeners. The document provides a structured approach to creating the KB, from understanding the gardening domain to defining logic symbols, constructing logical rules, and performing propositional inference.

## Table of Contents
- [Introduction](#introduction)
- [Step 1: Understanding the Domain](#step-1-understanding-the-domain)
- [Step 2: Defining Logic Symbols](#step-2-defining-logic-symbols)
- [Step 3: Creating the Knowledge Base (KB)](#step-3-creating-the-knowledge-base-kb)
- [Step 4: Propositional Inference on the KB](#step-4-propositional-inference-on-the-kb)
- [Conclusion](#conclusion)

---

### Introduction

This project provides the framework for a chat bot that assists new gardeners by giving advice on essential gardening tasks and troubleshooting common issues. The knowledge base is created using propositional logic, with symbols and rules defined to model gardening principles. This document is intended as a resource for understanding how logical inference can be applied to real-world domains.

### Step 1: Understanding the Domain

In the first step, the gardening domain was explored to identify the core concepts that new gardeners need to understand. These concepts include:

- Soil type and quality
- Watering practices
- Optimal planting times
- Pollination requirements
- Fertilization needs
- Sunlight exposure

In addition, the general rules of gardening were established to determine what factors contribute to a good yield. Common problems faced by gardeners were also identified, such as under-watering, over-watering, lack of pollination, and insufficient fertilization. 

### Step 2: Defining Logic Symbols

The next step involved defining propositional logic symbols to represent the main parameters and conditions relevant to gardening. For example, symbols were created for conditions like regular watering, adequate sunlight, pollination, and expected yield. Each common gardening issue was also assigned specific symbols, such as:

- `RightTimePlanting`: Planting at the right time.
- `RegularWatering`: Watering regularly.
- `Sun`: Receiving adequate sunlight.
- `Pollination`: Availability of pollination.
- `ExpectedGoodYield`: Expectation of a good yield.
  
Additional symbols were created to represent specific issues, such as `OverWatering`, `UnderWatering`, `NeedMoreWatering`, and `NeedMoreFertilization`, to capture the possible states and needs of plants in a garden.

### Step 3: Creating the Knowledge Base (KB)

Using the defined logic symbols, a set of logical sentences was constructed to form the KB. Each sentence represented a rule or condition based on the gardening principles established in Step 1. For example:

1. **Expected Good Yield Condition**: Planting at the right time, regular watering, sufficient sunlight, and pollination lead to a good yield.
RightTimePlanting ∧ RegularWatering ∧ Sun ∧ Pollination ⇒ ExpectedGoodYield


2. **Watering Conditions**: Conditions were defined for both under-watering and over-watering based on the appearance of plant leaves:
- Yellow, non-dry leaves indicate over-watering.
- Yellow, dry leaves indicate under-watering.

3. **Other Growth Conditions**: Rules were created to identify common problems like slow growth, which could indicate the need for more water or sunlight.

Each of these sentences represents a logical rule that the chat bot can use to diagnose and recommend solutions to gardening issues.

### Step 4: Propositional Inference on the KB

In this step, propositional logic inference was applied to the KB to simulate the chat bot’s response to specific gardening issues. Using information about the plant’s current state (such as whether it’s blossoming, bearing fruits, or has yellow leaves), logical deductions were made to determine whether the plant was overwatered, underwatered, or needed more sunlight or fertilization.

For example, given specific conditions (e.g., the plant has yellow, non-dry leaves and is growing slowly), a truth table was constructed to infer whether over-watering or under-watering was occurring. Only the combinations that satisfied all rules were considered valid, leading to a conclusion about the plant's watering needs.

### Conclusion

This document serves as a comprehensive guide to designing a simple Knowledge Base for a gardening chat bot using propositional logic. The steps involve understanding the domain, defining logic symbols, constructing a set of logical rules, and applying inference to make gardening recommendations. The KB provides a foundation for future expansions and improvements, potentially incorporating more complex logic or integrating with an interactive chat bot interface.

