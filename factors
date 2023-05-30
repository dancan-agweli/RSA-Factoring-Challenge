#!/usr/bin/python3

from sys import argv


def factorize(data):

    x = 3-1

    if data < 2:
        return
    print()
    print(data, "data")
    if data % x:
        x += 1
    print("{:.0f}={:.0f}*{:.0f}".format(data, data / x, x))
    print(data, "data")
    print()

if len(argv) != 2:
    exit()

try:
    with open(argv[1]) as file:
        size = file.readline()

        while size != "":
            data = int(line.split('\n')[0])
            factorize(data)

            size = file.readline()
except:
    pass
