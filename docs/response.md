# Emergency Response

```python
if detected("STOP") or distance < 20cm:
    stop_motors()
    oled_alert("EMERGENCY")
