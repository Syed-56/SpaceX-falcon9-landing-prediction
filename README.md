# SpaceX Falcon 9 First Stage Landing Prediction

## Project Background

The commercial space age has arrived, with companies making space travel more affordable. Key players include:

- **Virgin Galactic** – suborbital spaceflights
- **Rocket Lab** – small satellite launch provider
- **Blue Origin** – sub-orbital and orbital reusable rockets
- **SpaceX** – arguably the most successful, with achievements including:
  - Cargo missions to the International Space Station (ISS)
  - **Starlink** – a satellite internet constellation
  - Crewed spaceflight missions

## Why SpaceX Launches Are Cheaper

SpaceX can offer significantly lower launch costs because it **reuses the rocket's first stage**.

| Provider | Cost per Launch |
|---|---|
| SpaceX (Falcon 9) | ~$62 million |
| Other providers | $165 million+ |

If we can predict whether the first stage will land successfully, we can estimate the **cost of a launch**.

## Falcon 9 Rocket Structure

- **Fairings** – enclose the payload
- **Second Stage** – helps deliver the payload to orbit
- **First Stage** – does most of the work; larger and more expensive than the second stage; the part SpaceX attempts to **recover and reuse**

> Diagrams referenced from Forest Katsch ([zlsadesign.com](http://zlsadesign.com)), a 3D artist and software engineer known for spaceflight infographics.

## Landing Outcomes

The first stage doesn't always land successfully:
- ✅ Successful landing and recovery
- ❌ Crash landing
- ⚠️ Intentionally expended (sacrificed) depending on mission parameters — payload mass, target orbit, and customer requirements

## Capstone Project Scenario

You are a **data scientist** working for **Space Y**, a new rocket company founded by billionaire industrialist Allon Musk, aiming to compete with SpaceX.

### Objectives
1. **Determine launch pricing** by gathering and analyzing public data on SpaceX.
2. **Predict first-stage reuse** — instead of using rocket science/physics, train a **machine learning model** using publicly available data to predict whether SpaceX will successfully reuse the first stage.
3. **Build dashboards** to present findings and insights to your team.

## Deliverables
- Data collection & wrangling pipeline
- Exploratory Data Analysis (EDA)
- Interactive dashboards
- Machine learning model to predict first-stage landing success