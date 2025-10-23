# Contributing Guidelines

Thank you for considering contributing to this project! Follow the steps below to make your contribution smooth and effective.

## How to Contribute
1. **Fork** the repository.
2. **Create a branch** for your feature or bug fix:
   ```bash
   git checkout -b feature-name
git commit -m "Add feature-name"
git push origin feature-name


---

### **Task 6 — simple-interest.sh**
> 📄 File name: `simple-interest.sh`

```bash
#!/bin/bash
# This script calculates simple interest

echo "Enter the Principal:"
read principal

echo "Enter the Rate of Interest:"
read rate

echo "Enter the Time (in years):"
read time

# Calculate simple interest
simple_interest=$(echo "scale=2; $principal * $rate * $time / 100" | bc)

echo "The Simple Interest is: $simple_interest"

chmod +x simple-interest.sh

