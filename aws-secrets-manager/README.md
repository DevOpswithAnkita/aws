# AWS Lambda Secret Rotation

This project contains a simple Python Lambda function that rotates a key inside AWS Secrets Manager using AWS 
Lambda.

## What This Function Does

- Generates a new random password
- Fetches existing secret
- Updates one key in the secret
- Saves updated secret back

## Flow

1. Lambda function is triggered
2. Generate new random password
3. Get current secret from Secrets Manager
4. Update specific key
5. Store updated secret

## Files

- secret-key-rotation-lambda.py
- policy.json
- README.md

## Requirements

- Python 3.x
- boto3
- IAM permissions  
