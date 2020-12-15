# dyntwist

Discover resolving dynamic DNS domains based on keywords.

#### Usage
```python
import dyntwist

result = dyntwist.dyntwist("solarwinds")
print(result)
```

example result snippet:
```python
{'domain': 'solarwinds.001www.com', 'dns': ['0.0.0.0']}
{'domain': 'solarwinds.16-b.it', 'dns': ['0.0.0.0']}
{'domain': 'solarwinds.32-b.it', 'dns': ['0.0.0.0']}
{'domain': 'solarwinds.64-b.it', 'dns': ['0.0.0.0']}
```

#### Caveats
 - Designed to work on unix style paths (for loading file lists)
