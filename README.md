# Smart-Traffic-Light-Control
graph TD
    %% ================================
    %% TOP LEVEL
    %% ================================
    L0["<b>Project Vision</b><br/>Intelligent Traffic Light System"] 

    %% ================================
    %% L1 SUBSYSTEMS
    %% ================================
    L0 --> L1_1["Data Acquisition & Ingestion"]
    L0 --> L1_2["Perception (YOLO Detection)"]
    L0 --> L1_3["Metrics & Analytics"]
    L0 --> L1_4["Control Algorithm & Simulation"]
    L0 --> L1_5["Visualization & Dashboard"]
    L0 --> L1_6["Infrastructure & Deployment"]

    %% ================================
    %% L2 + L3: DATA ACQUISITION
    %% ================================
    L1_1 --> L1_1_1["Camera Setup & Config"]
    L1_1 --> L1_1_2["Sample Dataset"]
    L1_1 --> L1_1_3["Video Input Interface"]

    %% ================================
    %% L2: PERCEPTION
    %% ================================
    L1_2 --> L1_2_1["YOLO Model Selection"]
    L1_2 --> L1_2_2["Frame Detection API"]
    L1_2 --> L1_2_3["Tracking & ID Assignment"]
    L1_2 --> L1_2_4["ROI & Queue Assignment"]

    %% ================================
    %% L2: METRICS
    %% ================================
    L1_3 --> L1_3_1["Per-frame Queue State"]
    L1_3 --> L1_3_2["Waiting Time per ID"]
    L1_3 --> L1_3_3["Per-second Aggregation"]
    L1_3 --> L1_3_4["Data Persistence"]

    %% ================================
    %% L2: CONTROL + SIMULATION
    %% ================================
    L1_4 --> L1_4_1["Problem Formulation"]
    L1_4 --> L1_4_2["Fixed-time Baseline"]
    L1_4 --> L1_4_3["Adaptive Rule-based Control"]
    L1_4 --> L1_4_4["(Optional) RL-based Control"]
    L1_4 --> L1_4_5["Simulation Engine"]

    %% ================================
    %% L2: VISUALIZATION
    %% ================================
    L1_5 --> L1_5_1["Overlay Video Generation"]
    L1_5 --> L1_5_2["Metric Plots"]
    L1_5 --> L1_5_3["Web Dashboard"]

    %% ================================
    %% L2: INFRASTRUCTURE
    %% ================================
    L1_6 --> L1_6_1["Repo Structure"]
    L1_6 --> L1_6_2["Config & Versioning"]
    L1_6 --> L1_6_3["(Optional) Dockerization"]

    %% ================================
    %% COLOR STYLES BY PROJECT STAGE
    %% ================================

    %% Data Acquisition: BLUE
    style L1_1 fill:#d0e7ff,stroke:#1a73e8,stroke-width:1px
    style L1_1_1 fill:#d0e7ff,stroke:#1a73e8
    style L1_1_2 fill:#d0e7ff,stroke:#1a73e8
    style L1_1_3 fill:#d0e7ff,stroke:#1a73e8

    %% Perception: PURPLE
    style L1_2 fill:#e6d5ff,stroke:#7b2cbf
    style L1_2_1 fill:#e6d5ff,stroke:#7b2cbf
    style L1_2_2 fill:#e6d5ff,stroke:#7b2cbf
    style L1_2_3 fill:#e6d5ff,stroke:#7b2cbf
    style L1_2_4 fill:#e6d5ff,stroke:#7b2cbf

    %% Metrics: GREEN
    style L1_3 fill:#d5f5d3,stroke:#2e8b57
    style L1_3_1 fill:#d5f5d3,stroke:#2e8b57
    style L1_3_2 fill:#d5f5d3,stroke:#2e8b57
    style L1_3_3 fill:#d5f5d3,stroke:#2e8b57
    style L1_3_4 fill:#d5f5d3,stroke:#2e8b57

    %% Control & Simulation: ORANGE
    style L1_4 fill:#ffe5cc,stroke:#ff8c00
    style L1_4_1 fill:#ffe5cc,stroke:#ff8c00
    style L1_4_2 fill:#ffe5cc,stroke:#ff8c00
    style L1_4_3 fill:#ffe5cc,stroke:#ff8c00
    style L1_4_4 fill:#ffe5cc,stroke:#ff8c00
    style L1_4_5 fill:#ffe5cc,stroke:#ff8c00

    %% Visualization: YELLOW
    style L1_5 fill:#fff9c4,stroke:#fbc02d
    style L1_5_1 fill:#fff9c4,stroke:#fbc02d
    style L1_5_2 fill:#fff9c4,stroke:#fbc02d
    style L1_5_3 fill:#fff9c4,stroke:#fbc02d

    %% Infrastructure: GRAY
    style L1_6 fill:#eeeeee,stroke:#757575
    style L1_6_1 fill:#eeeeee,stroke:#757575
    style L1_6_2 fill:#eeeeee,stroke:#757575
    style L1_6_3 fill:#eeeeee,stroke:#757575
