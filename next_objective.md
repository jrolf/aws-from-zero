# Solving for the Future of Cognitive Engineering

## Task
Create a simple Python script using Boto3 that creates a Python "layer" and a Lambda service to test the layer.

## Context
I have been working with AWS services, specifically using the Boto3 Python library to create various instances and execute transactions with them. However, I'm currently stuck on how to create Lambda layers that work without errors. If you can help me solve this, I will be grateful.

## What I Have Done So Far
I understand how to create simple Lambda functions and S3 buckets exclusively through Python code (via Boto3) and have no dependency on the AWS UI—besides creating the IAM accounts. 

Currently, the problem I am facing is how to create a Lambda layer that includes the `requests` library. I keep getting errors, and ChatGPT has hit a wall.

## Example Code
You can refer to the "TUTORIALS" section of this repository and look for the `LAMBDA_FROM_ZERO3_TUTORIAL.ipynb` file.

## Next Objectives
1. **Create a Layer Programmatically**  
   Use only a Python script and the Boto3 library to create a layer.
   
2. **Include Libraries in the Layer**  
   The layer should include the following libraries:
   - `requests`
   - `numpy`
   - `pandas`
   - `openai`
   - `transformers`

3. **Script Requirements**  
   The Python script to create the layer should be robust and compatible with execution from a Mac machine.

4. **Attach the Layer to a Lambda Function**  
   Programmatically attach the created layer to a Lambda function.

5. **Test the Lambda Function**  
   The Lambda function should return a payload confirming that the Python libraries were successfully imported.

6. **Send the Script**  
   Provide me with the Python script so I can test it on my machine with my AWS credentials.

---

It will be a huge unlock for me if we can solve this. Please let me know if you have any questions. Reach me anytime on WhatsApp.




.
