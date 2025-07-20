{
  "type": "array",
  "items": {
    "type": "object",
    "properties": {
      "company": {
        "type": "string",
        "description": "Name of the company"
      },
      "ticker": {
        "type": "string",
        "description": "Stock ticker symbol"
      },
      "sector": {
        "type": "string",
        "description": "Market sector of the company"
      },
      "exchange": {
        "type": "string",
        "description": "Stock exchange (e.g., NASDAQ, NYSE, OMX)"
      },
      "catalyst": {
        "type": "string",
        "description": "Technical or fundamental reason for trade"
      },
      "trade_type": {
        "type": "string",
        "enum": ["Breakout", "Pullback", "Volume Spike", "News Catalyst", "Gap Fill"]
      },
      "entry": {
        "type": "string",
        "description": "Suggested entry price"
      },
      "stop_loss": {
        "type": "string",
        "description": "Stop loss price"
      },
      "target": {
        "type": "string",
        "description": "Profit target price"
      },
      "risk_level": {
        "type": "string",
        "enum": ["Low", "Medium", "High"]
      }
    },
    "required": [
      "company",
      "ticker",
      "sector",
      "exchange",
      "catalyst",
      "trade_type",
      "entry",
      "stop_loss",
      "target",
      "risk_level"
    ]
  }
}

