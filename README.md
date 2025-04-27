# PostForge - Social Media Post Generator 🚀

## Project Overview
PostForge instantly generates promotional social media captions based on any product name or idea using AI!

## Features
- AI-powered caption generation
- Easy-to-use web interface
- Serverless backend with AWS Lambda
- Cloud storage with AWS S3
- Quick and creative outputs

## Stack Used
- Frontend: React.js
- Backend: Node.js (Express)
- AI Model: OpenAI GPT / AWS Bedrock
- AWS Services:
  - AWS Lambda
  - AWS S3
  - (Optional) AWS Bedrock

## How It Works
1. User enters a product name or idea.
2. Backend calls the AI model via API.
3. Caption is generated and displayed to the user.
4. Optionally save generated captions to AWS S3.

## How to Run Locally
- Clone this repo.
- Install dependencies with `npm install`.
- Create an `.env` file for API keys.
- Run frontend: `npm run start`
- Deploy backend serverless: AWS Lambda function.

## Demo Video
[Insert YouTube Link Here]

## Deployment
- Frontend: Vercel / Netlify
- Backend: AWS Lambda
