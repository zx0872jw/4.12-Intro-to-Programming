# 4.12-Intro-to-Programming
print("Davy's auto shop services")
print('Oil change -- $35')
print('Tire rotation -- $19')
print('Car wash -- $7')
print('Car wax -- $12')
firstService = input('Select first service:')
secondService = input('Select second service:')
if secondService == 'Oil change':
    print('Service 2: oil change, $35')
elif secondService == 'Tire rotation':
    print('Service 2: tire rotation, $19')
elif secondService == 'Car wash':
    print('Service 2: car wash, $7')
elif secondService == 'Car wax':
    print('Service 2: car wax, $12')
elif secondService == '-':
    print('Service 2: No service')
