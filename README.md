# GlobalTimeZones

This repository contains a comprehensive list of sovereign states, their time zones, unique offsets, and countries with multiple time zones. The data is useful for applications requiring accurate and up-to-date time zone information, such as scheduling systems, geolocation-based apps, and international business solutions.

## Features
- **Countries with Multiple Time Zones**: Lists all time zones for countries spanning multiple zones.
- **Unique Time Zone Offsets**: Highlights offsets used globally, including rare cases like Nepal and Iran.
- **Regular Updates**: Contributions from the community ensure the data remains current.

## Data Format
The data is stored in JSON format, making it easy to parse in any programming language. Example:

```json
{
    "countries": [
        {
            "name": "United States",
            "primary_time_zone": "America/New_York",
            "other_time_zones": ["America/Chicago", "America/Denver", "America/Los_Angeles"],
            "unique_offsets": [-18000, -21600, -25200, -28800]
        },
        {
            "name": "India",
            "primary_time_zone": "Asia/Kolkata",
            "unique_offsets": [19800]
        }
    ]
}
```

### Contributions
Fork the repository.
Update timezones.json with new or corrected data.
Submit a pull request for review.
We welcome contributions from developers and time zone enthusiasts around the world!

