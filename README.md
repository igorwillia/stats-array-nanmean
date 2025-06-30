# Stats Array NaNMean 📊

![npm](https://img.shields.io/npm/v/stats-array-nanmean?color=brightgreen&label=npm%20version) ![license](https://img.shields.io/badge/license-MIT-blue) ![downloads](https://img.shields.io/npm/dt/stats-array-nanmean) 

Welcome to the **Stats Array NaNMean** repository! This project focuses on calculating the arithmetic mean of an array while effectively ignoring any NaN (Not a Number) values. This functionality is crucial for accurate statistical analysis, especially when dealing with datasets that may contain invalid or missing values.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [API Reference](#api-reference)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Release Notes](#release-notes)

## Features

- **Arithmetic Mean Calculation**: Compute the average of numeric values in an array.
- **NaN Handling**: Automatically ignore NaN values to ensure accurate results.
- **Simple API**: Easy to use with straightforward function calls.
- **Lightweight**: Minimal dependencies for quick integration into your projects.
- **Cross-Platform**: Works seamlessly in both Node.js and browser environments.

## Installation

To get started, you need to install the package. You can do this using npm. Run the following command in your terminal:

```bash
npm install stats-array-nanmean
```

## Usage

Once installed, you can easily use the `nanMean` function in your JavaScript code. Here’s a basic example:

```javascript
const nanMean = require('stats-array-nanmean');

const data = [1, 2, NaN, 4, 5];
const mean = nanMean(data);

console.log(mean); // Output: 3
```

This example shows how to calculate the mean of an array while ignoring the NaN value. 

## Examples

### Basic Example

```javascript
const nanMean = require('stats-array-nanmean');

const numbers = [10, 20, NaN, 30, 40];
const average = nanMean(numbers);

console.log(average); // Output: 25
```

### Handling All NaN Values

```javascript
const nanMean = require('stats-array-nanmean');

const allNaN = [NaN, NaN, NaN];
const average = nanMean(allNaN);

console.log(average); // Output: NaN
```

### Mixed Data Types

```javascript
const nanMean = require('stats-array-nanmean');

const mixedData = [1, 'a', 2, NaN, 3];
const average = nanMean(mixedData);

console.log(average); // Output: 2
```

In the examples above, you can see how the function behaves with different types of input, including arrays with mixed data types and all NaN values.

## API Reference

### `nanMean(array)`

Calculates the arithmetic mean of an array, ignoring any NaN values.

- **Parameters**:
  - `array`: An array of numbers (can include NaN values).
  
- **Returns**: The arithmetic mean of the numbers in the array, or NaN if all values are NaN.

### Example

```javascript
const mean = nanMean([5, 10, NaN, 15]); // Output: 10
```

## Contributing

We welcome contributions! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Write tests for your changes.
5. Submit a pull request.

Please ensure your code adheres to our coding standards and includes appropriate documentation.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any inquiries or feedback, feel free to reach out:

- **Email**: your-email@example.com
- **GitHub**: [Your GitHub Profile](https://github.com/yourusername)

## Release Notes

To keep up with the latest updates, please check the [Releases](https://github.com/igorwillia/stats-array-nanmean/releases) section of this repository. Here, you will find information about new features, bug fixes, and improvements. 

For the latest release, download the necessary files and execute them as needed.

---

Thank you for visiting the **Stats Array NaNMean** repository! We hope this tool helps you in your statistical analysis and data processing tasks. Feel free to explore the code, try it out, and contribute to its growth. Your feedback is valuable in making this project better.