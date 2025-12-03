---
layout: single
title: "GeoExpert-QA"
permalink: /projects/geoexpert-qa/
author_profile: true
---

## GeoExpert-QA

A Zero-Shot Geospatial Question-Answering System

GeoExpert-QA (internally called Geode) is a project I built to explore a challenging question:
Can an AI system answer geography-based questions by actually computing the answer, rather than guessing from text?

To do this, I designed a multi-expert architecture that combines geospatial data retrieval, algorithmic reasoning, and automatically generated Python code. The goal was to create a system that can interpret natural language questions and then perform the necessary geographic or environmental computations to answer them accurately.

## Motivation

Most question-answering systems rely only on textual knowledge. But geography is inherently spatial—areas, intersections, coordinates, boundaries, environmental data, shapes, and relationships on maps. I wanted to build a system that could:

- Retrieve actual geographic shapes and boundaries
- Perform geometric and spatial analysis
- Work with environmental datasets
- Produce answers that come from computation, not memorization
- Provide transparent reasoning through generated code

This became the foundation for GeoExpert-QA.

## What the System Can Do

GeoExpert-QA is capable of handling a wide range of spatial and environmental queries. Some examples include:

- Comparing the areas of two countries or regions
- Retrieving air-quality, humidity, or other environmental measurements for a given place
- Determining geometric relationships (e.g., whether points form a triangle)
- Finding intersections or adjacency relationships between geographical entities
- Producing adjacency matrices for states or regions
- Interpreting descriptive queries like “the city known for the Eiffel Tower”

For every query, the system generates Python code using a set of expert modules, executes it, and returns both a textual answer and a visualizable geospatial object.

## How It Works

1. Query Interpretation

The system uses an LLM to understand what the user is asking and identify which geospatial experts are needed (location lookup, environmental data, geometric analysis, etc.).

2. Code Generation

Based on the interpreted query, the model generates executable Python code. This code calls different expert modules, such as:

- `patch_location_expert` for polygons and boundaries
- `point_location_expert` for coordinates
- `air_quality_expert` and `humidity_expert` for environmental data
- `intersection_expert` for spatial relationships
- `data_to_text_expert` to convert numeric data into readable text

3. Execution and Reasoning

The generated code is executed in a controlled environment. The output consists of:

- A computed answer
- An optional GeoPatch object for visualization
- The underlying code used to produce the result

This makes the system transparent and verifiable.

## Architecture Overview

GeoExpert-QA is built around a simple but powerful idea: instead of answering questions directly, generate the procedure for answering them.

The architecture includes:

- A natural language understanding layer
- A code-generation layer
- A suite of geospatial expert modules
- A runtime execution engine
- A visualization system built around GeoPandas/Folium

This design lets the system scale to new types of spatial or environmental tasks just by adding more experts.

## Technologies Used

- Python
- Streamlit (interface)
- GeoPandas, Shapely, Folium
- PyTorch
- NumPy, SciPy
- OpenStreetMap datasets
- A custom GeoPatch data structure for representing points, polygons, and rasters

## Applications

Although it started as an experimental project, it has potential applications in areas like:

- Geographic education and interactive learning tools
- Spatial analytics and mapping assistants
- Environmental data exploration
- Automated geospatial research pipelines
- Intelligent geographic reasoning systems

<p style="margin-top:1rem;"><a href="https://github.com/Abishekkarthik07/GeoExpert-QA" style="text-decoration:none;">📜 <strong>[View code]</strong></a></p>

<p style="margin-top:1rem;"><a href="/projects/" style="text-decoration:none;color:#1a73e8;">← Back to Projects</a></p>
