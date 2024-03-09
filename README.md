# cheez
class Cheese:
    def __init__(self, name, type, flavor, price_per_kg):
        self.name = name
        self.type = type
        self.flavor = flavor
        self.price_per_kg = price_per_kg

    def display_info(self):
        print(f"Cheese: {self.name}")
        print(f"Type: {self.type}")
        print(f"Flavor: {self.flavor}")
        print(f"Price per kg: ${self.price_per_kg}")

# Example usage
if __name__ == "__main__":
    # Creating an instance of the Cheese class
    my_cheese = Cheese(name="Cheddar", type="Hard", flavor="Sharp", price_per_kg=10.99)

    # Displaying information about the cheese
    my_cheese.display_info()
