S = "welcommepco"
maxlen = 0
current = ""
for char in S:
    if char in current:
        duplicate_ind = current.index(char)
        current= current[duplicate_ind + 1 :]
    current += char
    if len(current) > maxlen:
        maxlen = len(current)
print(maxlen)
