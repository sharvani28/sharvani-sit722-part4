# Your Solution
# Your Solution
# Use Python base image
FROM python:3.11-slim
 
# Set working directory
WORKDIR /app
 
# Copy requirements file
COPY requirements.txt .
 
# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt
 
# Copy application code
COPY . .
 
# Expose the port
EXPOSE 8000
 
# Run the application
CMD ["uvicorn", "app.main:app", "--host", "0.0.0.0", "--port", "8000"]