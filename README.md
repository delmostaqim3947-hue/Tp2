entier = 42              # int
flottant = 3.14          # float
texte = "Python"         # str
vrai_ou_faux = True      # bool
print(entier, "→", type(entier))
print(flottant, "→", type(flottant))
print(texte, "→", type(texte))
print(vrai_ou_faux, "→", type(vrai_ou_faux))
age_str = input("Quel âge as-tu ? ")
print("Tu as saisi :", age_str, "→", type(age_str))

age = int(age_str)
print("Après conversion :", age, "→", type(age))
age = int(input("Quel âge as-tu ? "))
    print(f"Dans 5 ans tu auras {age + 5} ans.")
except ValueError:
    print("Saisie invalide, merci d'entrer un entier.")
    nombre = 10 
print(nombre)

nombre = 10 + 5  
int (15)
print(nombre)
liste = [1, 2, 3]
age: int = int(input("Age ? "))
