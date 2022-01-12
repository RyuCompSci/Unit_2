### Japanese Units. Create a program that converts meters to traditional japanese units (bu, sun, shaku) following the table below: 

```.py
def japanese_length(input):
    remainder = 0
    shaku = input // 0.3
    remainder = input % 0.3
    sun = remainder // 0.03
    remainder = remainder % 0.03
    bu = remainder // 0.003
    output = f"{input} meters are approximately {shaku}尺　and {sun}寸 and {bu}分"
    return output
```
