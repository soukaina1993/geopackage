# PDF Documents Summary

## 1. Article_Scientifique_Cornelia_Kane_ADVENS.pdf

**Title:** An object-oriented implementation of a recursive "quantum network" solver and its application to district heating networks

**Authors:** Cornelia Blanke, Malick Kane

**Published in:** Energy Conversion and Management: X 24 (2024) 100690

**Institution:** School of Engineering and Architecture (HEIA-FR), Energy Institute, HES-SO University of Applied Sciences and Arts of Western Switzerland, Fribourg, Switzerland

**Number of pages:** 15

### Summary:
This scientific article presents an object-oriented C++ implementation of a "quantum network" solver for district heating networks (DHN). Key points include:

- **Problem addressed:** Traditional engineering methods are insufficient for modern district heating networks. Existing simulation packages offer high accuracy but require considerable manual preparation and computational effort.

- **Solution proposed:** A novel, highly flexible modular approach called "quantum networks" where all parts of the district heating network are abstracted into quantum elements.

- **Implementation:** Object-oriented C++ library using inheritance and polymorphism, allowing different levels of detail for the same element type.

- **Key concepts:**
  - District heating networks can be modeled as binary trees
  - Pipes run in antiparallel manner (supply and return paths)
  - Recursive solver approach for efficiency
  - Suitable for both simplified early-phase studies and detailed planning

---

## 2. Kane_Q-Network_2022_submitted_.pdf

**Title:** A "quantum network" theory to model, design and operate a district's energy systems

**Authors:** Malick Kane, Lucile Schulthess, Jérémy Rolle

**Institution:** School of Engineering and Architecture (HEIA-FR), HES-SO University of Applied Sciences and Arts of Western Switzerland, Fribourg, Switzerland

**Number of pages:** 49

### Summary:
This comprehensive document presents the theoretical foundation of the "quantum network" approach for district heating/cooling (DHC) systems. Key points include:

- **Challenge:** New generation District Heating/Cooling (DHC) systems are more complex and difficult to simulate, design and operate.

- **Traditional approach:** Cluster or layer-based design divides large networks into subsystems, but still requires time-consuming iterative procedures.

- **Quantum network theory:** An original method inspired by "quantum mechanics" that:
  - Represents any network as an equivalent branched network called a "quantum network"
  - Uses quanta for energy distribution (discontinuous quantities)
  - Eliminates iterative procedures in simulation
  
- **ADVENS tool:** The "quantum flow-energy" formulation is implemented in the "ADVENS" network simulation tool.

- **Validation results:**
  - Comparison with Neplan software: 0.8% to 2% relative error
  - Calibration with real operating network data: ~1% deviation in winter and between seasons
  - Summer deviation: ~5% (due to domestic hot water load scenarios)

---

## Relationship to Repository

These documents are directly related to the `superstructure.gpkg` GeoPackage file in this repository, which contains a heating network model. The PDF files provide the theoretical and implementation foundation for simulating district heating networks using the "quantum network" approach developed at HEIA-FR.
