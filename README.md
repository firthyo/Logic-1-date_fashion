# Logic-1-date_fashion
def date_fashion(you, date):
  #if either of you has style of 2 or less, then the result is 0
    if date <=2 or you <= 2:
        return 0
  #If either of you is very stylish, 8 or more, then the result is 2 
    elif date >=8  or you >= 8:
        return 2
  #Otherwise the result is 1
    else:
        return 1
