<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/profile-banner-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/profile-banner.svg">
    <img alt="Sreekar — Software Engineering / Generative AI / Machine Learning" src="assets/profile-banner.svg" width="100%">
  </picture>
</p>

<p align="center">
  <strong>Tirumala Sai Raghava Sreekar</strong> &nbsp;·&nbsp; 
  <code>IIITDM Kancheepuram</code> &nbsp;·&nbsp; 
  <code>Chennai, India</code> &nbsp;·&nbsp; 
  <a href="mailto:sreekartirumala0706@gmail.com">sreekartirumala0706@gmail.com</a>
</p>

<p align="center">
  <a href="#-architectural-focus">Focus</a> &nbsp;·&nbsp;
  <a href="#-featured-systems">Featured Systems</a> &nbsp;·&nbsp;
  <a href="#-complete-systems--applied-ml-portfolio">Complete Portfolio</a> &nbsp;·&nbsp;
  <a href="#-technical-toolkit">Toolkit</a> &nbsp;·&nbsp;
  <a href="#-active-research-vectors">Research</a> &nbsp;·&nbsp;
  <a href="#-engineering-principles">Principles</a> &nbsp;·&nbsp;
  <a href="#-connect">Contact</a>
</p>

---

### 00 // Architectural Focus

I am a software engineer and researcher at **IIITDM Kancheepuram** building intelligent software systems across the abstraction stack. My work spans **production Generative AI & tool-calling agent pipelines**, **deep learning with Vision Transformers for remote sensing**, and **systems programming & computer architecture simulation**.

I approach software from first principles: understanding low-level memory latency, operating system primitives, and mathematical attention mechanisms before constructing application layers. I build robust, measurable software—whether implementing process tracing inside the xv6 Unix kernel or serving sub-second RAG retrieval over dense video transcripts.

---

### 01 // Featured Systems

<table>
  <thead>
    <tr>
      <th width="50%">System &amp; Architecture</th>
      <th width="50%">Key Engineering Highlights</th>
    </tr>
  </thead>
  <tbody>
    <!-- Project 1: YouTube Sage -->
    <tr>
      <td valign="top">
        <h4><a href="https://github.com/Sreekar-2612/Youtube-Sage">YouTube Sage</a> &nbsp;<code>GenAI / RAG / Agents</code></h4>
        <p><strong>Multi-Modal Video RAG &amp; Agentic Transcript Synthesis Engine</strong></p>
        <p>A production-ready retrieval-augmented generation platform that ingests full-length YouTube transcripts, indexes semantic chunks into vector storage, and powers autonomous tool-calling agents for contextual Q&amp;A and automated chapter synthesis.</p>
        <p>
          <a href="https://youyap.vercel.app"><b>Live App: youyap.vercel.app</b></a> &nbsp;|&nbsp; 
          <a href="https://github.com/Sreekar-2612/Youtube-Sage"><b>Repository</b></a>
        </p>
        <p>
          <code>LangChain LCEL</code> &nbsp; <code>FastAPI</code> &nbsp; <code>Groq LPU (Llama-3)</code> &nbsp; <code>Hugging Face</code> &nbsp; <code>FAISS</code> &nbsp; <code>React</code>
        </p>
      </td>
      <td valign="top">
        <ul>
          <li><strong>Dual Inference Architecture:</strong> Integrated Groq LPUs for sub-second conversational generation alongside Hugging Face model endpoints for flexible open-weight embedding fallback.</li>
          <li><strong>Tool-Calling Agent Runtime:</strong> Implemented LangChain agents equipped with dynamic tools (<code>search_transcript</code>, recursive chunk summary) with conversational memory.</li>
          <li><strong>Optimized Retrieval Pipeline:</strong> Custom recursive character splitting with timestamp preservation and vector similarity search across high-density transcript embeddings.</li>
          <li><strong>Decoupled Service Model:</strong> RESTful FastAPI session-mapped backend containerized with Docker, communicating with a responsive React frontend.</li>
        </ul>
      </td>
    </tr>
    <!-- Project 2: CivicLens -->
    <tr>
      <td valign="top">
        <h4><a href="https://github.com/Sreekar-2612/CivicLens">CivicLens (QuickSort)</a> &nbsp;<code>Infrastructure OS / GIS</code></h4>
        <p><strong>Civic-Tech Infrastructure Operating System &amp; Spatial Registry</strong></p>
        <p>An enterprise-grade coordination platform designed to align municipal excavation schedules, eliminate redundant road-cutting, and coordinate public works departments, contractors, and residents through a single unified geospatial interface.</p>
        <p>
          <a href="https://quicksort-civiclens.vercel.app/"><b>Live App: quicksort-civiclens.vercel.app</b></a> &nbsp;|&nbsp; 
          <a href="https://github.com/Sreekar-2612/CivicLens"><b>Repository</b></a>
        </p>
        <p>
          <code>React 19</code> &nbsp; <code>TypeScript</code> &nbsp; <code>Supabase (PostgreSQL)</code> &nbsp; <code>Leaflet GIS</code> &nbsp; <code>Vite</code> &nbsp; <code>Recharts</code>
        </p>
      </td>
      <td valign="top">
        <ul>
          <li><strong>Spatial Coordination Engine:</strong> Built interactive multi-layer GIS mapping with Leaflet for geospatial conflict detection across municipal work permits.</li>
          <li><strong>Reactive Architecture:</strong> Engineered responsive client dashboards with React 19, strict TypeScript contracts, and Supabase real-time subscriptions.</li>
          <li><strong>Telemetry &amp; Audit Trail:</strong> Automated project milestone tracking, transparent contractor accountability logs, and interactive telemetry charts with Recharts.</li>
          <li><strong>Modern Toolchain:</strong> Rigorous code quality maintained via Vite, Oxlint, and automated Vitest suites.</li>
        </ul>
      </td>
    </tr>
    <!-- Project 3: SwinGeo -->
    <tr>
      <td valign="top">
        <h4><a href="https://github.com/Sreekar-2612/LAND_SURFACE_TEMPERATURE_PREDICTION_USING_TRANSFORMERS">SwinGeo</a> &nbsp;<code>Deep Learning / Vision Transformers</code></h4>
        <p><strong>Hierarchical Shifted-Window Transformer for Urban Heat Island (UHI) Mapping</strong></p>
        <p>A deep learning research implementation leveraging Swin Transformer architectures to perform high-resolution Land Surface Temperature (LST) regression and microclimate anomaly prediction from multispectral satellite imagery.</p>
        <p>
          <a href="https://github.com/Sreekar-2612/LAND_SURFACE_TEMPERATURE_PREDICTION_USING_TRANSFORMERS"><b>Repository: SwinGeo</b></a>
        </p>
        <p>
          <code>PyTorch 2.0+</code> &nbsp; <code>Swin Transformer</code> &nbsp; <code>Remote Sensing</code> &nbsp; <code>Landsat 8</code> &nbsp; <code>Explainable AI (XAI)</code>
        </p>
      </td>
      <td valign="top">
        <ul>
          <li><strong>Shifted Window Attention:</strong> Adapted hierarchical vision transformers to model cross-patch spatial dependencies in multispectral satellite bands without quadratic compute overhead.</li>
          <li><strong>Radiometric Pipeline:</strong> Ingested Landsat 8 thermal infrared and optical channels; computed spectral vegetation/built-up indices (NDVI, NDBI).</li>
          <li><strong>Explainable AI &amp; Profiling:</strong> Developed integrated attribution tooling and empirical bias correction routines to validate model interpretability against physical ground truth.</li>
          <li><strong>Benchmark Rigor:</strong> Benchmarked regression accuracy against classical baseline algorithms (Random Forests) on HPC compute environments.</li>
        </ul>
      </td>
    </tr>
    <!-- Project 4: MemCentric-Sim -->
    <tr>
      <td valign="top">
        <h4><a href="https://github.com/Sreekar-2612/Memory-Centric-Computing-Dynamic-Scheduling-Simulator">MemCentric-Sim</a> &nbsp;<code>Computer Systems &amp; Architecture</code></h4>
        <p><strong>Memory-Centric Heterogeneous Architecture &amp; Dynamic Scheduling Simulator</strong></p>
        <p>A cycle-level architecture simulator modeling Processing-in-Memory (HBM-PIM) and CXL 2.0 interconnect topologies to evaluate dynamic workload offloading strategies that mitigate the von Neumann memory wall.</p>
        <p>
          <a href="https://github.com/Sreekar-2612/Memory-Centric-Computing-Dynamic-Scheduling-Simulator"><b>Repository: MemCentric-Sim</b></a>
        </p>
        <p>
          <code>Python 3.10+</code> &nbsp; <code>CXL 2.0 / PIM</code> &nbsp; <code>Cache Hierarchy</code> &nbsp; <code>DRAM Banks</code> &nbsp; <code>Architecture Sim</code>
        </p>
      </td>
      <td valign="top">
        <ul>
          <li><strong>Heterogeneous Memory Modeling:</strong> Simulated multi-tier memory subsystems including L1/L2 caches, DRAM banks, HBM-PIM computational units, and CXL interconnect latency.</li>
          <li><strong>Dynamic Workload Scheduler:</strong> Formulated scheduling heuristics that dynamically route compute-heavy vs. memory-bound tasks to host cores or in-memory logic.</li>
          <li><strong>Bottleneck Mitigation:</strong> Quantified data-movement energy reductions and speedups across diverse synthetic and trace-driven memory access patterns.</li>
          <li><strong>IEEE/ACM Micro Standards:</strong> Structured modular evaluation harness, automated verification suite (100% test pass rate), and publication-grade academic reporting.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---

### 02 // Complete Systems & Applied ML Portfolio

Every repository reflects verified engineering investigations, systems implementations, or empirical research:

<table>
  <thead>
    <tr>
      <th width="32%">Category &amp; Domain</th>
      <th width="36%">Repository &amp; System</th>
      <th width="32%">Core Technical Stack</th>
    </tr>
  </thead>
  <tbody>
    <!-- Systems & OS Internals -->
    <tr>
      <td rowspan="3"><strong>01 / Systems, OS &amp; Networks</strong><br><em>Low-level primitives, kernel tracing &amp; socket engines</em></td>
      <td><a href="https://github.com/Sreekar-2612/Kernel_Logging"><strong>Kernel_Logging</strong></a><br>Kernel-level logging, system call tracing, and process instrumentation inside xv6 Unix.</td>
      <td><code>C</code> · <code>xv6 Unix OS</code> · <code>Systems Programming</code> · <code>GDB</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/Sreekar-2612/VIDEO-CONFERENCING-APPLICATION-WORKING-ON-LOCAL-AREA-NETWORK"><strong>LAN Video Conferencing Engine</strong></a><br>Zero-internet collaboration system: real-time audio/video streaming &amp; LAN file sharing.</td>
      <td><code>Python</code> · <code>Socket Programming</code> · <code>Multithreading</code> · <code>OpenCV</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/Sreekar-2612/CN_PROJECT"><strong>CN_PROJECT</strong></a><br>Computer networking communication protocols and socket transmission routines.</td>
      <td><code>Python / C</code> · <code>TCP/IP</code> · <code>Socket API</code> · <code>Packet Analysis</code></td>
    </tr>
    <!-- Computer Vision & Deep Learning -->
    <tr>
      <td rowspan="4"><strong>02 / Deep Learning &amp; Vision</strong><br><em>Transformers, remote sensing &amp; biomedical AI</em></td>
      <td><a href="https://github.com/Sreekar-2612/Urban_Hotspots_Prediction_Using_VisionTransformer"><strong>Urban Hotspots Prediction</strong></a><br>Deep learning pipeline predicting urban thermal hotspots via CNNs and Landsat 8 satellite data.</td>
      <td><code>Python</code> · <code>PyTorch</code> · <code>Landsat 8</code> · <code>NDVI / NDBI Spectral Indices</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/Sreekar-2612/BRAIN_TUMOR_SEGMENTATION_USING_CLIP_ARCHITECTURE"><strong>Brain Tumor Segmentation via CLIP</strong></a><br>Zero-shot and fine-tuned biomedical segmentation leveraging vision-language alignment.</td>
      <td><code>Python</code> · <code>PyTorch</code> · <code>OpenAI CLIP</code> · <code>Medical Imaging</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/Sreekar-2612/Geospatial-Classification-Framework"><strong>Geospatial Classification Framework</strong></a><br>Multi-spectral satellite image categorization and land-use segmentation pipelines.</td>
      <td><code>Jupyter</code> · <code>Scikit-Learn</code> · <code>Rasterio</code> · <code>Geospatial Analysis</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/Sreekar-2612/End-to-End-Convolutional-Neural-Network-for-Fashion-MNIST-Classification-Using-PyTorch"><strong>Fashion-MNIST CNN Pipeline</strong></a><br>Modular convolutional neural network pipeline with training checkpoints and evaluation curves.</td>
      <td><code>PyTorch</code> · <code>Torchvision</code> · <code>CNN Architecture</code> · <code>Python</code></td>
    </tr>
    <!-- Clinical AI & Predictive Analytics -->
    <tr>
      <td rowspan="4"><strong>03 / Predictive Modeling &amp; ML</strong><br><em>Clinical anomaly detection &amp; time-series forecasting</em></td>
      <td><a href="https://github.com/Sreekar-2612/Multi-Vital-Sepsis-Monitor"><strong>Multi-Vital Sepsis Monitor</strong></a><br>Personalized early-warning sepsis detection utilizing multi-vital clinical time-series anomalies.</td>
      <td><code>Python</code> · <code>Clinical ML</code> · <code>Anomaly Detection</code> · <code>Feature Engineering</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/Sreekar-2612/hetnet-traffic-forecast"><strong>HetNet Traffic Forecast</strong></a><br>Predictive traffic load modeling for heterogeneous 4G/5G telecommunication networks.</td>
      <td><code>Python</code> · <code>Time-Series Forecasting</code> · <code>Pandas</code> · <code>Scikit-Learn</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/Sreekar-2612/Diabetes-Prediction-Using-Pytorch"><strong>Diabetes Prediction with PyTorch</strong></a><br>Deep learning feedforward network for clinical diagnostic risk assessment.</td>
      <td><code>PyTorch</code> · <code>Binary Classification</code> · <code>Tabular ML</code> · <code>Python</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/Sreekar-2612/Space-decay-prediction-machine-learning-project"><strong>Space Decay Trajectory Prediction</strong></a><br>Orbital decay analysis modeling satellite atmospheric re-entry profiles.</td>
      <td><code>Python</code> · <code>Regression Modeling</code> · <code>Orbital Mechanics</code> · <code>Pandas</code></td>
    </tr>
    <!-- Full-Stack, Mobile & Platforms -->
    <tr>
      <td rowspan="5"><strong>04 / Full-Stack &amp; Platforms</strong><br><em>Web applications, mobile software &amp; services</em></td>
      <td><a href="https://github.com/Sreekar-2612/TEAM_FORGE"><strong>TEAM_FORGE</strong></a><br>Collaborative team formation and project management platform. <a href="https://team-forge-backend-nine.vercel.app"><em>(Live Backend)</em></a></td>
      <td><code>JavaScript</code> · <code>Node.js</code> · <code>Express</code> · <code>REST API</code> · <code>Vercel</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/Sreekar-2612/FacultyAPP"><strong>FacultyAPP</strong></a><br>Native Android mobile application streamlining faculty schedules, student requests, and notices.</td>
      <td><code>Kotlin</code> · <code>Android SDK</code> · <code>Mobile Architecture</code> · <code>Material Design</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/Sreekar-2612/futura-fintech"><strong>Futura Fintech</strong></a><br>Financial operations dashboard and modern digital transaction interface. <a href="https://digital-rebel.vercel.app"><em>(Live Interface)</em></a></td>
      <td><code>JavaScript / React</code> · <code>Fintech UI</code> · <code>Vercel</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/Sreekar-2612/restaurant-management-system"><strong>Restaurant Management System</strong></a><br>Structured multi-tier ordering, billing, and inventory tracking application.</td>
      <td><code>Java / Web</code> · <code>Database Management</code> · <code>CRUD Workflows</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/Sreekar-2612/urban-service-intelligence"><strong>Urban Service Intelligence</strong></a><br>Integrated municipal asset analytics and urban maintenance workflow automation.</td>
      <td><code>Python</code> · <code>Data Processing</code> · <code>Urban Computing</code></td>
    </tr>
    <!-- Algorithmic & Empirical Foundations -->
    <tr>
      <td rowspan="5"><strong>05 / Algorithms &amp; Foundations</strong><br><em>Problem solving, NLP &amp; exploratory data science</em></td>
      <td><a href="https://github.com/Sreekar-2612/neetcode-submissions"><strong>NeetCode Submissions</strong></a><br>Verified algorithmic problem solutions across dynamic programming, graphs, trees, and heaps.</td>
      <td><code>Python</code> · <code>Data Structures &amp; Algorithms</code> · <code>Complexity Optimization</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/Sreekar-2612/email-spam-detection"><strong>Email Spam Detection</strong></a><br>Natural language processing text vectorization and probabilistic spam filtering.</td>
      <td><code>Python</code> · <code>NLP</code> · <code>TF-IDF / Naive Bayes</code> · <code>Scikit-Learn</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/Sreekar-2612/COVID-19-Data-Visualization-Analysis"><strong>COVID-19 Data Analytics</strong></a><br>Epidemiological transmission trend analysis and geographic statistical charts.</td>
      <td><code>Python</code> · <code>Matplotlib</code> · <code>Seaborn</code> · <code>Data Visualization</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/Sreekar-2612/Netflix-Data-Analysis"><strong>Netflix Catalog Analysis</strong></a><br>Content distribution, regional releases, and genre clustering exploratory study.</td>
      <td><code>Python</code> · <code>Pandas</code> · <code>Exploratory Data Analysis (EDA)</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/Sreekar-2612/Coursera-Machine-Learning-Stanford"><strong>Stanford Machine Learning Foundations</strong></a><br>Mathematical implementations of gradient descent, neural networks, SVMs, and PCA.</td>
      <td><code>Octave / MATLAB / Python</code> · <code>Linear Algebra</code> · <code>Optimization Theory</code></td>
    </tr>
  </tbody>
</table>

---

### 03 // Technical Toolkit

A balanced engineering repertoire grounded in systems programming, machine learning research, and modern web application development:

<table>
  <thead>
    <tr>
      <th width="25%">Discipline</th>
      <th width="75%">Technologies &amp; Methodologies</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Core Languages</strong></td>
      <td>
        <code>Python 3.x</code> &nbsp; <code>C</code> &nbsp; <code>C++</code> &nbsp; <code>TypeScript</code> &nbsp; <code>JavaScript (ESNext)</code> &nbsp; <code>Kotlin</code> &nbsp; <code>SQL (PostgreSQL)</code>
      </td>
    </tr>
    <tr>
      <td><strong>Generative AI &amp; LLMs</strong></td>
      <td>
        <code>LangChain (LCEL)</code> &nbsp; <code>Tool-Calling Agents</code> &nbsp; <code>FAISS Vector Index</code> &nbsp; <code>Hugging Face Hub</code> &nbsp; <code>Sentence Transformers</code> &nbsp; <code>Groq LPU Hardware Acceleration</code> &nbsp; <code>Contextual RAG Architectures</code>
      </td>
    </tr>
    <tr>
      <td><strong>Machine Learning &amp; Vision</strong></td>
      <td>
        <code>PyTorch 2.x</code> &nbsp; <code>Vision Transformers (Swin / ViT)</code> &nbsp; <code>CLIP Architectures</code> &nbsp; <code>Convolutional Neural Networks (CNNs)</code> &nbsp; <code>Scikit-Learn</code> &nbsp; <code>Explainable AI (XAI)</code> &nbsp; <code>Multispectral Satellite Telemetry (Landsat 8)</code>
      </td>
    </tr>
    <tr>
      <td><strong>Computer Systems &amp; Low-Level</strong></td>
      <td>
        <code>xv6 Unix Kernel Programming</code> &nbsp; <code>CXL 2.0 Interconnects</code> &nbsp; <code>HBM Processing-in-Memory (PIM) Simulation</code> &nbsp; <code>Multi-Threaded POSIX Socket Networking</code> &nbsp; <code>Memory Hierarchy &amp; Cache Modeling</code> &nbsp; <code>Linux / GDB Internals</code>
      </td>
    </tr>
    <tr>
      <td><strong>Full-Stack &amp; Production</strong></td>
      <td>
        <code>React 19</code> &nbsp; <code>FastAPI</code> &nbsp; <code>Node.js</code> &nbsp; <code>Vite</code> &nbsp; <code>Supabase (PostgreSQL / Edge Functions)</code> &nbsp; <code>Leaflet GIS</code> &nbsp; <code>Docker</code> &nbsp; <code>Vitest / Oxlint</code> &nbsp; <code>Git / GitHub Actions</code> &nbsp; <code>Vercel Cloud</code>
      </td>
    </tr>
  </tbody>
</table>

---

### 04 // Active Research Vectors

I am actively investigating the intersection of low-latency intelligent systems, distributed computing, and computer vision:

- **Sub-Second Multi-Modal Agent Orchestration:** Exploring speculative decoding, asynchronous tool-calling graphs, and quantized local inference to minimize round-trip latencies in conversational video synthesis.
- **Hierarchical Attention on High-Dimension Earth Observation Data:** Adapting shifted-window vision transformer variants to fuse thermal infrared, SAR, and optical earth observation data for microclimate hazard forecasting.
- **Memory-Centric Dynamic Offloading in Heterogeneous Runtimes:** Designing scheduling heuristics for CXL-attached memory accelerators to minimize bandwidth contention in LLM inference caches.

---

### 05 // Engineering Principles

1. **First-Principles Rigor Over Black-Box Intuition:** Understand how data moves across the physical bus, through the kernel socket buffers, and into the GPU memory pool. If you cannot explain the hardware or runtime cost, the abstraction is unproven.
2. **Production Viability Over Synthetic Demos:** Toy scripts are easy to show; resilient systems are hard to break. I prioritize typed API boundaries, comprehensive error isolation, real-world datasets, and measurable latency benchmarks.
3. **Restrained, Purposeful Craft:** From code organization to user interface design, clarity is paramount. Eliminate visual noise, superfluous dependencies, and speculative complexity. Let the function dictate the form.

---

### 06 // Connect &amp; Collaborate

I welcome discussions regarding engineering roles, systems research, Generative AI infrastructure, and collaborative open-source development:

- **Email:** <a href="mailto:sreekartirumala0706@gmail.com"><code>sreekartirumala0706@gmail.com</code></a>
- **GitHub:** <a href="https://github.com/Sreekar-2612"><code>@Sreekar-2612</code></a>
- **Academic Affiliation:** Indian Institute of Information Technology, Design and Manufacturing (IIITDM), Kancheepuram
- **Location:** Chennai, Tamil Nadu, India

<br>

<p align="center">
  <sub>Designed with the Swiss International Typographic System · Monospace Precision · Verified Implementations</sub>
</p>
