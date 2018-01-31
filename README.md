# HashPay

Implementing Swirlds_ byzantine consensus algorithm by Leemon Baird
([whitepaper](http://www.swirlds.com/wp-content/uploads/2016/07/SWIRLDS-TR-2016-01.pdf)
available) in python. _Swirlds_ is an algorithm constructing a strongly
consistent and partition tolerant, peer-to-peer append-only log.




## Dependencies

- python3
- [pysodium](https://pypi.python.org/pypi/pysodium) for the crypto
- [bokeh](http://bokeh.pydata.org/en/latest/) for the analysis and interactive
  visualization

## Usage
For now it is just an (not proper)implementation of the hashgraph consensus algorithm.
You can see how network evolves in real time.
        ```bokeh serve --show hashgraph.py --args <number of nodes>```
