### SameFirstLast

```.py
def SameFirstLast(inp):
    len_inp = len(inp)
    result = ""
    if len_inp >= 1 and inp[0] == inp[len_inp-1]:
        result = "TRUE"
    else:
        result = "FALSE"
    return result
```

![](quiz_sameFirstLast.jpg)

![](スクリーンショット (225).png)
