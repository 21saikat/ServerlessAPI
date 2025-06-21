# Serverless API with Azure Functions (Python)

This project contains a simple serverless API built with Azure Functions and Python.

## Function

**Route:** `/api/myfunction`  
**Method:** `GET` or `POST`  
**Response:** `Hello from MyFunctionUnique!`

## Run Locally

```bash
func start




Deploy

func azure functionapp publish serverlessapiapp






---

Now your structure looks like this:

ServerlessAPI/
├── MyFunction/
│ ├── init.py
│ ├── function.json
├── host.json
├── requirements.txt
├── .gitignore
├── README.md





---

### ✅ Final Step: Initialize Git & Push to GitHub

```bash
git init
git add .
git commit -m "Initial commit: Azure Function app with Python HTTP trigger"
git remote add origin https://github.com/YOUR_USERNAME/ServerlessAPI.git
git branch -M main
git push -u origin main

