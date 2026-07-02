def find_divisors(number):
    return [i for i in range(1, number + 1) if number % i == 0]

if __name__ == "__main__":
    num = 24
    print(f"Number: {num}")
    print(f"Divisors: {find_divisors(num)}")
