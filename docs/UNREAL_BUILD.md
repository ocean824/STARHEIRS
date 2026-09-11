# STARHEIRS — Unreal Production Build

Foundation: Narrative Pro 2 + Ultra Game Template 1.3.

Recommended Fab: Turn-Based RPG Template for battle prototype; Pocket Creature Tamer as collection/evolution reference; Element Reaction System for affinities; HKH Attribute System only if selected as sole stat layer; Game Animation Sample and environments for prototype content.

Canonical ownership: STARHEIRS rules define party turn/action economy, companion parts/evolution/fusion, puzzle/traversal abilities, narrative state integration and save schema. Template data is migrated into canonical definitions rather than becoming permanent parallel truth.

Implementation: pure/data-driven battle rules where possible; C++ domain/state core; Blueprints for content/UI/encounters; deterministic battle replay fixtures for testing.

Gauntlet: battle legality/turn ordering, evolution/fusion lineage, inventory/parts invariants, puzzle soft-lock checks, save migration, UI/controller accessibility and packaged performance.
