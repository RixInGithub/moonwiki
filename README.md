# moonwiki
moonwiki is a wiki application made with Python that doesn't require:
- A database
- External modules
- Too much configuration
## Usage
Here are some usage examples:
```py
import moonwiki

print(moonwiki.__package__) # "moonwiki"
``````py
from moonwiki import moonwiki
wiki = moonwiki()

wiki.run("0.0.0.0", 8080)
```