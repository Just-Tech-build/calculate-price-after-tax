# calculate-price-after-tax
def calculate_total(price: float, tax_rate: float = 0.05) -> float:
    """Calculate the final price after adding tax."""
    return price * (1 + tax_rate)

# Example usage
total = calculate_total(100.0, 0.08)
print(total)  # 108.0
