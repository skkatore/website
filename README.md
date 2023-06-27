
import numpy as np
import matplotlib.pyplot as plt

# Define the function
def f(x):
    return np.exp(x)

# Generate x values in the interval [-10, 10]
x = np.linspace(-10, 10, 100)

# Calculate corresponding y values
y = f(x)

# Plot the graph
plt.plot(x, y)
plt.xlabel('x')
plt.ylabel('f(x) = e^x')
plt.title('Graph of f(x) = e^x')
plt.grid(True)
plt.show()
