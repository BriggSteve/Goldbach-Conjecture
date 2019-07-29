import itertools

for x in itertools.count(4, 2):
    for i in range(2, x + 1):
        if x % i == 0:
            primenumber = 1
            for j in range(2, (i // 2 + 1)):
                if i % j == 0:
                    primenumber = 0
                    break
            if primenumber == 1:
                print(" The number %d has the prime factor of %d" % (x, i))
