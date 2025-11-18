# Smart-Traffic-Light-Control
graph TD
    L0["Project Vision"]
    
    L0 --> L1_1["Data Acquisition & Ingestion"]
    L0 --> L1_2["Perception (YOLO Detection)"]
    L0 --> L1_3["Metrics & Analytics"]
    L0 --> L1_4["Control Algorithm & Simulation"]
    L0 --> L1_5["Visualization & Dashboard"]
    L0 --> L1_6["Infrastructure & Deployment"]

    L1_1 --> L1_1_1["Camera Setup & Config"]
    L1_1 --> L1_1_2["Sample Dataset"]
    L1_1 --> L1_1_3["Video Input Interface"]

    L1_2 --> L1_2_1["YOLO Model Selection"]
    L1_2 --> L1_2_2["Frame Detection API"]
    L1_2 --> L1_2_3["Tracking & ID Assignment"]
    L1_2 --> L1_2_4["ROI & Queue Assignment"]

    L1_3 --> L1_3_1["Per-frame Queue State"]
    L1_3 --> L1_3_2["Waiting Time per ID"]
    L1_3 --> L1_3_3["Per-second Aggregation"]
    L1_3 --> L1_3_4["Data Persistence"]

    L1_4 --> L1_4_1["Problem Formulation"]
    L1_4 --> L1_4_2["Fixed-Time Baseline"]
    L1_4 --> L1_4_3["Adaptive Rule-based Control"]
    L1_4 --> L1_4_4["(Optional) RL-based Control"]
    L1_4 --> L1_4_5["Simulation Engine"]

    L1_5 --> L1_5_1["Overlay Video"]
    L1_5 --> L1_5_2["Metric Plots"]
    L1_5 --> L1_5_3["Web Dashboard"]

    L1_6 --> L1_6_1["Repo Structure"]
    L1_6 --> L1_6_2["Config & Versioning"]
    L1_6 --> L1_6_3["(Optional) Dockerization"]
