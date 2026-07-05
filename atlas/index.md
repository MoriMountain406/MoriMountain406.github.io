---
title: Living Atlas
layout: page
nav_order: 1
---

# Living Atlas

The Living Atlas is the biological foundation of Mori Mountain.

It organizes plant life into structured, evolving systems of:
- species
- cultivars
- genetics
- soil relationships
- ecological interactions
- experimental data

---

## Enter the System

### 🌿 Species Atlas
Core plant systems and taxonomic organization  
→ [Open Species Atlas](/atlas/species/)

---

## System Layers

The Atlas is structured in layers:

### 1. Species Layer
Biological categories and plant groups

### 2. Cultivar Layer
Genetic and functional variations within species

### 3. Experimental Layer
Field data, trials, and observed behavior (linked via Lab)

### 4. System Interactions
Soil, fungi, climate, pollinators, and market feedback loops

---

## Connected Systems

- Laboratory → experimental validation
- Living Market Atlas → economic modeling
- Field Journal → real-world observations
- Protocol Library → repeatable methods

---

## How to Use This Atlas

Start here:
1. Enter Species Atlas
2. Select a plant system (e.g. Haskaps)
3. Explore cultivars
4. Follow links into experiments and market analysis

---

## Philosophy

The Living Atlas is not a catalog.

It is a **living model of plant systems under observation, experimentation, and commercial development.**

---
## Mission Statement

Okay, just to clarify, for myself as much for anyone else, as of now this is my schema development:

Mori Mountain Entity Schema

The Mori Mountain Entity Schema exists to create a standardized, extensible framework for documenting plants and other living organisms in a way that is both scientifically grounded and practically useful. Rather than serving as a simple collection of notes, the schema is intended to become a structured knowledge system that allows biological information to be stored, compared, searched, and expanded over time.

Each entity—whether a species, cultivar, variety, or individual plant—is documented using the same consistent structure. This allows information to remain organized as the database grows while making it possible to compare different organisms using shared attributes instead of scattered observations.

The schema is designed to capture more than taxonomy alone. It aims to document ecological function, environmental preferences, performance, relationships with other organisms, cultivation requirements, and long-term observations. Unknown information is intentionally preserved as unknown rather than estimated, allowing the database to remain scientifically honest while highlighting opportunities for future research.

As Mori Mountain evolves, this schema will become the foundation of a living ecological knowledge base. New observations can be added without changing the identity of an entity, allowing records to mature alongside our own experience and research. Over time, subjective evaluations can be refined using measured field data, creating an increasingly reliable body of knowledge.

A central design principle is that no single plant exists in isolation. Every organism participates in a network of relationships with soil biology, pollinators, companion species, climate, and human management. The schema is therefore designed not only to describe individual organisms, but also to represent the connections between them. These relationships ultimately allow the database to function as an ecological network rather than a collection of independent records.

Although initially developed for Mori Mountain’s own research and production systems, the long-term goal is to create an open, community-driven standard that others can adopt, contribute to, and build upon. By documenting plants using a shared structure, growers, researchers, breeders, educators, and enthusiasts can exchange information more consistently while reducing duplicated effort and improving the quality of collective knowledge.

Version 0.1.0 intentionally focuses on a minimal set of essential attributes. Rather than attempting to anticipate every future use case, the schema will evolve through practical application. Each new plant entered into the system serves as a real-world test, allowing the structure to grow naturally in response to demonstrated needs instead of unnecessary complexity.

Ultimately, the Mori Mountain Entity Schema is intended to become the foundation for a searchable, interconnected library of ecological knowledge—one that helps people better understand not only individual plants, but also the living systems they create together.

We believe ecological knowledge should be structured, transparent, and cumulative. Every observation should have a place, every unknown should remain honestly unknown until verified, and every plant should be understood not as an isolated organism but as part of a larger living network. The Mori Mountain Entity Schema is our attempt to build a common language for documenting those relationships so that knowledge can be shared, improved, and carried forward.

---

## Current Status

The Mori Mountain Entity Schema is in active development.

Current priorities include:

- Core taxonomy
- Environmental preferences
- Cultivation data
- Ecological relationships
- Stable identifiers

Future versions may expand into:

- Soil biology
- Genomic information
- Geographic observations
- Phenology
- Breeding lineages
- Sensor-derived field data

---

Draft Specification — v0.1.0

This document represents the initial public draft of the Mori Mountain Entity Schema. It is expected to evolve as additional plants, cultivars, fungi, and ecological relationships are documented. Backward compatibility is desirable but not guaranteed during the 0.x development phase. Feedback, discussion, and proposed improvements are encouraged.

# MORI MOUNTAIN ENTITY SCHEMA — v0.1.0 (TEMPLATE)
# Copy this block once per cultivar/plant. Leave a field as `unknown` or
# `null` rather than guessing — unknown is a valid, honest value here.

id:                          # unique-slug, e.g. aurora
name:                        # Display Name, e.g. Aurora
type: cultivar                # species | cultivar | plant
status:                        # wild | trial | production | archived
species:                      # e.g. haskap

system_role:
  primary:                    # production | pollination | resilience | research | benchmark
  network_function:            # short free-text description of its job in the system

performance:
  productivity_score:          # 1-10
  stability_score:              # 1-10
  vigor_score:                  # 1-10

risk:
  frost_sensitivity:            # low | medium | high
  drought_tolerance:            # low | medium | high
  disease_susceptibility:        # low | medium | high
  winter_kill_risk:              # low | medium | high

environment:
  climate_zone:                # e.g. "USDA 2-7"
  soil_ph:
    optimum:   {min: null, max: null}   # thrives here
    tolerance: {min: null, max: null}   # survives, but stressed
    lethal:    {below: null, above: null} # plant dies outside this

soil:
  mycorrhizal_type:              # endo | ecto | ericoid | none | unknown
  root_architecture:              # tap | fibrous | rhizomatous | surface

relationships:
  best_pollinators: []
  companion_plants: []
  antagonistic_species: []

phenology:
  bud_break:                    # early | mid | late
  flowering_time:                # early | mid | late
  fruiting_window:                # early | mid | late

utility:
  edible_value:                  # low | medium | high
  market_demand:                  # low | medium | high



