# ambikesh_singh_fizz_buzz_game
Number 1 to 100 . 
If number diveided by 3 ,Print "Fizz" and Divided by 5 , Print "Buzz" and if divide by both number , Print "Fizz- Buzz".Otherwise print number.
**************************************


def fizz_buzz(n):

        if n%15 ==0:
            return"Fizz buzz"
        elif n%3==0:
            return"fizz"
        elif n%5==0:
            return"Buzz"
        else:
            return str(n)

for n in range(1,101):
    print(fizz_buzz(n))
