# first_coding
coding for fun

fhand = open("gdf.txt")
d = []
for lines in fhand:
    lines = lines.rstrip()
    if len(lines) < 1:
        d = d
    else:
        d.append(lines)
print(d)
c = []
for num in range(12):
    c.append(d[num][-4:])
print(c)
count = 0
for i in c:
    count = count + int(i)
print(count)
