    # Hi, I'm JoeKingFish! 

    class JoeKingFish:
        def __init__(self):
            self.favorite_beverage = "Mountain Dew"  # Because coffee is overrated
            self.caffeine_level = 5  # Start fully caffeinated

        def code(self):
            while self.caffeine_level > 0:
                print("Coding... ")
                self.caffeine_level -= 1  # Coding consumes caffeine
                self.check_dew()

            print("WARNING: Caffeine Levels Dangerously Low!")

        def check_dew(self):
            if self.caffeine_level == 0:
                print(f"Refueling with {self.favorite_beverage}...")
                self.caffeine_level = 5  # New Dew, back to full energy!

    # Start the day
    joe = JoeKingFish()
    joe.code()
