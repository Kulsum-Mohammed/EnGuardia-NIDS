# EnGuardia NIDS
Real-time Network Intrusion Detection System

## Features
- Machine learning-powered threat detection
- Live dashboard with Plotly visualizations
- FastAPI backend for scalable predictions

## Deployment
```bash
git clone https://github.com/yourusername/EnGuardia-NIDS.git
cd EnGuardia-NIDS
docker build -t enguardia .
docker run -p 80:80 enguardia
