# Examen2

## Yahoo Finance

Link de KC=F -> https://finance.yahoo.com/quote/KC%3DF/

Como importar los Datos financieros:

import yfinance as yf

coffee = yf.download("KC=F", start="2000-01-01")

print(coffee.head())



---

