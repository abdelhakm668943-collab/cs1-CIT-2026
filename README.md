# cs1-CIT-2026import random
import string

letters = string.ascii_letters

l = ""
counter = 0   # initialisation du compteur

while l != "w":
    l = random.choice(letters)
    print(f"La lettre choisie est {l}")
    counter += 1

print(f"Le nombre de tirages effectués est {counter}")
