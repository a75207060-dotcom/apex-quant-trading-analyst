# apex-quant-trading-analyst
Production-grade Quantitative Trading Analyst agent for Swarms Marketplace

# Apex Quant Trading Analyst

Production-grade quantitative trading and financial analysis agent built with [Swarms](https://swarms.ai).

## Installation

```bash
pip install swarms
from apex_quant import create_apex_quant_agent

agent = create_apex_quant_agent()

result = agent.run(
    "Analyze the current market structure of Bitcoin and provide a risk-aware outlook for the next 2-4 weeks."
)

print(result)
agent = create_apex_quant_agent(model_name="claude-sonnet-4-6")
