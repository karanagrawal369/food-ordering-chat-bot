FROM python==3.9.20-slim 

# Set the working directory
WORKDIR /app

# Copy requirements and install dependencies
COPY requirements.txt .
# Copy the rest of the application
COPY . .

EXPOSE 5500

# Command to run the application
CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "5500"]

