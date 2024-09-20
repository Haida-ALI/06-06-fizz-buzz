def fizz_buzz(x,y,max):
  for i in range(1,max+1):
    if i%x==0 and i%y==0:
      print('fizz buzz')
    elif i % x == 0:
      print('fizz')
    elif i % y == 0:
      print('buzz')
    else:
      print(i)



fizz = int(input('what number do you want to be fizz?  '))
buzz = int(input('what number do you want to be buzz?  '))
max = int(input('what number do you want to be the max?  '))

fizz_buzz(fizz,buzz,max)
