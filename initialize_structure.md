anti_drone_system/
│── ai_module/                  # AI-based detection and classification
│   ├── models/                 # Trained ML/DL models (YOLO, Faster R-CNN, etc.)
│   ├── scripts/                # Training and inference scripts
│   ├── dataset/                # Image and sensor datasets
│── sensors/                    # Sensor integration (RF, Camera, LIDAR, etc.)
│   ├── camera/
│   ├── rf_scanner/
│   ├── gps/
│── countermeasures/            # Jamming, GPS spoofing, etc.
│   ├── jammer/
│   ├── gps_spoofer/
│── navigation/                 # Drone tracking and interception
│   ├── path_planning/
│   ├── flight_control/
│── ros_packages/               # ROS-based modules for communication
│── backend/                    # Server-side logic and API
│   ├── api/                    # FastAPI/Flask for remote monitoring
│   ├── database/                # SQLite/PostgreSQL for storing events
│── frontend/                   # UI for monitoring system
│   ├── mobile/                 # Mobile app (Flutter)
│── docs/                       # Documentation and research
│── scripts/                    # Utility scripts
│── configs/                    # Configuration files
│── tests/                      # Unit and integration tests
│── requirements.txt            # Python dependencies
│── Dockerfile                  # Containerization -- later
│── README.md                   # Project overview
