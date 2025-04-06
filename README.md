# solmate

# ☀️ Solar Investment Planning Tool

An AI-powered web application that helps users analyze rooftop solar potential, estimate government subsidies, and plan solar panel investments with data-driven insights. The tool uses NASA's solar irradiance data, user inputs, and rooftop analysis to generate a detailed report including ROI, payback period, and energy savings.

---

## 🔍 Features

- 🧠 **AI-based Rooftop Analysis**: Upload roof images to detect obstructions, assess orientation, and evaluate suitability.
- 🌐 **Location-based Solar Data**: Integrates with the **NASA POWER API** to fetch real-time solar radiation and weather info.
- 📊 **Custom Investment Planning**:
  - Panel count estimation
  - Annual energy output
  - Cost savings over time
  - ROI & payback period visualization
- 💰 **Subsidy Estimation**: Suggests central/state government subsidies based on current policies.
- 📄 **Personalized Report**: Generates downloadable PDF with your investment summary.

---

## 🚀 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask)
- **AI/ML**: OpenCV, Image Processing
- **Data Source**: [NASA POWER API](https://power.larc.nasa.gov/)
- **PDF Reports**: Python libraries like `reportlab` or `xhtml2pdf`

---

## 📥 How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/solar-panel-tool.git
   cd solar-panel-tool
