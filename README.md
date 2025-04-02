
# System Design Assistant — Version 4.0

An interactive Streamlit-based tool designed to help you plan, evaluate, and present scalable system architectures — perfect for system design interviews or real-world capacity planning.

## 🚀 Features

- 🔄 **Problem Type Selector**: Choose from common system categories like General, LLM Chatbot, Financial App, AV Platform, and more
- ✅ **"Use Default" Toggles**: Focus only on inputs your interviewer gives you; everything else is intelligently defaulted
- 📐 **Unit Selection**: Supports KB/MB/GB, sec/min, Mbps/Gbps — with validation
- 📊 **Live Capacity Estimation**: QPS, storage, bandwidth calculated in real time
- 🏗️ **Dynamic Architecture Generator**: Layered suggestions based on toggles + problem type
- ⚖️ **Trade-off Reasoning**: Adaptive CAP/PACELC insights + cost/latency/consistency analysis
- 🧠 **Interview Walkthrough Mode**: Generate a structured verbal explanation of your design
- 📁 **Export**: Download summary as CSV
- 🎨 **Streamlit Custom Theme** for clean UI

---

## 🧑‍💻 How to Run Locally

```bash
pip install -r requirements.txt
streamlit run system_design_tool_app_v4.py
```

> Make sure your folder includes:
> - `system_design_tool_app_v4.py`
> - `requirements.txt`
> - `.streamlit/config.toml`
> - `README.md`
> - `.gitignore`

---

## 🌐 Deploy to Streamlit Cloud

1. Push this folder to a GitHub repo
2. Go to [streamlit.io/cloud](https://streamlit.io/cloud)
3. Select your repo
4. Set **main file path** to:

```
system_design_tool_app_v4.py
```

5. Click **Deploy**

---

## 📂 Project Structure

```
.
├── system_design_tool_app_v4.py     # Main interactive app
├── requirements.txt                 # Dependencies
├── README.md                        # This file
├── .gitignore                       # Python + Streamlit ignores
└── .streamlit/
    └── config.toml                  # Theme customization
```

---

## 🧠 Ideal Use Cases

- Live technical interviews (TPM, Eng, Architect)
- Internal architecture planning
- Lightweight POCs for design proposals
- Teaching system design concepts

---

## 🙌 Credits

Created using [Streamlit](https://streamlit.io/) and community feedback to make system design thinking faster and clearer.
