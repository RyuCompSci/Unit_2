### mirroredTime

```.md
def mirroredTime(n:int):
    output = ""
    if n > 24:
        return None
    if n < 10:
        output = f"0{n}:0{n}, 0{n}:{n}0"
    elif 10 <= n < 24:
        output = f"{n}:{n}"
        if (n//10)+10*(n%10) < 59:
            output += f"\n{n}:{n//10+10*(n%10)}"
        return output
 ```
 
 ![]()
