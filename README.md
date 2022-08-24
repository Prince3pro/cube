# Created by Prince kumar

def qrange(n):
    for i in range(1, n):
        yield i * i * i


n = 100
print('Cubes of numbers from 1 to %d are:' % (n - 1))
for i in qrange(n):
    print(i)
