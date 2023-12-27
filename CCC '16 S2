q = int(input())
citizens = int(input())
dmojistan = sorted([int(i) for i in input().split()])
pegland = sorted([int(i) for i in input().split()])

if q == 2:
    Sum = 0
    pegland = pegland[::-1]

    for i in range(citizens):
        Sum += max(dmojistan[i], pegland[i])

else:
    Sum = 0

    for i in range(citizens):
        Sum += max(dmojistan[i], pegland[i])

print(Sum)
