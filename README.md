import random

names = ["Fluffy", "Mochi", "Bubbles", "Noodle","Toothless"]
colors = ["pink", "purple","blue", "rainbow","golden"]
powers = ["controls the weather", "makes unlimited pancakes",
            "can teleport","turns invisible","speaks to animals"]

print("Your DRAGON HAS ARRIVED!")

print("Name:", random.choice(names))
print("Color:", random.choice(colors))
print("Power:", random.choice(powers))
