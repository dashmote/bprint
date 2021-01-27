### **Installation**
```bash
pip install git+https://github.com/dashmote/bprint.git
```

### **Usage**
```python
from bprint import bprint as print
```

```python
print(content, text_color = None, text_format = None, tag = None)
```
**text_color** will accept:

- purple
- cyan
- darkcyan
- blue
- green
- yellow
- red

**text_format** will accept:

- bold
- underline

**tag** will be printed in uppercase in square brackets ([]) before content.

If content is *list*, bprint will print it into lines.
