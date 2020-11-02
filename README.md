# convert_numbers
![Twitter Follow](https://img.shields.io/twitter/follow/Al_Azwari?label=Follow&style=social) [![Downloads](https://pepy.tech/badge/convert-numbers)](https://pepy.tech/project/convert-numbers) ![PyPI - Python Version](https://img.shields.io/pypi/pyversions/Django?style=plastic) [![PyPI version](https://badge.fury.io/py/convert-numbers.svg)](https://badge.fury.io/py/convert-numbers)
##### Arabic Persian English Hindi Numbers Conversion


##### Installation

```bash
pip install convert_numbers
```

##### Usage

```python
import convert_numbers

# From Hindi To Englis
print(convert_numbers.hindi_to_english('٨٧٦٥٤٣٢٣٤٥٦٧٨')) #8765432345678


# From Englis To Hindi
print(convert_numbers.english_to_hindi('12309876523')) ##١٢٣٠٩٨٧٦٥٢٣


# From Hindi To Arabic
print(convert_numbers.hindi_to_arabic('٨٧٦٥٤٣٢٣٤٥٦٧٨')) #8765432345678


# From Arabic To Hindi
print(convert_numbers.arabic_to_hindi('12309876523')) #١٢٣٠٩٨٧٦٥٢٣


# From Arabic To English
print(convert_numbers.arabic_to_english('٢٣٤٥٦٧٨٠٩٨٧٦')) #234567809876


# From English To Arabic
print(convert_numbers.english_to_arabic('09876523456')) #٠٩٨٧٦٥٢٣٤٥٦


# From Persian To English
print(convert_numbers.persian_to_english('۵۱۲۳۹۶۰۴۴')) #512396044


# From English To Persian
print(convert_numbers.english_to_persian('512396044')) #۵۱۲۳۹۶۰۴۴


# From Persian To Hindi
print(convert_numbers.persian_to_hindi('۵۱۲۳۹۶۰۴۴')) #٥١٢٣٩٦٠٤٤


# From Hindi To Persian
print(convert_numbers.hindi_to_persian('٢٣٤٥٦٧٨٠٩٨٧٦')) #۲۳۴۵۶۷۸۰۹۸۷۶
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)