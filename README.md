# Universe Database Repository

This repository contains the SQL dump file for the "universe" database created as part of the freeCodeCamp.org curriculum.

## Contents

- `universe.sql`: SQL dump file containing commands to recreate the "universe" database with sample data.
- `README.md`: This README file providing information about the repository.

## Database Description

The "universe" database is a relational database designed to store information about celestial objects such as galaxies, stars, planets, moons, and constellations. It is created following specific requirements outlined in the freeCodeCamp.org curriculum.

## How to Use

1. **Download the SQL Dump File:**
   - Clone or download this repository to your local machine.
   - Use the provided instructions to download the `universe.sql` file from the repository.

2. **Rebuild the Database:**
   - Open a terminal and navigate to the directory containing the `universe.sql` file.
   - Run the following command to rebuild the "universe" database:
     ```
     psql -U postgres < universe.sql
     ```
   - Ensure that you have PostgreSQL installed and configured on your machine.

3. **Accessing the Database:**
   - Once the database is created, you can connect to it using your preferred SQL client or command-line tool.
   - Use the credentials provided during PostgreSQL installation or as configured in your environment.

## Contributing

Contributions to this repository are welcome. If you find any issues or would like to improve the database structure or sample data, feel free to open a pull request or submit an issue.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
