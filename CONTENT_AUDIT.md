# Learn Blog source-to-lesson coverage audit

**Sources audited:** `SIA-documentation updated.pdf` (124 pages; Parts 0?22 and 7B; 244 numbered examples) and `sia_examples.ipynb` (244 matching numbered examples). The lesson application routes and rendered content were checked against the in-project topic map.

## Scope and audit result

- The 45 examples in the protected Basics / Mathematical Foundations curriculum (Examples 1?45; Parts 0, 0B and 0C) were deliberately left out of this update. Their lesson bodies were not edited.
- All remaining PDF/notebook examples (Examples 46?244, 199 total) are assigned exactly once across the 25 remaining Learn Blog topics below. Split parts are noted in the table. The counts are taken from each topic?s actual rendered lesson example array, not inferred from heading text.
- For all 199 relevant examples, the lesson has the exact notebook code and saved textual output. Each also has a code explanation and an output explanation; saved figures are attached where present (14 visual artifacts). Any extra PDF context that is distinct from the notebook caption is displayed alongside the example.
- ?Included / available? is the code/output example count. Theory and subtopic coverage is checked in the lesson?s concepts text and part introduction; per-example code/output explanations are checked separately.

## Topic checklist

| Learn Blog topic | PDF part and concepts/subtopics audited | Notebook examples available / included | Coverage checklist |
|---|---|---:|---|
| Basic Circuits | Part 1 ? Basic circuits: register creation with hdqs(n); chained operations; superposition; Bell/GHZ states and sampling | 16 / 16 (46?61) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| The Gate Set | Part 2 ? The gate set: Pauli, Clifford, phase and rotation gates; controlled/multi-qubit gates; custom matrices | 16 / 16 (62?77) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| Measurement, Records and Feed-Forward | Part 3 ? Measurement, records and feed-forward: measurement outcomes; records; conditional feed-forward | 8 / 8 (78?85) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| Analysing Quantum States | Part 4 ? Analysing states: expectation values; Bloch vectors; entropy; entanglement; state distances | 12 / 12 (86?97) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| Observables, Hamiltonians and Primitives | Part 5 ? Observables, Hamiltonians and primitives: Pauli-sum observables; time evolution; Sampler and Estimator | 7 / 7 (98?104) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| Noise and Mitigation | Part 6 ? Noise and mitigation: density matrices; noise channels; trajectories; mitigation | 14 / 14 (105?118) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| Programs: Replay, Sweep and Undo | Part 7 ? Programs: replay, sweep, undo, save: program replay; optimization/sweeps; inversion/undo; examples 119?122 and 125?129 (save/restore examples are mapped to the adjacent lesson) | 9 / 9 (119?122, 125?129) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| Save and Restore Programs | Part 7 ? Programs: replay, sweep, undo, save: save and restore program examples | 2 / 2 (123?124) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| Checking and Research Tools | Part 7B ? Checking and research tools: unitary/equivalence checks; state comparison; parameter sweeps; engine self-check | 5 / 5 (130?134) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| OpenQASM 3 | Part 8 ? OpenQASM 3: OpenQASM 3 import and export | 4 / 4 (135?138) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| Large Registers | Part 9 ? Large registers and simulation modes: large-register program representation; examples 139?141 | 3 / 3 (139?141) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| Simulation Modes | Part 9 ? Large registers and simulation modes: stabilizer and matrix-product-state simulation; examples 142?143 | 2 / 2 (142?143) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| Algorithms | Part 10 ? Algorithms: documented algorithm result dictionaries and their circuit/state outputs | 10 / 10 (144?153) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| Communication Protocols | Part 11 ? Communication protocols: teleportation; superdense coding; quantum key distribution | 7 / 7 (154?160) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| Applications: Optimisation, VQE, Error Correction and CRIA | Part 12 ? Applications: optimisation, VQE, error correction, CRIA: variational optimization; chemistry-style VQE; error correction; CRIA/interference accessibility | 14 / 14 (161?174) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| Visuals for Registers | Part 13 ? Visuals for registers: circuit, probability, counts, amplitudes/phase, Bloch, Q-sphere, density matrix, entanglement, CRIA and step-through views | 15 / 15 (175?189) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| Algorithm Visuals and Live Players | Part 14 ? Algorithm visuals and live players: algorithm animations and interactive HTML players | 10 / 10 (190?199) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| Publication Figures | Part 15 ? Publication figures: paper preset; publication-ready figures and captions | 5 / 5 (200?204) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| LaTeX, Bundles and Frame Sequences | Part 16 ? LaTeX, bundles and frame sequences: LaTeX circuits; research bundles; numbered frames | 8 / 8 (205?212) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| 3D Models | Part 17 ? 3D models: Bloch sphere; Q-sphere; density-matrix 3D scenes | 2 / 2 (213?214) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| 3D Printing | Part 18 ? 3D printing: STL/3MF exports; dimensions; presets; print reports | 5 / 5 (215?219) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| Lessons and Worksheets | Part 19 ? Teaching: lessons and worksheets: prediction questions; interactive lessons; printable worksheets | 11 / 11 (220?230) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| The Browser Playground | Part 20 ? The browser playground: offline HTML playground; HDQS chains; step-through; Plain/Python input | 4 / 4 (231?234) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| Machine Learning with PyTorch | Part 21 ? Machine learning with PyTorch: quantum layers; exact and parameter-shift gradients; hybrid batches/models | 4 / 4 (235?238) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |
| Interoperability and Utilities | Part 22 ? Interoperability and utilities: optional SDK adapters; capabilities and resource utilities | 6 / 6 (239?244) | ? Concepts and subtopics; ? exact code/output; ? code and output explanations |

## Source-integrity checklist

- [x] PDF curriculum parts 1?22 and 7B mapped to the existing 25 topic routes; Parts 7 and 9 are intentionally split at the lesson boundary.
- [x] Notebook numbered headings 46?244 matched against lesson example IDs: 199 of 199 found, with no duplicates or unassigned examples.
- [x] Compared all mapped code against the original notebook code cells: 199 exact matches, 0 mismatches.
- [x] Compared all mapped captured outputs against original notebook outputs: 199 exact matches, 0 mismatches.
- [x] Checked all 199 records have code/output explanations; 14 saved notebook images are present and referenced.
- [x] Verified all 25 topic routes, titles, sidebar destinations, and adjacent-topic links; protected Basics and Mathematical Foundations lesson bodies remain unchanged.
- [x] Removed the UP NEXT and ON THIS PAGE panels; checked browser history and mobile layout.

The examples? recorded outputs are reproduced from saved notebook outputs; this report does not claim they were freshly re-executed. See the task completion notes for the browser/runtime verification details.
