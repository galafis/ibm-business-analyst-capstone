# Guia do Usuário - IBM Business Analyst Platform

## 📋 Visão Geral

Este guia fornece instruções detalhadas para usar a plataforma de análise de negócios.

## 🚀 Primeiros Passos

### Instalação
```bash
pip install -r requirements.txt
streamlit run src/main_platform.py
```

### Configuração Inicial
1. Configure as variáveis de ambiente no arquivo `.env`
2. Importe seus dados de negócio
3. Configure os KPIs desejados

## 📊 Funcionalidades Principais

### Dashboard de KPIs
- Acesse através do menu principal
- Configure métricas personalizadas
- Visualize tendências em tempo real

### Análise de Processos
- Mapeie processos existentes
- Identifique gargalos
- Gere relatórios de otimização

### Gestão de Stakeholders
- Cadastre stakeholders
- Analise influência e interesse
- Crie planos de engajamento

## 🔧 Configurações Avançadas

### Personalização de Dashboards
```python
from src.business_analytics_platform import BusinessAnalyzer

analyzer = BusinessAnalyzer()
dashboard = analyzer.create_custom_dashboard(metrics=['revenue', 'conversion'])
```

### Integração com APIs
Configure APIs externas no arquivo `config/apis.py`

## 📞 Suporte

Para suporte técnico, consulte a documentação da API ou entre em contato.
