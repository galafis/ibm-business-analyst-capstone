# Documentação da API - Business Analyst Platform

## 📡 Endpoints Principais

### Analytics
- `GET /api/analytics/kpis` - Retorna KPIs configurados
- `POST /api/analytics/calculate` - Calcula métricas específicas
- `GET /api/analytics/trends` - Análise de tendências

### Processes
- `GET /api/processes` - Lista processos mapeados
- `POST /api/processes/optimize` - Otimiza processo específico
- `GET /api/processes/gaps` - Identifica lacunas

### Stakeholders
- `GET /api/stakeholders` - Lista stakeholders
- `POST /api/stakeholders/analyze` - Análise de influência
- `GET /api/stakeholders/engagement` - Planos de engajamento

## 📝 Exemplos de Uso

### Calcular KPIs
```python
import requests

response = requests.post('/api/analytics/calculate', json={
    'metrics': ['revenue', 'conversion_rate'],
    'period': '30d'
})
```

### Otimizar Processo
```python
response = requests.post('/api/processes/optimize', json={
    'process_id': 'sales_pipeline',
    'optimization_type': 'efficiency'
})
```

## 🔐 Autenticação

Use API keys no header:
```
Authorization: Bearer YOUR_API_KEY
```
