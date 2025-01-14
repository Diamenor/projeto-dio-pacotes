# pacote-analise-dio

## Description
The package pacote-analise-dio is used to:
- Manipulation (by using data-clean or data-info)
- Visualization (by using plot)

of [this](https://raw.githubusercontent.com/ine-rmotr-curriculum/data-cleaning-rmotr-freecodecamp/master/data/btc-eth-prices-outliers.csv) dataset.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install data-analysis:

```bash
pip install pacote-analise-dio
```

## Usage
One example can be:
```python
from pacote-analise-dio.manipulation import data-clean #or data-info
data-clean.fill(data_frame, method)
```

## Author
Renan Faria

## License
MIT License

Copyright (c) 2022 Renan Faria

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
