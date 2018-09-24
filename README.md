# darkcolab
darknet on google colab


```bash
curl -X POST http://xxxxxx.ngrok.io/detect -F "file=@./sample.jpg"
```

```python3
import requests
from icecream import ic
r = requests.get('http://xxxxxx.ngrok.io/detect',files={'file': open("sample.jpg", "rb")})
ic(r.text)
```

```go

```
