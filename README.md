# SRMS Connect Database

This repository serves as the online database for the SRMS Connect mobile application. It contains JSON files that store all the application data in a structured format.

## Structure

The repository contains the following files:

- `aktu_validation_data.json` - AKTU validation data for student verification
- `alumni.json` - Alumni profiles and information
- `events.json` - Campus events and activities
- `forum_topics.json` - Community forum topics and replies
- `internships.json` - Internship opportunities
- `marketplace_items.json` - Marketplace listings for buying/selling
- `skills.json` - Skill development courses and workshops
- `study_materials.json` - Academic study materials
- `users.json` - User account information

## Usage

This repository is accessed by the SRMS Connect application to provide real-time data to users. The application uses the GitHub API to:

1. Fetch data when the app is launched
2. Cache the data locally for offline access
3. Update the repository when changes are made by authorized users

## Data Format

All data is stored in standard JSON format with consistent schemas for each data type.

## Security

- User passwords in the `users.json` file should be properly hashed in a production environment
- This repository should be kept private if it contains sensitive information
- Use GitHub tokens for secure access from the application

## Contributing

If you're a developer working on the SRMS Connect application, please follow these guidelines:

1. Never commit sensitive or personal data
2. Maintain the existing schema structure
3. Use descriptive commit messages
4. Test your changes in a development environment before pushing

## License

This data repository is proprietary and intended for use only with the SRMS Connect application. 