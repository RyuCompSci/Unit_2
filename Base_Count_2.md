### Base Count

Create a function that returns a list with the numbers up to a 100 (decimal) in a base given (base), where base is 1<base<17
Then, test this function by showing the numbers up to 100 on 3 different bases with a nice message as show in the example below.


```.py
def base_count(inp):
    r = 0
    rr = ""
    div = 100
    abc = {10: "a", 11: "b", 12: "c", 13: "d", 14: "e", 15: "f", 16: "g"}
    while div >= inp:
        r = div % inp
        if r >= 10:
            rr += abc[r]
            div = div // inp
        else:
            rr += str(r)
            div = div // inp
    rr += str(div)
    rrr = rr[::-1]
    return rrr
 ```
 
 ```.py
 def base_count(base, div):
    r = 0
    rr = ""
    abc = {10: "a", 11: "b", 12: "c", 13: "d", 14: "e", 15: "f", 16: "g"}
    while div >= base:
        r = div % base
        if r >= 10:
            rr += abc[r]
            div = div // base
        else:
            rr += str(r)
            div = div // base
    rr += str(div)
    rrr = rr[::-1]
    return rrr


def base_count2(base):
    div = 0
    for i in range(101):
        print(f" {div} decimal in base {base} is {base_count(base, div)}")
        div += 1
    return


print(base_count2(16))
```
