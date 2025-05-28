# 🌍 Conversor de Moedas com Cotações em Tempo Real

Este programa em Python converte valores de reais (R$) para Dólar (USD), Euro (EUR) e Iene Japonês (JPY), utilizando **cotações em tempo real** obtidas através da API [ExchangeRate.host](https://exchangerate.host).

## ⚙️ Funcionalidades

- Entrada de valor em reais (R$)
- Conversão para:
  - Dólar americano (USD)
  - Euro (EUR)
  - Iene japonês (JPY)
- Utiliza dados de câmbio atualizados via API
- Saída formatada com duas casas decimais

## 🔌 Requisitos

- Python 3.x
- Biblioteca `requests` (instale com `pip install requests`)

## 💻 Como Usar

1. Salve o código como `conversor_moedas.py`
2. Instale a biblioteca `requests`, se necessário:
   ```bash
   pip install requests
   ```
3. Execute o script:

```bash
  python conversor_moedas.py
```

4. Digite o valor em reais e veja a conversão ao vivo!

## 📋 Exemplo de Saída

```
Quanto dinheiro você tem na carteira? R$100
Com R$100.00 você pode comprar:
- US$19.24
- €17.56
- ¥2943.84
```

## 🌐 Fonte dos Dados

ExchangeRate.host – API gratuita e sem autenticação.

## 📄 Licença

Este projeto é de uso livre para fins educacionais e pessoais.
