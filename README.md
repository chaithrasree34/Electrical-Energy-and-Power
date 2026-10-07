# Electrical Energy and Power Calculator

print("ELECTRICAL ENERGY AND POWER CALCULATOR")
print("---------------------------------------")

# Input values
voltage = float(input("Enter voltage (V): "))
current = float(input("Enter current (A): "))
time = float(input("Enter time (hours): "))

# Calculate power
power = voltage * current

# Calculate energy
energy_wh = power * time
energy_kwh = energy_wh / 1000

# Display results
print("\n--- RESULTS ---")
print("Voltage       :", voltage, "V")
print("Current       :", current, "A")
print("Power         :", power, "W")
print("Energy        :", energy_wh, "Wh")
print("Energy        :", energy_kwh, "kWh")# Electrical-Energy-and-Power