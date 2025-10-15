FROM tiangolo/uwsgi-nginx-flask:python3.6

# Install Python dependencies
COPY requirements.txt /app/requirements.txt
RUN pip install --no-cache-dir -r /app/requirements.txt

# Copy application code
COPY . /app

EXPOSE 80