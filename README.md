# Call Center Performance Analysis Using SQL

## Project Overview
This project analyzes a call center dataset to uncover insights into agent performance, customer satisfaction, and the effectiveness of different communication channels. The dataset includes various details about each call, such as the call reason, channel, response time, and customer sentiment.

## Dataset
The dataset used in this project contains the following columns:

id: Unique identifier for the call
customer_name: The customer’s name
sentiment: Overall tone of the call
csat_score: Customer Satisfaction Rating Score (Scale is 1-10)
call_timestamp: Date of call
reason: Category of call purpose
channel: How the customer connected to the call center
response_time: Response time relative to the Service Level Agreement (SLA)
call_duration_in_minutes: Length of call in minutes
call_center: Call center location
agent_id: The agent who took the call
city: City of the customer’s location
state: State of the customer’s location
yob: Years of business

## Analysis Goals

1. **Agent Performance:** Identify agents with timely responses and those with poor response times. Evaluate their customer satisfaction scores.

2. **Customer Sentiment:** Analyze customer sentiment to understand how customers feel about the service provided.
   
3. **Call Center Performance:** Determine the performance of different call centers and communication channels.
   
4. **Customer Location:** Identify the most loyal customers' locations and areas with consistently high or low satisfaction.

## Key Findings

- **Top Negative Sentiment Reasons:** Billing questions, payments, and service outages are the top reasons for negative and very negative sentiments.
  
- **Channel Performance:** All channels show similar negative sentiment patterns, suggesting that improvements are needed across all communication methods.

- **Recommendations:** Focus on enhancing agent training for handling billing, payment, and service outage calls. Improve self-service options to reduce call volume for these issues.
