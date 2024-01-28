# python3-logo_gen.py
A port of the semi lost qcom logo_gen.py to python3

## The Script currently generate a 10MiB splash.img, if your original splash.img is bigger or smaller, you need to adjust the following part accordingly:
``` python
    # Calculate the remaining size to fill with zeros
    total_size = 10 * 1024 * 1024  # 10 MiB
    written_size = len(header) + len(body)
    remaining_size = total_size - written_size
```
