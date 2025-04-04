# Calculator-
# Einfacher Taschenrechner in Python

def addiere(a, b):
    return a + b

def subtrahiere(a, b):
    return a - b

def multipliziere(a, b):
    return a * b

def dividiere(a, b):
    if b != 0:
        return a / b
    else:
        return "Durch 0 teilen geht nicht!"

# Beispiel
x = 10
y = 2

print("Addition:", addiere(x, y))
print("Subtraktion:", subtrahiere(x, y))
print("Multiplikation:", multipliziere(x, y))
print("Division:", dividiere(x, y))

