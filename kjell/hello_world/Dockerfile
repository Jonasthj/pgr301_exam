# Use the official AWS Lambda Python image with Python 3.9
FROM public.ecr.aws/lambda/python:3.9

# Set the working directory to /var/task
WORKDIR /var/task

# Copy the Lambda function code
COPY . /var/task

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Set the CMD to your handler
CMD ["lambda_handler"]
