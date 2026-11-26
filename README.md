# Ohm's Law Calculator - By Engineer Student
# V = I * R

print("===== OHM'S LAW CALCULATOR =====")
print("1. Voltage (V) Maloom Karna Hai")
print("2. Current (I) Maloom Karna Hai")
print("3. Resistance (R) Maloom Karna Hai")

choice = input("Apna Choice Likhein (1/2/3): ")

if choice == "1":
    I = float(input("Current (I) in Ampere likhein: "))
    R = float(input("Resistance (R) in Ohm likhein: "))
    V = I * R
    print(f"Voltage (V) = {V} Volt")

elif choice == "2":
    V = float(input("Voltage (V) in Volt likhein: "))
    R = float(input("Resistance (R) in Ohm likhein: "))
    I = V / R
    print(f"Current (I) = {I} Ampere")

elif choice == "3":
    V = float(input("Voltage (V) in Volt likhein: "))
    I = float(input("Current (I) in Ampere likhein: "))
    R = V / I
    print(f"Resistance (R) = {R} Ohm")

else:
    print("Ghalat Choice!")

print("Thanks! Made by Future Engineer")
