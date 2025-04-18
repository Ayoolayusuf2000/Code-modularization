# Code-modularization
# How to use the find_root function
# Find square root of 25 (equivalent to 25**(1/2))
result = find_root(25, 2, 0.001)
print(result)  # Output will be ~5.0

# Find cube root of -8 (equivalent to (-8)**(1/3))
result = find_root(-8, 3, 0.0001)
print(result)  # Output will be ~-2.0

# Attempt to find square root of -4 (invalid)
result = find_root(-4, 2, 0.001)
print(result)  # Output will be None
