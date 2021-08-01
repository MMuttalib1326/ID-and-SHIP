# ID-and-SHIP
Write a program that takes in a letterclass ID of a ship and display the equivalent string class description of the given ID.

t = int(input())

for i in range(t):
    ch = input()
    if ch == 'B' or ch == 'b':
        print('BattleShip')
    elif ch == 'C' or ch == 'c':
        print('Cruiser')
    elif ch == 'D' or ch == 'd':
        print('Destroyer')
    elif ch == 'F' or ch == 'f':
        print('Frigate')
