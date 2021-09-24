import random
print("H A N G M A N")
a = input('Type "play" to play the game, "exit" to quit: ')
# print('\n')
while a != 'play':
    a = input('Type "play" to play the game, "exit" to quit: ')
    if a == 'play':
        break
    elif a == 'exit':
        break

while a == 'play':
    words = ['python', 'java', 'kotlin', 'javascript']
    word = random.choice(words)
    l = list(word)
    print('\n')
    print('-' * len(word))
    var = list('-' * len(word))
    att = 8
    inp = list()
    while att > 0:

        c = input('Input a letter: ')
        inp.append(c)

        if len(c) != 1:
            print("You should input a single letter\n")

        elif inp.count(c) > 1:
            print("You've already guessed this letter\n")

        elif (c.isalpha() is False) or (c.islower() is False):
            print("Please enter a lowercase English letter\n")

        elif c in l:
            print()

            for n in range(len(var)):
                if l[n] == c:
                    var.insert(n, c)
                    var.pop(n + 1)

            if var == l:
                print("".join(var))
                break

        else:
            att -= 1
            print("That letter doesn't appear in the word")
            if att == 0:
                break
            print()

        print("".join(var))

    if var == l and att > 0:
        print("You survived!\n")
        inp.clear()
        a = input('Type "play" to play the game, "exit" to quit: ')
        if a == "play":
            continue
        else:
            while a != 'play':
                a = input('Type "play" to play the game, "exit" to quit: ')
                if a == 'play':
                    break
                elif a == 'exit':
                    break
    else:
        print("You lost!\n")
        inp.clear()
        a = input('Type "play" to play the game, "exit" to quit: ')
        if a == "play":
            continue
        else:
            while a != 'play':
                a = input('Type "play" to play the game, "exit" to quit: ')
                if a == 'play':
                    break
                elif a == 'exit':
                    break
    continue









