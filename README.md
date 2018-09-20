# 4.12-Intro-to-Programming
print("Davy's auto shop services")
print('Oil change -- $35')
print('Tire rotation -- $19')
print('Car wash -- $7')
print('Car wax -- $12\n')
firstService = input('Select first service:\n')
secondService = input('Select second service:\n')
print("\nDavy's auto shop invoice\n")
if firstService == 'Oil change':
    print('Service 1: Oil change, $35')
elif firstService == 'Tire rotation':
    print('Service 1: Tire rotation, $19')
elif firstService == 'Car wash':
    print('Service 1: Car wash, $7')
elif firstService == 'Car wax':
    print('Service 1: Car wax, $12')
elif firstService == '-':
    print('Service 1: No service')
else:
    print('Error')
if secondService == 'Oil change':
    print('Service 2: Oil change, $35\n')
elif secondService == 'Tire rotation':
    print('Service 2: Tire rotation, $19\n')
elif secondService == 'Car wash':
    print('Service 2: Car wash, $7\n')
elif secondService == 'Car wax':
    print('Service 2: Car wax, $12\n')
elif secondService == '-':
    print('Service 2: No service\n')
else:
    print('Error')
if firstService == 'Oil change' and secondService == 'Tire rotation':
    print('Total: $54')
elif firstService == 'Oil change' and secondService == 'Car wash':
    print('Total: $42')
elif firstService == 'Oil change' and secondService == 'Car wax':
    print('Total: $47')
elif firstService == 'Oil change' and secondService == '-':
    print('Total: $35')
elif firstService == 'Tire rotation' and secondService == 'Oil change':
    print('Total: $54')
elif firstService == 'Tire rotation' and secondService == 'Car wash':
    print('Total: $26')
elif firstService == 'Tire rotation' and secondService == 'Car wax':
    print('Total: $31')
elif firstService == 'Tire rotation' and secondService == '-':
    print('Total: $19')
elif firstService == 'Car wash' and secondService == 'Oil change':
    print('Total: $42')
elif firstService == 'Car wash' and secondService == 'Tire rotation':
    print('Total: $26')
elif firstService == 'Car wash' and secondService == 'Car wax':
    print('Total: $19')
elif firstService == 'Car wash' and secondService == '-':
    print('Total: $7')
elif firstService == 'Car wax' and secondService == 'Oil change':
    print('Total: $47')
elif firstService == 'Car wax' and secondService == 'Tire rotation':
    print('Total: $31')
elif firstService == 'Car wax' and secondService == 'Car wash':
    print('Total: $19')
elif firstService == 'Car wax' and secondService == '-':
    print('Total: $12')
elif firstService == '-' and secondService == 'Oil change':
    print('Total: $35')
elif firstService == '-' and secondService == 'Tire rotation':
    print('Total: $19')
elif firstService == '-' and secondService == 'Car wax':
    print('Total: $12')
elif firstService == '-' and secondService == 'Car wash':
    print('Total: $7')

