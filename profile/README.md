# GaiaWM

GaiaWM is an experimental world model framework designed to help intelligent systems *interpret*, *reason about*, and *act within* spatial environments — not by knowing everything, but by understanding what matters.

GaiaWM uses the data from the sister projects **OpenHistoryMap** (https://www.openhistorymap.org) and **OpenFantasyMaps** (https://www.fantasymaps.org) as well as the rules managed by **OntoRAG** (https://ontorag.github.io) as core elements in the construction of a complex living world where LLM agents can learn and interact with the world.

GaiaWM focuses on **meaningful, agent-centric world representation**, supporting contexts where systems operate under uncertainty, partial observation, and evolving goals.

---

## Use Cases

- **Eye on FantasyMaps** - You can explore the world not only by "looking" at the map but also by havin an eye directly in the field: By clicking the eye in the top right angle of the map you can select a poin from which the world has to be described and a direction. The way you are looking at the world defines the description that is passed through the GaiaWM API and returns a description as if you were there. 
  https://map.fantasymaps.org/toril/1302/9.155188741024675/43.171531516613754/-75.4897972464646
  <img width="1280" height="853" alt="image" src="https://github.com/user-attachments/assets/bec386cf-2dc9-4d96-8d6a-e6cf61e486d7" />


---

## 🔍 What GaiaWM Is

GaiaWM stands for **“Gaia World Model”**, a conceptual foundation for representing context in ways agents can *use*, not just *store*. At its core, GaiaWM models:

- **Spatial context** that agents can query and interpret  
- **Belief states** instead of perfect world states  
- **Affordances and uncertainty** instead of static tags  
- **Action-relevant context** instead of global knowledge dumps

It’s designed for scenarios where agents need to make decisions based on *incomplete information* — which is most real-world and simulation domains.

---

## 🧠 Conceptual Highlights

GaiaWM rethinks world models by emphasizing:

- **Belief over truth**  
  Agents hold *what they think might be true* based on observations and limited context.

- **Affordance-based understanding**  
  Objects and elements in the environment are interpreted for *what they enable*.

- **Actionable representation**  
  The model isn’t solved once; it evolves with agent interaction and needs.

---

## 🌍 Foundational Data Sources

GaiaWM builds on open spatial datasets you may already know and trust:

- **OpenHistoryMap** — a web platform for historical and archaeological spatial information.  
  https://www.openhistorymap.org

- **OpenFantasyMaps** — open cartography for fantasy and imagined worlds built with real GIS foundations.  
  https://www.fantasymaps.org

These serve as anchor points for world context without locking GaiaWM into any single map format or visualization approach.

---

## 🚀 What GaiaWM Can Be Used For

GaiaWM is relevant to multiple domains:

✅ **AI Training & Synthetic Data** — Generate context-rich scenarios for model training.  
✅ **Game Worlds & Simulation** — Support intelligent behavior and dynamic world queries.  
✅ **Multi-Agent Reasoning** — Represent agent beliefs and influence planning under uncertainty.  
✅ **Research & Prototyping** — Explore alternative world model representations beyond exhaustive state.

---

## 🧩 How It Fits Together

GaiaWM is organized as an **open ecosystem** of repositories shaped around:

- World context APIs  
- Agent belief frameworks  
- Object interpretation helpers  
- Extensible connectors for other systems  
- Example integrations for AI workflows and simulations

Each repo under this organization is part of that ecosystem — modular, interoperable, and open to extension.

---

## 🧠 About the Author

GaiaWM builds on years of work in spatial systems and open data, including:

- **OpenHistoryMap** — historical spatial mapping  
- **OpenFantasyMaps** — open GIS for creative worlds

Learn more in the individual repositories or reach out via GitHub.

---

## 📜 License

Most GaiaWM repositories use permissive open source licenses. Check individual repos for specific terms.

---

**GaiaWM** — World models reimagined for intelligent systems.
