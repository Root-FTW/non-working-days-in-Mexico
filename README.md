# Mexican Holidays JSON

This repository contains a JSON file with the official non-working days in Mexico, as specified in Article 74 of the Federal Labor Law (LFT). The JSON file is designed to be consumed by other applications in English and can be used for all future years.

## Content

The `holidays.json` file in this repository includes an array of holiday objects, each representing a non-working day in Mexico. Each holiday object has the following properties:

- `name`: The name of the holiday.
- `date`: The date of the holiday in `MM-DD` format.
- `observed` (optional): Specifies how the holiday is observed when the date falls on a weekend. It can take the following values:
  - `firstMonday`: The holiday is observed on the first Monday of the month.
  - `thirdMonday`: The holiday is observed on the third Monday of the month.
- `frequency` (optional): Specifies the interval at which the holiday occurs. This is applicable only for the inauguration day, which occurs every six years.

## List of Holidays

The JSON file includes the following holidays:

1. **New Year's Day**
   - Date: January 1st (`01-01`)

2. **Constitution Day**
   - Date: February 5th (`02-05`)
   - Observed: First Monday of February

3. **Benito Juárez's Birthday**
   - Date: March 21st (`03-21`)
   - Observed: Third Monday of March

4. **Labor Day**
   - Date: May 1st (`05-01`)

5. **Independence Day**
   - Date: September 16th (`09-16`)

6. **Revolution Day**
   - Date: Novermber 20th (`11-20`)
   - Observed: Third Monday of November

7. **Inauguration Day**
   - Date: December 1st (`12-01`)
   - Frequency: Every six years

8. **Christmas Day**
   - Date: December 25th (`12-25`)

Please note that all dates are mentioned in `MM-DD` format.

## Usage

You can use this repository to easily access and integrate the Mexican holidays into your applications. By consuming the `holidays.json` file, you can ensure that the holidays are accurately reflected in your app for all future years.

## Contributing

If you find any inaccuracies or missing information in the JSON file, or if new holidays are added by federal or local laws, feel free to contribute to this repository. Simply create a pull request with the proposed changes, and they will be reviewed and merged if appropriate.

## License

This repository is licensed under the [MIT License](LICENSE), allowing you to use, modify, and distribute the JSON file freely.

---
*Disclaimer: This information is based on the Federal Labor Law (LFT) and may be subject to change. It is always recommended to consult the latest official sources for any legal or official references.*
