# Eu-Taxonomy-Ontology-OWL
This project consists in the development of an OWL ontology, developed using Protégé, that formalizes the structure of the EU Taxonomy for sustainable activities.
The ontology is designed to represent the core elements of the taxonomy, including environmental objectives, economic activities, technical screening criteria, minimum safeguards, and classification outcomes. It models the relationships and constraints that determine whether an economic activity can be considered taxonomy-aligned. The model is intentionally developed at a conceptual level, without instantiating specific individuals, in order to provide a clear and navigable representation of the taxonomy structure rather than a full operational classification system.

The conceptual structure has been derived from official EU documentation, with a focus on preserving the logical dependencies between:
* substantial contribution to environmental objectives
* the Do No Significant Harm (DNSH) principle
* compliance with minimum safeguards
* technical screening criteria

The ontology includes:
* classes for environmental objectives, economic sectors, and activities
* subclasses reflecting taxonomy categories (e.g. enabling, transitional activities)
* object properties defining relationships such as contribution, compliance, and classification
* logical constraints reflecting the conditions required for taxonomy alignment
