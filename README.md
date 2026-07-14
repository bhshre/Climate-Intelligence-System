# Climate Intelligence System: Hybrid Time-Series Forecasting of Global Temperature Using SARIMA, XGBoost & LSTM

A Unified Predictive Framework Incorporating Multivariate Anthropogenic and Meteorological Forcing Drivers. This major project establishes an end-to-end data engineering and modeling pipeline deployed as an interactive analytical web application to advance **UN Sustainable Development Goal 13: Climate Action**.

---

##  Candidacy Identification
* **Presenter:** Shreya Bhattacharjee  
* **Degree:** Master of Science in Data Science (2024 – 2026)  
* **Project Supervisor:** Prof. Madhurima Paul  
* **Department:** Department of Computing and Analytics  
* **Institution:** Bhawanipur Global Campus / NSHM Knowledge Campus, Kolkata  
* **Affiliation:** Maulana Abul Kalam Azad University of Technology (MAKAUT), West Bengal  

---

##  Core Research Objectives
* **Multivariate Stream Consolidation:** Integrate asynchronous, heterogeneous environmental tracking streams into a unified monthly matrix core.
* **Hybrid Modeling Framework:** Formulate a parallel-execution algorithmic block fusing linear statistical forecasting, gradient-boosted tabular decision trees, and sequential recurrent neural networks.
* **Accuracy Optimization:** Minimize forecast prediction error metrics to capture seasonal atmospheric patterns alongside non-linear structural shocks.
* **Deployment & Public Access:** Wrap complex data modeling inside an intuitive user-facing web dashboard served securely over cloud proxy networks.

---

##  System Architecture & Five-Layer Pipeline
1. **Layer 1: Data Engineering Layer:** Ingesting global surface temperatures, industrial carbon footprint data ($CO_2$ kilotons), regional atmospheric vectors, and sea-level rise variations. Standardizes time signatures into standard `Datetime64` columns, applies monthly aggregation smoothers, and executes structural timeline left-joins.
2. **Layer 2: Feature Engineering & Context Generation:** Crafting historical lag arrays ($T_{-1}$, $T_{-3}$), monthly rolling window statistics (3 & 6-month averages) to filter noisy weather spikes, and cyclical calendar month identifiers.
3. **Layer 3: Parallel Modeling Engine:** Simulating historical baseline cycles via **SARIMA**, tracking complex tabular variable reactions via an optimized **XGBoost Regressor**, and retaining deep chronological sequential dependencies through an advanced **LSTM Neural Network**.
4. **Layer 4: Empirical Evaluation Layer:** Validating predictions against ground-truth data points utilizing Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and Coefficient of Determination ($R^2$ Score) tracking matrices.
5. **Layer 5: Production Dashboard Layer:** Exposing multi-model horizon projections onto a cross-device responsive web utility engineered via **Streamlit** and proxied instantly through secure **Cloudflare Tunnels**.

---

##  Empirical Validation Matrix & Diagnostic Insights
Through rigorous cross-validation checks, individual architectural nodes registered the following performance indicators:

| Model Architecture Configuration | RMSE (Lower = Better) | MAE (Lower = Better) | $R^2$ Score (Higher = Better) | Deployment Status |
| :--- | :---: | :---: | :---: | :---: |
| **SARIMA Baseline Model** | **0.3412** | **0.2811** | **98.71%** | 🟢 Active Production |
| **XGBoost Regressor** | **0.5721** | **0.4519** | **96.40%** | 🟢 Active Production |
| **LSTM Deep Learning Network** | *1,329,122.0* | *1,164,033.0* | *-1.91 × 10¹¹%* | 🔴 Isolated (Data Boundary Collapse) |

>  **Critical Pipeline Discovery Note:** During validation checks, the LSTM sequence node suffered a numerical breakdown due to data scaling imbalances across a sudden historical step boundary. Because the model weights skewed exponentially, it was cleanly isolated from the final live prediction layer, allowing the robust SARIMA and XGBoost components to drive the production dashboard with maximum stability.

---

##  Live Production Dashboard Interface View

### 1. Key Performance Metrics Scorecard Panel
Displays responsive real-time accuracy percentages, system tracking performance updates, and historical deviation counters.
![Dashboard Performance Metrics](<img width="1317" height="495" alt="Screenshot 2026-07-11 013212" src="https://github.com/user-attachments/assets/ecc5391e-2255-4d56-a9f1-ce5ae890fa1c" />
)

### 2. Multi-Step Temperature Projection Horizon Canvas
Visualizes a high-fidelity interactive vector timeline mapping real-world target records tightly against forecasted trace patterns.
![Interactive Forecasting Timeline Horizon](<img width="1253" height="571" alt="Screenshot 2026-07-11 013228" src="https://github.com/user-attachments/assets/669b5e26-18d2-4043-b8fe-b83c164c4bda" />
)

### 3. Integrated Analytical Model Matrix Tabular Sheet
Provides an accessible scoreboard view sorting errors side-by-side to enable quick data verification loops for non-technical stakeholders.
![Model Performance Comparison Matrix](<img width="1269" height="335" alt="Screenshot 2026-07-11 013245" src="https://github.com/user-attachments/assets/790f95a5-7151-4b6e-a604-a149dee04738" />
)

---

##  Repository File Directory Configuration
* `datasets/` — Directory containing historical environmental attribute registers.
  *  *Note: The dataset file uploaded inside this folder is an optimized sample preview (limited to the first 150 rows) to fulfill strict cloud hosting file upload bounds while fully maintaining baseline column headers and formatting structure.*
* `screenshots/` — Assets directory embedding UI verification snapshots.
* `Climate_Intelligence_System_...ipynb` — Fully documented Jupyter source code notebook featuring raw training steps, missing index interpolations, hyperparameter optimization models, and error validation metrics.
* `Climate_Intelligence_System_Major_Project_Report.docx` — Complete, master-level academic research documentation and comprehensive thesis text.

---

##  Execution & Local Deployment Instructions
To host the analytical dashboard engine within a localized workspace loop, initialize the terminal sequence below:

```bash
# 1. Clone this repository to your machine
git clone [https://github.com/YOUR_USERNAME/Climate-Intelligence-System.git](https://github.com/YOUR_USERNAME/Climate-Intelligence-System.git)

# 2. Enter the active repository directory path
cd Climate-Intelligence-System

# 3. Download and install all structural software dependancies
pip install streamlit pandas numpy statsmodels xgboost tensorflow plotly matplotlib

# 4. Trigger the multithreaded Streamlit live execution client
streamlit run app.py
