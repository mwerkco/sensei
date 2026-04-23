![Logo](https://beeimg.com/images/c82627653203.png)


# Sensei | The Ultimate Intelligence Interface

Sensei is a high-accuracy intelligence and reconnaissance platform designed for OSINT (Open Source Intelligence), SOCMINT (Social Media Intelligence), and LOCINT (Location Intelligence) operations. It provides a unified command center for data collection, asset analysis, geopolitical analysis, and tactical reconnaissance.
## Features

- 🔍 Target Recon
- 🗺️ Geospatial Intelligence
- 🖥️ Geopolitical Monitoring
- 🌐 Automated Search
- 📂 Case Management
- 👤 Social Media Scraping
- ⌨️ Open Web Scraping
- 🔦 DarkWeb Scraping
- 📍 Location Find From Images


## Architecture

The application follows a modern desktop architecture that combines high-performance Python services with a contemporary and responsive React-based interface.

### Frontend (Electron + Vite + React);
 Framework: TypeScript and React 18.

Shell: Electron for native desktop capabilities (file system access, process management).

 Style: Vanilla CSS + TailwindCSS for modular design.

Situation Management: Zustand/React Context for application-wide situations.

Visualization: D3.js and Canvas for high-performance graphical visualization (OsintGraph, WhoisGraph).

Maps: Mapbox GL JS for geographic data visualization.

![App Screenshot](https://beeimg.com/images/g06407540683.jpg)


### Backend  (FastAPI + Python)
Engine: FastAPI (Uvicorn) running on localhost:8000.

Concurrency: Asyncio for input/output intensive tasks (scanning, API calls) and threading for CPU intensive tasks (ML inference).

ML Stack: PyTorch, OpenCV, YOLOv8/v10 for image processing tasks.

NLP: Spacy and custom LLM wrappers for asset extraction and correlation.

![App Screenshot](https://beeimg.com/images/o96427226033.jpg)
![App Screenshot](https://beeimg.com/images/i90298842672.jpg)

## Node Modules
### SOCMINT (Social Media Intelligence)
The SOCMINT engine follows a 5-stage pipeline for target exploration: 1. Discovery: Parallel searching across platforms (Twitter, Instagram, LinkedIn, etc.) with intelligent validation. 2. Crawling: Headless crawler (Playwright/Puppeteer) or direct requests (Proxy/Tor supported) to retrieve raw data. 3. Extraction: NLP-supported entity recognition (usernames, emails, phone numbers, biographies). 4. Normalization: Deduplication and schema alignment of extracted entities. 5. Correlation: Connecting entities using graph theory (Maltego-style relationships).

Features: SQLite query caching (1-hour TTL), proxy rotation, headless crawler backup.

### LOCINT (Location Intelligence)
Advanced Geographic Exploration Module: - Image Processing AI: Uses YOLO for object detection (buildings, signs, landmarks) and CLIP for visual semantic matching. - Geolocation: Neural network-based image positioning and cross-referencing with Mapillary/WISE visual similarity engines. - Solar Telemetry: EXIF ​​timestamps and mathematical calculation of Solar Azimuth/Elevation based on predicted coordinates to verify authenticity. - 3D Exploration: Procedural 3D model generation for Areas of Interest (AOI).

### LIVE MONITOR (Geopolitical Pipeline)
A multi-threaded data acquisition engine monitoring global signals: - GDELT: Real-time acquisition of global news events. - Health/Bio: Biological/health-focused intelligence tracking. - Conflict: War-room-style monitoring of active conflict zones. - Climatic: Environmental data and Gaia-feed integration. - OSINT Aggregator: In-depth monitoring of various OSINT streams.

### Auto Agents (m0nk)
Autonomous AI agents (M0nk Engine) perform the following operations: - Analyze natural language-based targets. - Develop search strategies. - Conduct multi-step searches between SOCMINT and Webint modules. - Synthesize findings into executive summaries.

## Technical Stack
![App Screenshot](https://beeimg.com/images/k45004081663.png)

## DEMO
![App Screenshot](https://s13.gifyu.com/images/bq17j.gif)
## Installation

Buy licence and download Sensei from its official website.

[![portfolio](https://beeimg.com/images/o81984283104.png)](https://mwerk.co/)
    
## 🔗 Links
[![portfolio](https://beeimg.com/images/z12551455333.png)](https://x.com/mwerkco)
