---
template: post
title: Level 1 | Exercise 1 - Blink
slug: level-1-exercise-1
level: 1
exercise: 1
category: CircuitPython
tags: ["Level 1"]
---

```python
from adafruit_circuitplayground.express import cpx
import time

while True:
    cpx.red_led = True
    time.sleep(0.5)
    cpx.red_led = False
    time.sleep(0.5)
```
