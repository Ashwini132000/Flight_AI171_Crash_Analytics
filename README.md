# ✈️ Air India Flight AI171 Crash Analytics  

This notebook presents a **fact-based, respectful analytical review** of the tragic crash of **Air India Flight AI171**, which occurred on **June 12, 2025**, shortly after takeoff from **Sardar Vallabhbhai Patel International Airport, Ahmedabad**. The aircraft, a **Boeing 787-8 Dreamliner**, was en route to **London Gatwick** and crashed within a minute of takeoff, resulting in a **major loss of life.**  

The purpose of this notebook is purely educational and analytical. It uses **publicly available data and media reports** to structure and examine the available information.  

![Screenshot 2025-07-10 002924](https://github.com/user-attachments/assets/573cbcb6-708d-4d11-a0bb-a8a829a9acbf)  

---  

## 📊 This analysis includes:   
🗂️ Key incident details  
⚰️ Casualty and survival statistics  
🚨 Emergency response timelines and resources  
✈️ Pilot experience and qualification context  
📣 Public and official statements  
📈 Data visualizations for impact understanding  

---  

## 🎯 Objective  

To explore the **incident using data science methods and derive insights into emergency readiness, aviation safety protocols**, and potential areas of improvement — in the **public interest**, and with full respect to all individuals involved.  

---  

## ⚠️ Disclaimer  

This analysis is based solely on information reported publicly as of June 2025. It is **not an official investigation**, and all interpretations are made with **respect and neutrality**. No part of this notebook should be construed as assigning blame or drawing conclusions on behalf of investigative authorities.  

---  

## 🗂️ Key Incident Details  

```
incident_data = { "Flight Number": ["AI171"], "Aircraft Type": ["Boeing 787-8 Dreamliner"], 
                 "Origin": ["Sardar Vallabhbhai Patel International Airport, Ahmedabad, India"], 
                 "Destination": ["London Gatwick, United Kingdom"], 
                 "Date": ["2025-06-12"],
                 "Time": ["Afternoon"], 
                 "Total People Onboard": [242],
                 "Passengers": [230], 
                 "Crew": [12], 
                 "Crash Location": ["Meghani area, Ahmedabad, India"], 
                 "Altitude at Crash": ["Approximately 425 feet"], 
                 "Cause": ["Under investigation (suspected engine failure, safety lapses flagged by DGCA)"], 
                 "Description": ["Aircraft stalled shortly after takeoff, crashed into a medical college campus,and burst into flames due to heavy fuel load."],
                 "Mayday Call": ["Issued before contact was lost"]}
```

![image](https://github.com/user-attachments/assets/8e6ed9a2-5622-4a7d-9606-3971c53c8ab4)  

### ⏱ Timeline  

```
timeline_data = {
    "Time": ["12:10 PM", "12:14 PM", "12:15 PM", "12:16 PM", "12:20 PM", "1:00 PM"],
    "Event": [
        "Takeoff from Ahmedabad",
        "Mayday call issued",
        "Loss of contact",
        "Crash into medical campus",
        "First responders arrive",
        "PM reviews operations"
    ]
}

df_timeline = pd.DataFrame(timeline_data)
```
![Timeline](https://github.com/user-attachments/assets/5cb4928f-94ff-478e-80a5-45990e9cf89b)


### 🛫 Casualty Metrics  

![casualty_metrics](https://github.com/user-attachments/assets/d189da5d-0f19-4172-bd86-53019b31dd06)  

### ✈️ Pilot Experience Comparison  

![pilot_experience](https://github.com/user-attachments/assets/1ff3a85c-dd90-4e47-9a71-e862f017143b)  

### 🚨Survivor vs Fatalities  

![casualty_pie](https://github.com/user-attachments/assets/1ae7e79c-0d73-4e5e-8672-185799d28501)  

### 🚒 Emergency Response Resource Comparison  

![emergency_resources](https://github.com/user-attachments/assets/f12458fe-0036-47a7-90dc-8f090984b185)  

### DNA Processing Progress  

![dna_processing_pie](https://github.com/user-attachments/assets/440c29fa-36b8-4de6-bdcf-b4e5e234ca9a)

---  

Source: https://timesofindia.indiatimes.com/city/ahmedabad/ahmedabad-air-india-plane-crash-news-live-air-india-london-flight-crash-sardar-vallabhbhai-patel-international-airport-deaths-injured-rescue-operation-latest-updates/liveblog/121799226.cms  

---  

## 🧑‍💻 Author

**Ashwini Bawankar**  
*Mathematician | Data Science Enthusiast*

---

## 📬 Contact

📧 Email: [abawankar13@gmail.com]  
🔗 LinkedIn: [https://www.linkedin.com/in/ashwini-bawankar/]  



















