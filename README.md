Data Science & AI Portfolio
Applied machine learning, agentic AI and analytics. Each project states the
business problem, the approach, the measured result, and the limitations.
Adewale Falade — data, analytics and AI for climate finance, MRV, market
systems and development finance. 14+ years across Africa and the Middle East.
LinkedIn · adewale.falad@gmail.com
---
Applied AI & GenAI
Project	What it does	Stack	Result
AI-Powered Last-Mile Delivery	Multi-agent system that triages, resolves, communicates and escalates delivery exceptions. Hub-and-spoke architecture with a Critic agent, playbook citations on every decision, and PII isolation so only the Communication agent ever sees the customer's name.	LangGraph, LLM tool-calling	80% task completion · 100% tool-call accuracy · ~1000x speedup on routine events
EHR Assistant Agent	Patient-facing agent that explains lab results, medications and visit summaries in plain language, behind a safety layer that refuses to diagnose, adjust medication or calculate doses, and escalates emergencies.	LangGraph, LangChain, GPT-4o, SQLite	Safety-gated: every request passes a policy check before tool access
RAG Document Assistant	Question answering over a PDF. Retrieves the most relevant passages and grounds the answer in the source rather than the model's memory, reducing hallucination.	LangChain, ChromaDB, OpenAI embeddings, GPT-4o	Grounded answers traceable to source passages
Machine Learning & Analytics
Project	Problem	Approach	Result
Visa Certification	Predict whether a US work-visa application is certified or denied, and surface what drives the decision. 25,480 applications, class-imbalanced.	Bagging, Random Forest, AdaBoost, Gradient Boosting, XGBoost. GridSearchCV tuned on F1.	Tuned XGBoost, F1 ≈ 0.85, strongest recall. Education, prior experience and wage band dominate.
Hotel Booking Cancellation	INN Hotels was losing revenue to last-minute cancellations. Flag high-risk bookings in advance. 36,275 bookings.	Logistic regression (statsmodels) and a pruned decision tree, with threshold tuning.	Lead time is the strongest predictor. Repeat guests, offline bookings and special requests lower cancellation risk.
ReCell	Price used and refurbished phones from their specifications, so the business can price inventory and decide what is worth buying.	OLS linear regression with full diagnostics, VIF multicollinearity handling, assumption testing.	Interpretable pricing model identifying the specs that drive resale value
Stock Market Clustering	Group ~340 S&P 500 stocks into segments with similar financial behaviour, to support diversification rather than isolated stock picking.	Unsupervised learning across price, volatility, ROE, cash ratio, EPS, P/E, P/B and sector.	Natural market segments for portfolio construction and risk management
New Wheels	A vehicle-resale company's orders and ratings were falling quarter on quarter. Find where the business was losing ground.	SQL across customer, order, product and shipper tables. Joins, window functions, conditional aggregation, date math.	Ten-query quarterly report covering customers, products, feedback, revenue and fulfilment
---
Stack
Languages & data · Python (pandas, NumPy, scikit-learn, statsmodels, XGBoost), SQL, Jupyter
AI · LangChain, LangGraph, RAG, agentic workflows, tool-calling, prompt engineering
Analytics & BI · Power BI, Tableau, Advanced Excel, Stata, SPSS
Geospatial · ArcGIS
---
Running the notebooks
```bash
git clone https://github.com/adewalefalade1/Data-Science-AI-Portfolio
cd Data-Science-AI-Portfolio
pip install -r requirements.txt
```
Projects that call an LLM need an API key. Copy `.env.example` to `.env` and add
your own. `.env` is gitignored and must never be committed.
```bash
cp .env.example .env
```
---
About
14+ years building measurement systems, analytics and financial models across
Africa and the Middle East, for USAID, FCDO, SIDA, the Gates Foundation, GIZ and
ECHO, and for commercial clients. Currently focused on climate finance MRV and
disclosure (ISSB / IFRS S1 and S2, SASB, PCAF, SBTi), and on applying LLM systems
to decision support.
LinkedIn
