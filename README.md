# Poultry Feed Grain Database

A collaborative, version-controlled database of common grains used in U.S. poultry diets. This database serves as a central, traceable resource for nutritional data, facilitating future diet formulation and analysis.

## Data Schema

The main data file `grains.csv` contains the following columns:

- `Grain`: Name of the grain or feed ingredient
- `Crude_Protein_pct`: Crude protein content (percent dry matter)
- `Metabolizable_Energy_kcalkg`: Metabolizable energy (kcal/kg, as-fed basis)
- `Crude_Fiber_pct`: Crude fiber content (percent dry matter)

Additional columns may be added in the future (e.g., amino acid profiles, phosphorus content, price indices).

## Contribution Guidelines

1. **Fork the repository** and create a feature branch.
2. **Add or modify data** in `grains.csv`. Ensure data follows the established schema and includes reliable sources (add a `Source` column if needed).
3. **Open a Pull Request** with a clear description of the changes and reference any related issues.
4. **Review** will be conducted by project maintainers to verify data accuracy and consistency.
5. **Merging** will follow a squash‑and‑merge policy to keep the commit history clean.

## License

This database is made available under the [MIT License](LICENSE).