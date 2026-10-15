# CascadeGuard — Infrastructure Resilience Simulator

CascadeGuard is a high-performance, client-side municipal infrastructure resilience simulator designed to model, analyze, and mitigate cascading failures across complex urban dependency networks.

## Features

- **25-Node Synthetic Urban Network**: Realistically modeled across 6 vital infrastructure sectors:
  - Electricity & Power Generation
  - Water Treatment & Pumping
  - Healthcare & Emergency Facilities (Trauma centers, Regional clinics, Dispatch)
  - Telecommunications & Cellular Exchanges
  - Transportation Systems (Transit hubs, Traffic control)
  - Data Centers & SCADA Control Systems
- **Physics-Based Dynamic Cascade Engine**: Multi-timestep failure propagation modeling capacity derating, dependency thresholds, and backup generator exhaustion.
- **Budget-Constrained Intervention Optimizer**: Combinatorial greedy search algorithm discovering high-leverage resilience investments (backup generator deployment, capacity upgrades, and topological redundancy).
- **Comprehensive Analysis Views**:
  - **Overview**: System-wide health metrics, sector breakdowns, and critical asset statuses.
  - **Infrastructure Network**: Interactive React Flow topology map with live inspector panel and failover triggers.
  - **Failure Simulation**: Step-by-step cascade playback controls, disaster scenarios, and chronological propagation timeline.
  - **Intervention Optimizer**: Budget allocation slider ($100K–$2M), algorithmic decision rationalization, and ROI impact metrics.
  - **Before & After Comparison**: Side-by-side counterfactual analysis with node-by-node protection audits and comparative charts.
  - **Vulnerability Analysis**: Single Points of Failure (SPOF) rankings by downstream risk and systemic impact.
  - **Scenario Testing**: Cross-hazard stress-testing matrix evaluating portfolio generalization.
  - **Methodology**: Mathematical formulas, threshold dynamics, and physics calibration sliders.
  - **Interactive Demo Runner**: 5-stage automated guided tour demonstrating end-to-end cascading failure and mitigation.

## Running the Application

### Development Server
```bash
npm run dev
```

### Production Build & Preview
```bash
npm run build
npm run preview
```

### Type Checking
```bash
npm run typecheck
```
