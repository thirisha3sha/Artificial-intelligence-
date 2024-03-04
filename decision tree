'''decision tree'''
def decide_to_buy_computer():
    # Take user input for attributes
    print("Enter the attributes to decide whether to buy a computer or not:")
    budget = input("Enter your budget (high/low): ").lower()
    credit = input("Enter your credit status (good/bad): ").lower()
    age = input("Enter your age (young/middle-aged/senior): ").lower()
    student = input("Are you a student? (yes/no): ").lower()

    # Decision tree rules
    if budget == 'high':
        if credit == 'good':
            decision = "Buy"
        else:
            if student == 'yes':
                decision = "Buy"
            else:
                decision = "Don't buy"
    else:
        if age == 'young':
            if credit == 'good':
                decision = "Buy"
            else:
                decision = "Don't buy"
        else:
            decision = "Don't buy"

    # Print decision
    print(f"Decision: {decision}")

if __name__ == "__main__":
    decide_to_buy_computer()
