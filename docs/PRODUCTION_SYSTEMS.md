# STARHEIRS — Production Systems

Domains: party, deterministic battle, companions, parts/equipment, evolution/fusion, exploration/puzzles, narrative/relationships, inventory/economy, UI/audio/save.

Battle commands/events are serializable for golden replays. Companion lineage and part compatibility use stable IDs and invariant tests. Puzzle/traversal unlock graph is statically analyzed for soft locks. Save migrations preserve party, inventory, relationship and world progression.

Requirements: STAR-REQ-001 deterministic battles; 002 companion identity/customization; 003 lineage integrity; 004 puzzle progression solvable; 005 narrative/bond state; 006 controller/accessibility; 007 Unreal/AXIOM parity fixtures.
