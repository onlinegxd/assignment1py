# Top cryptocurrencies parser using CoinGecko API

### Installation
PyPI
```bash
pip install pycoingecko
pip install pandas
```

### Usage

```python
val = int(input("Please enter number n:\n"))
print(f'Top {val} cryptocurrencies by market capitalization \n')
print(sort_by_market_cap(val))
```

### Examples

Usage examples:
```python
# Please enter number n:
>>> 5
Top 5 cryptocurrencies by market capitalization 

id
bitcoin        1
ethereum       2
cardano        3
tether         4
binancecoin    5

# OR Please enter number n:
>>> 10
Top 10 cryptocurrencies by market capitalization 

id
bitcoin         1
ethereum        2
cardano         3
tether          4
binancecoin     5
ripple          6
solana          7
usd-coin        8
polkadot        9
dogecoin       10


```

