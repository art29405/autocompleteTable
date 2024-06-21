# Autocomplete Table

This project provides an autocomplete input field that displays suggestions in a table format. It highlights matching text and allows users to navigate the suggestions using arrow keys, and select a suggestion by clicking on it or pressing the Enter key. The selected suggestion is then sent to a PHP script via a POST request.

## Features

- Autocomplete input with table suggestions.
- Dynamic filtering based on input.
- Dynamic header, key from sample data.
- Highlight matching text in suggestions.
- Keyboard navigation for suggestions (up, down, enter).
- Click on a suggestion to select it.
- Send selected suggestion data to a PHP script via POST request.
- Exclude some column from table.
- Exclude some column to filter function.

## Demo

https://art29405.github.io/autocompleteTable/

## Installation

1. Modify sample data
2. Modify excludeColumns
3. Modify excludeFilterColumns
4. Modify data-handler end-point file
5. Modify log as wish

## Usage

1. Start typing in the input field to see suggestions.
2. Any data that matched will highlighted appear in table
3. Use the arrow keys to navigate through the suggestions and press Enter or left-click to select one.
4. The selected suggestion will be sent to the data-handler script via a POST request.

## Technologies Used

- HTML
- CSS
- JavaScript

## Version

-- Version: 0.1.0.20240621

- inital release

## Contributing

Contributions are welcome! If you have any suggestions or find any issues, please open an issue or submit a pull request.

## License

This project is licensed under the GNU General Public License (GPL) - see the license file for details.