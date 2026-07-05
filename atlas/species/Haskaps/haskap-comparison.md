---
title: Haskap Comparison
parent: Haskaps
layout: page
permalink: /atlas/species/Haskaps/haskap-comparison/
nav_order: 6
---

# Haskap Cultivar Comparison System

This page synthesizes performance, role, and system behavior across Mori Mountain haskap cultivars.

---

## Cultivar
{% assign cultivars = site.data.cultivars.haskaps.cultivars %}
<table>
  <tr>
    <th>Attribute</th>
    {% for cultivar in cultivars %}
      <th>{{ cultivar.name }}</th>
    {% endfor %}
  </tr><tr>
    <td>Status</td>
    {% for cultivar in cultivars %}
      <td>{{ cultivar.status }}</td>
    {% endfor %}
  </tr><tr>
    <td>Primary Role</td>
    {% for cultivar in cultivars %}
      <td>{{ cultivar.system_role.primary }}</td>
    {% endfor %}
  </tr><tr>
    <td>Flowering Time</td>
    {% for cultivar in cultivars %}
      <td>{{ cultivar.phenology.flowering_time }}</td>
    {% endfor %}
  </tr><tr>
    <td>Fruiting Window</td>
    {% for cultivar in cultivars %}
      <td>{{ cultivar.phenology.fruiting_window }}</td>
    {% endfor %}
  </tr><tr>
    <td>Winter Kill Risk</td>
    {% for cultivar in cultivars %}
      <td>{{ cultivar.risk.winter_kill_risk }}</td>
    {% endfor %}
  </tr><tr>
    <td>Soil pH (Optimum)</td>
    {% for cultivar in cultivars %}
      <td>{{ cultivar.environment.soil_ph.optimum.min }}–{{ cultivar.environment.soil_ph.optimum.max }}</td>
    {% endfor %}
  </tr><tr>
    <td>Soil pH (Tolerance)</td>
    {% for cultivar in cultivars %}
      <td>{{ cultivar.environment.soil_ph.tolerance.min }}–{{ cultivar.environment.soil_ph.tolerance.max }}</td>
    {% endfor %}
  </tr><tr>
    <td>Best Pollinators</td>
    {% for cultivar in cultivars %}
      <td>{{ cultivar.relationships.best_pollinators | join: ", " }}</td>
    {% endfor %}
  </tr><tr>
    <td>Edible Value</td>
    {% for cultivar in cultivars %}
      <td>{{ cultivar.utility.edible_value }}</td>
    {% endfor %}
  </tr><tr>
    <td>Market Demand</td>
    {% for cultivar in cultivars %}
      <td>{{ cultivar.utility.market_demand }}</td>
    {% endfor %}
  </tr><tr>
    <td>Productivity Score</td>
    {% for cultivar in cultivars %}
      <td>{{ cultivar.performance.productivity_score }}</td>
    {% endfor %}
  </tr><tr>
    <td>Stability Score</td>
    {% for cultivar in cultivars %}
      <td>{{ cultivar.performance.stability_score }}</td>
    {% endfor %}
  </tr>
</table>

---

## Functional Analysis

The sections below are generated directly from the schema data above —
nothing here is asserted independently of the table. Fields marked
`unknown` reflect real gaps pending field observation, not omissions
from this page.

### Yield Performance
{% for cultivar in cultivars %}
- **{{ cultivar.name }}** → productivity score: {{ cultivar.performance.productivity_score }}
{% endfor %}

### Pollination Contribution
{% for cultivar in cultivars %}
- **{{ cultivar.name }}** → role: {{ cultivar.system_role.primary }}, compatible pollinators: {{ cultivar.relationships.best_pollinators | join: ", " }}
{% endfor %}

### Climate / Winter Stability
{% for cultivar in cultivars %}
- **{{ cultivar.name }}** → winter kill risk: {{ cultivar.risk.winter_kill_risk }}, stability score: {{ cultivar.performance.stability_score }}
{% endfor %}

### System Role Classification
{% for cultivar in cultivars %}
- **{{ cultivar.name }}** → {{ cultivar.system_role.primary }}
{% endfor %}

---

## Research Dimensions

Mori Mountain evaluates cultivars across:

- Yield efficiency
- Pollination overlap
- Soil response variability
- Climate stress tolerance
- Market desirability
- System integration value

---

## Experimental Framework

Current comparative studies:

- Yield variation across cultivar mixes
- Pollination network efficiency
- Soil biology response (biochar + fungal inoculation)
- Spring frost resilience mapping
- Multi-year productivity curves

*(No trials are active yet — this section describes planned, not completed, work.)*

---

## Key Insight

Haskap performance is not cultivar-independent.

It is a **networked system outcome**, where:

- pollination structure
- cultivar mix
- soil biology
- climate timing

all determine final yield.

---

## Mori Mountain Interpretation Layer

This system is treated as:

> a biological production network, not a collection of independent shrubs.

---

## Related Pages

- Individual cultivar profiles
- Laboratory experiments
- Pollination biology research
- Living Market Atlas
