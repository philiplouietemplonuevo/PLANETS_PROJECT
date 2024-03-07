### HABITABLE PLANETS FINDER

This Node.js application parses through the Kepler mission data to identify potentially habitable planets. It filters the planets based on specific criteria such as disposition, insolation flux, and planetary radius.

## Features

- Parse Kepler mission data from a CSV file.
- Identify planets that are potentially habitable based on:
  - Confirmed disposition.
  - Insolation flux between 0.36 and 1.11.
  - Planetary radius less than 1.6 times that of Earth's.
- Outputs the names and total count of habitable planets found.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Node.js installed on your machine.
- `csv-parse` package installed in your project.

## Installation

To install `csv-parse`, run the following command in your project directory:

```
npm install csv-parse
```

## Usage

1. Place your `kepler_data.csv` file in the root directory of your project.
2. Run the script with Node.js:

```
node index.js
```

Replace `index.js` with the name of your main script file if it's different.

## Contributing

Contributions to the Habitable Planets Finder are welcome. If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgments

- This project was inspired by the Kepler mission's search for habitable planets.
- This project is part of the Complete Node.js Developer in 2024: Zero to Mastery course
