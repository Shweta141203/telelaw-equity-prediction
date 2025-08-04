<!-- README Banner -->
<h1 align="center">📖 Tele-Law Equity Predictor</h1>
<p align="center">✨ An IBM Cloud + AutoAI project by <b>Shweta Nautiyal</b> ✨</p>
<p align="center"><i>Predicting regional and demographic equity in legal aid access across Indian districts 🧠📊</i></p>

---

## 🌟 Project Overview

Even though India's Tele-Law initiative is expanding, **not everyone is being served equally**.  
This project uses **real case registration data** to uncover **gender-wise, caste-wise, and district-wise gaps** in legal aid access — especially for women and marginalized groups (SC, ST, OBC).  

With the power of **IBM Cloud + AutoAI**, I built a system that tells us:
> 🗺️ *"Which districts are falling behind in fairness — and where should help go next?"*

---

## 💡 What Makes It Special

✔️ Built **end-to-end on IBM Cloud** (Data Refinery → AutoAI → Deployed Model)  
✔️ Focused on **equity, inclusiveness, and real social impact**  
✔️ Uses **clean, smart features** like % of female participation and caste representation  
✔️ Gives **clear predictions** with confidence scores

---

## 🧠 What the Model Predicts

It answers:  
🎯 *“Is this district showing signs of low equity in Tele-Law access?”*

### 🔍 Inputs:
- `Percent_Female`
- `Percent_SC`, `ST`, `OBC`
- `Cases_per_CSC` (service load)

### 📤 Output:
- `Low_Equity = 1` → This district may need more outreach 💬  
- `Low_Equity = 0` → Access looks fairly balanced ✅  
- Plus a **confidence score** (e.g., 0.83 = 83% sure it's low equity)

---

## 🛠 Tech Stack

| Tool | Role |
|------|------|
| 🧼 IBM Data Refinery | Cleaned and processed data (calculated %s, created labels)  
| ⚙️ IBM AutoAI        | Automatically trained multiple ML models and picked the best  
| 🚀 IBM Watson ML     | Deployed the model for real-time testing  
| ☁️ IBM Cloud Object Storage | Stored raw + cleaned data  
| 🧾 GitHub            | Hosting this beautiful project 💖

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `Telelaw_Prediction.pptx` | My final presentation slides 🎤  
| `telelaw_cleaned.csv`     | Cleaned dataset with engineered features  
| `prediction_output.png`   | Screenshot of the deployed model’s prediction 🔮  
| `README.md`               | This magical write-up 🌟

---

## 🌱 Future Scope

- Add socio-economic indicators (education, internet access)
- Visualize equity scores on **district-level maps** 🗺️
- Make a public-facing web app for decision-makers and NGOs
- Apply the same idea to other government welfare schemes

---

## 💖 About Me

Hi! I’m **Shweta Nautiyal**,  
a B.Tech student at *Sunderdeep Group of Institutions* 🎓  
A thinker who loves mixing **tech with heart**, and building solutions that can actually help people.

- 👩‍💻 I love learning by doing (this is one of my first end-to-end ML projects!)  
- 💫 I believe tech should be **inclusive, empowering, and human**    

---

## 📚 References

- [IBM AutoAI Docs](https://www.ibm.com/cloud/watson-studio/autoai)  
- [Tele-Law Official Website](https://tele-law.in/)  
- [IBM Watson Studio](https://dataplatform.cloud.ibm.com/)  
- Dataset Source: [https://www.data.gov.in/resource/district-wise-tele-law-case-registration-and-advice-enabled-data-fy-2021-22-2024-25]

---

<h3 align="center">🌸 Thank you for reading! 🌸</h3>
<p align="center">Let’s build a more fair, inclusive world — one model at a time 💫</p>
