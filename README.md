# Python_Gen_Random
# random_sample.py
import numpy as np

def generate_random_sample(size=10):
    """Generate a random sample of numbers."""
    return np.random.rand(size)

def calculate_mean(data):
    """Calculate the mean of a given dataset."""
    return np.mean(data)

if __name__ == "__main__":
    # Generate a random sample of 10 numbers
    random_data = generate_random_sample()

    # Calculate the mean of the random sample
    mean_value = calculate_mean(random_data)

    print(f"Random Sample: {random_data}")
    print(f"Mean: {mean_value}")
