#  SteamNoodles Feedback Agent – Pawan Madushanka

## SteamNoodles Review Analyzer

##  Submitted by
**Name**: Pawan Madushanka  
**University**: University of Jaffna  
**Year**: 2nd Year  

---

##  Project Summary

This project analyzes customer reviews for the fictional restaurant **SteamNoodles** using two intelligent agents:

1. **LLM-Based Review Response Agent** (Groq + LLaMA 3):  
   - Accepts customer reviews in text format  
   - Detects sentiment (positive, neutral, negative)  
   - Generates polite and helpful replies using LLM

2. **Rule-Based Sentiment Analyzer + Trend Plotter**:  
   - Maps numeric star ratings to sentiment categories  
   - Visualizes sentiment trends using line plots

---

##  Setup Instructions

1. Clone the project:
   ```bash
   git clone https://github.com/your-username/steamnoodles-review-analyzer.git
   cd steamnoodles-review-analyzer
   
---


##  Instructions to Test Agent 1
1.Add your Groq API Key in the script:

2.Run the following code:
sample_review = input("Enter customer review: ")
reply = generate_feedback_response(sample_review)
print("\nGenerated Response:\n", reply)

---
##  Instructions to Test Agent 2
1.Load the dataset (e.g., reviews.csv) with the columns:

2.plot_sentiment_trends("2023-07-24", "2024-07-31")

---

##  Prompt:
Agent1:The noodles were amazing but the service was a bit slow.

Agent2:plot_sentiment_trends("2023-07-24", "2023-08-31")


---

##  Expected Output:
Agent1:Thank you for your feedback! We're glad you enjoyed the noodles. We apologize for the slow service and will work to improve it.

Agent2:

<img width="1717" height="712" alt="Image" src="https://github.com/user-attachments/assets/e07792b2-5833-4d5e-936c-149e33c9cce4" />











https://github.com/user-attachments/assets/31772aa9-49f8-4426-a5d1-1797673f64dc
