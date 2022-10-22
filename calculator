from math import sqrt


def meters_of_free_fall():
    t = int(input("Time: "))
    return f"{1 / 2 * 9.80665 * t**2} meters."


def time_of_free_fall():
    h = int(input("Height: "))
    return f"{sqrt(h * 2 / 9.80665)} seconds."


def velocity_of_free_fall():
    t = int(input("Time: "))
    return f"{9.80665 * t} meters per second."


def main():
    functions = {"1": meters_of_free_fall, "2": time_of_free_fall, "3": velocity_of_free_fall}
    choice = input("[1] = Meters of free fall, [2] = Time of free fall, [3] = Velocity of free fall: ")
    if choice not in functions:
        print('[-] Invalid Input')
        exit()
    print(functions[choice]())


if __name__ == "__main__":
    while True:
        main()
