# Design Document – AyuSense AI

## Process Flow
1. Patient provides symptoms through voice input
2. Speech is converted to text using AI
3. Medical NLP extracts symptoms and severity
4. Risk level is identified
5. Clinical summary is generated for doctors

## Architecture Overview
- Frontend: Mobile/Web Application
- Backend: Cloud-based AI processing
- AI Services: Speech recognition and medical NLP
- Storage: Secure cloud storage for patient data
- Dashboard: Doctor-facing clinical summary interface

## Wireframes (Description)
The system includes a patient voice input screen and a doctor dashboard displaying structured clinical summaries and risk alerts.

## Technologies Used
- AWS Transcribe
- AWS Comprehend Medical
- AWS Bedrock
- AWS Lambda
- Amazon DynamoDB
- Amazon S3
- API Gateway
- React / Flutter

## Estimated Cost
The solution uses a serverless, pay-per-use architecture with an estimated cost of ₹2–5 per patient interaction, making it affordable and scalable.
