print(“Hello!”)
name = input(“What’s your name? “)
age = input(“How old are you? “)

while True:
    print(f”\nHi {name}, do you want to:”)
    print(“1. Talk about travel destinations”)
    print(“2. Discuss your favorite books”)
    print(“3. Exit”)

    choice = input(“Choose a number: “)

    if choice == “1”:
        print(f”{name}, let’s explore some amazing travel destinations!”)
    elif choice == “2”:
        print(f”Great choice, {name}! What’s your favorite book genre?”)
    elif choice == “3”:
        print(f”Goodbye, {name}!”)
        break
    else:
        print(“Invalid choice. Please try again.”)