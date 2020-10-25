# dict
....
w = input('Enter your word: ')
v = ['a', 'e', 'i', 'o', 'u']
found = {}

for letters in w :
    if letters in v :
        found.setdefault(letters, 0)
        found [letters]  += 1
        
for k, v in found.items():
    print(k, 'was found', v, 'time(s).')
