# Privacy Policy

Last updated: 27 September 2026

This policy covers "Personal Health Dashboard", a personal, single-user application registered with the Oura API.

## Scope

The application is operated by its author for their own use only. It has no other users, no sign-up, and no public interface.

## Data accessed

With the owner's explicit consent, given through Oura's OAuth2 authorisation screen, the application reads the owner's own Oura Ring data. This may include daily sleep, readiness, activity, stress and resilience summaries, heart rate and heart rate variability, SpO2, body temperature deviation, workouts, sessions, tags, ring configuration and battery level, and basic personal details such as age, height and weight. The Oura account email address is not requested.

## Storage

All retrieved data is stored locally on the owner's own computer in a SQLite database file. Nothing is uploaded to any server, hosted service, or third party.

## Use

Data is displayed in a dashboard that runs on localhost and is used to calculate trends and deviations from the owner's own historical baseline. No processing is performed on behalf of anyone else.

## Sharing

No data is sold, shared, transmitted, or disclosed to any third party. The application contains no analytics, tracking, advertising, or external integrations.

## Retention and revocation

Data is retained until the owner deletes the local database file. Access can be withdrawn at any time from the owner's Oura account settings or through Oura's token revocation endpoint, after which the application can no longer retrieve data.

## Security

OAuth client credentials and tokens are held in a local environment file that is excluded from version control and never committed to this repository.

## Contact

Questions may be raised as an issue on this repository.
