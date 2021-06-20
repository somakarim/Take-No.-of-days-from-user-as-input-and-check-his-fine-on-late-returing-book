# Take-No.-of-days-from-user-as-input-and-check-his-fine-on-late-returing-book-in-python
days= input('Enter the number of days: ')
if int(days)<=7:
    print('You have to pay fine of 10 PKR.')
elifint(days)>=8 and int(days)<=14:
    print('You have to pay fine of 20 PKR.')
elifint(days)>14 and int(days)<31:
    print('You have to pay fine of 50 PKR.')
else:
    print('SORRY! Your membership has been cancelled.')
