# Logistics Shipping Rates

A shipping cost calculator built for a logistics company's supply chain management process, calculating shipping costs based on package weight and rate per kilogram.

This project also demonstrates a complete open-source project setup and collaborative Git workflow: repository initialization, licensing, community guidelines, feature branching, and merging changes via a pull request.

## What it does

`Shipping_Cost_Calculator.py` takes two inputs, package weight (in kilograms) and the shipping rate (per kilogram), and calculates the total shipping cost.

## How to run it

```bash
python3 Shipping_Cost_Calculator.py
```

You'll be prompted to enter:
- Package weight in kilograms
- Shipping rate per kilogram

The script then outputs the total shipping cost in USD.

## Example

```
Enter the package weight in kilograms: 10
Enter the shipping rate per kilogram: 2.5
Shipping Cost: 25.0 USD
```

## Project setup and workflow

This repository follows standard open-source project practices:

- **License**: [Apache License 2.0](./LICENSE)
- **Code of Conduct**: [Contributor Covenant](./CODE_OF_CONDUCT.md)
- **Contributing guidelines**: see [CONTRIBUTING.md](./CONTRIBUTING.md) before submitting changes

The shipping calculator itself was developed on a feature branch (`Shipping_Calculation`) and merged into `main` through a pull request ([#1](https://github.com/Book0fEli/LogisticsShippingRates/pull/1)), following a standard collaborative Git workflow rather than committing directly to `main`.

## Tech used

`Python` · `Git` · `GitHub` (branching, pull requests, open-source project setup)

---

*Elijah Cordova — working toward a DevOps/Cloud Engineering role. Practice project from the IBM DevOps and Software Engineering Professional Certificate.*
