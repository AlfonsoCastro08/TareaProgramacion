print('Enter a positive integer:')
num = input()
for i in range(1, 21):
        mult = num * i
        if mult % 2 != 0:
            print(f"{num} x {i} = {mult} - the number is even")
        else:
            print(f"{num} x {i} = {mult} - the number is odd")
