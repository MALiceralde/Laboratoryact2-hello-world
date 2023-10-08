pounds = input("Enter weight in pounds (lbs): ")
kilograms = 0.45359237
kilog = (kilograms * float(pounds))
print(str(pounds) + " pounds in kilograms is: " + str(kilog) + " kilograms")
print("=================================")

miles = input("Enter distance in miles (mi): ")
kilometers = 1.60934
km = (kilometers * float(miles))
print(str(miles) + " miles in kilometers is: " + str(km) + " kilometers")
print("=================================")

Fahrenheit = input("Enter temperature in Fahrenheit: ")
Celsius = ((float(Fahrenheit) - int(32)) / 1.8)
print(str(Fahrenheit) + "° Fahrenheit in Celsius is: " + str(Celsius) + "°")
print("=================================")

counter = 0
sumttl = 0
string = "Age of Student "
while counter < 10:
    counter = counter + 1
    age = int(input(string + str(counter) + ": "))
    sumttl = sumttl + age
average = sumttl / 10
print("The average age of the students is ", average)
print("=================================")

Character = ["Frank", "Ky", "Ryu", "Cassanova", "Sazuna"]
Equipment = ["Clock of Destiny", "Blade of Despair", "Immortality", "Berserkers Fury", "Magical Prayers"]
Abilities = ["Divine Companion", "Phantom Execution", "Black Dragon Form", "Blazing Arrow", "Fatal Links"]

print("In the land of dawn, there are 5 heroes who are agents of change and justice, each being mighty and unique in their appearance.")
print("For two days they traveled to prepare for the Fight of Noxus, an event that would end the reign of the abyss, a clan of the evil empire.")
print("When they arrived at their destination, " + Character[0] + " casted " + Abilities[0] + ", which summoned an energy-healing unicorn of light, which helped them recover from their long journey ")
print(Character[1] + ", the assassin, sneaked through the bushes for a surprise attack later on.")
print(Character[3] + ", the marksman, bears the " + Equipment[1] + " and " + Equipment[3] + ".")
print(Character[2] + ", their strongest fighter, has the item " + Equipment[2] + " that grants him immortal will.")
print("Lastly, " + Character[4] + " is the support of the team and has the essential item, " + Equipment[4] + ".")
print("They planned perfectly on their teamfight tactics and waited for the right time to initiate.")
print("When the general of the abyss was sleeping, they knew it was the perfect time for a clash.")
print(Character[1] + " then performed " + Abilities[1] + " and successfully killed nearby enemies.")
print("His engagement marks the start of the clash.")
print(Character[2] + " then used his " + Abilities[2] + " in order to transform into a state of a fire-breathing dragon.")
print(Character[3] + " made some cover for her teammates and directly projected " + Abilities[3] + ".")
print("It killed a lot of enemies, however, they were too many to handle.")
print(Character[4] + " made his entry and immediately used " + Abilities[4] + " to clear out the way.")
print("They were having a hard time dealing with the abyss as their warriors are numerous.")
print("Luckily, " + Character[0] + " made use of her equipment " + Equipment[4] + ", which allowed their skills to refresh faster than the normal rate.")
print("As time passed by, they were able to conquer the troopers.")
print("They were ready to execute the evil king; however, a last horde of warriors stopped them and gave ample time for the king to escape with his mutated dragon.")
print("The evil king became complacent, not knowing that " + Character[2] + " has the " + Abilities[2] + ".")
print("He was then executed later on, and the remaining heroes were destroying the artifact that symbolizes the clan of the abyss.")
print("After destroying the artifact, this marks their historic victory over the course against the evil clan.")
print("Finally,", Character[0], "used", Equipment[0],  "for them to recall inside their hometown.")
