<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License">
  <img src="https://img.shields.io/badge/Contributions-Welcome-orange.svg" alt="Contributions">
</p>

<h1 align="center">🚶‍♂️ Pedestrian Simulation Models</h1>
<p align="center">
  <strong>A vibrant hub of pedestrian simulation models for researchers, urban planners, and tech enthusiasts.</strong>
</p>
<p align="center">
  From social forces to AI-driven trajectories, explore, simulate, and innovate crowd dynamics like never before!
</p>

---

## 🌟 Why This Repository?

Crowd dynamics shape our cities, safety systems, and autonomous tech. **Pedestrian Simulation Models** is your one-stop shop for exploring *24 cutting-edge models*—from classic physics-based approaches to modern AI-driven predictions. Whether you're studying evacuation scenarios, designing smarter cities, or building AVs that navigate human crowds, this repository empowers you with:

- **Executable Code**: Ready-to-run Python implementations with Jupyter Notebook demos.
- **Comprehensive Coverage**: 24 models, including Social Force, Cellular Automata, RL-based, Vision-based, and more.
- **Research-Ready Tools**: Benchmarks, comparisons, and integrations with CARLA, SUMO, and Unity.
- **Open & Modular**: MIT-licensed, designed for easy extensions and community contributions.

This isn’t just a collection—it’s a *playground for innovation* in crowd simulation.

## 🎨 Features That Shine

- **24 Models**: From granular physics to generative AI, covering macroscopic, microscopic, mesoscopic, and hybrid approaches.
- **Interactive Demos**: Jupyter Notebooks for every model, showcasing scenarios like evacuations and street crossings.
- **Performance Insights**: Compare models with `metrics_eval.ipynb` for runtime, accuracy, and scalability.
- **Real-World Integrations**: Plug into CARLA for AV testing, SUMO for traffic sims, or Unity for 3D visualizations.
- **Data & Scenarios**: Synthetic datasets and example scenarios to jumpstart your experiments.
- **Research Context**: Curated paper summaries in `docs/paper_summaries.md` to ground your work.

## 🚀 Quickstart

Get moving in minutes!

1. **Clone the repo**:
   ```bash
   git clone https://github.com/<your-username>/pedestrian-sim-models.git
   cd pedestrian-sim-models
   ```
2. **Install dependencies (example for Social Force model)**:
   ```bash
   pip install -r models/social_force/requirements.txt
   ```
3. **Run a demo**:
    ```bash
   jupyter notebook models/social_force/demo.ipynb
   ```
Watch pedestrians navigate an evacuation scenario with physics-based flair!

---

## 📦 What's Inside?
 ```bash
   pedestrian-sim-models/
├── README.md                   # You're here!
├── LICENSE                     # MIT, free for all
├── models/                     # The heart of the action
│   ├── social_force/           # Physics-based crowd movement
│   ├── cellular_automata/      # Grid-based discrete dynamics
│   ├── vision_based/           # CNN-driven navigation
│   ├── rl_based/               # RL-powered pedestrians
│   ├── hybrid_models/          # Best of multiple worlds
│   ├── granular/               # Particle-based contact forces
│   ├── macroscopic/            # Crowd as flows
│   ├── microscopic/            # Individual precision
│   ├── mesoscopic/             # Group dynamics
│   ├── agent_based/            # Mesa-driven agents
│   ├── rule_based/             # Simple rule-driven movement
│   ├── prediction_models/      # Data-driven trajectory forecasting
│   ├── social_lstm_gans/       # Socially-aware LSTMs & GANs
│   ├── generative_models/      # VAEs and diffusion models
│   ├── continuum/              # Flow-based crowds
│   ├── fluid_dynamics/         # Navier-Stokes for crowds
│   ├── graph_based/            # Graph-driven navigation
│   ├── path_based/             # A* pathfinding
│   ├── sumo_models/            # SUMO pedestrian sims
│   ├── optimal_steps/          # Efficient A* movement
│   ├── gradient_navigation/    # Gradient field navigation
│   ├── behavioral_heuristics/  # Heuristic-driven behavior
│   ├── steering_behaviors/     # Game-inspired steering
│   ├── collision_free_speed/   # Velocity-based avoidance
│   ├── anticipation_velocity/  # Predictive collision avoidance
│   ├── centrifugal_force/      # Generalized force dynamics
│   └── common/                 # Shared utilities & visualizations
├── comparison/                 # Benchmark models
│   └── metrics_eval.ipynb      # Compare runtime, accuracy, scalability
├── integrations/               # Real-world connections
│   ├── CARLA/                  # AV simulation
│   ├── SUMO/                   # Traffic simulation
│   └── Unity/                  # 3D visualization
├── data/                       # Ready-to-use scenarios
│   └── example_scenarios/      # Evacuation, street crossing datasets
├── docs/                       # Research fuel
│   └── paper_summaries.md      # Key paper summaries
└── .gitignore                  # Keep it clean
   ```
---

## 🧠 Models at a Glance

| **Model**           | **Type**       | **Key Feature**                                 | **Use Case**                          |
|---------------------|----------------|--------------------------------------------------|----------------------------------------|
| **Social Force**        | Microscopic    | Physics-based attractive/repulsive forces        | Evacuation, crowd flow                 |
| **Cellular Automata**   | Microscopic    | Grid-based discrete movement                     | Large-scale crowds                     |
| **Vision-Based**        | AI-Driven      | CNN for visual navigation                        | AV pedestrian detection                |
| **RL-Based**            | AI-Driven      | Learned policies via reinforcement learning      | Adaptive behaviors                     |
| **Hybrid Models**       | AI-Driven      | Learned policies via reinforcement learning      | Adaptive behaviors                     |
| **RL-Based**            | AI-Driven      | Learned policies via reinforcement learning      | Adaptive behaviors                     |
| **RL-Based**            | AI-Driven      | Learned policies via reinforcement learning      | Adaptive behaviors                     |
| **RL-Based**            | AI-Driven      | Learned policies via reinforcement learning      | Adaptive behaviors                     |
| **RL-Based**            | AI-Driven      | Learned policies via reinforcement learning      | Adaptive behaviors                     |
| **RL-Based**            | AI-Driven      | Learned policies via reinforcement learning      | Adaptive behaviors                     |
| **RL-Based**            | AI-Driven      | Learned policies via reinforcement learning      | Adaptive behaviors                     |
| **RL-Based**            | AI-Driven      | Learned policies via reinforcement learning      | Adaptive behaviors                     |
| **RL-Based**            | AI-Driven      | Learned policies via reinforcement learning      | Adaptive behaviors                     |
