https://chrisyeh96.github.io/2017/08/08/definitive-guide-python-imports.html


# List all importable modules

```python
import pkgutil
search_path = ['.'] # set to None to see all modules importable from sys.path
all_modules = [x[1] for x in pkgutil.iter_modules(path=search_path)]
print(all_modules)
```
