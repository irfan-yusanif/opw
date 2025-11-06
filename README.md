# OPW Flutter App

This is a Flutter web application for event planning and management.

## Security Notice

This repository excludes build files (`web/`, `build/`) to prevent accidental exposure of sensitive information like API keys.

## Important Notes

- **Never commit build files** - The `web/` directory is gitignored to prevent secrets exposure
- **Use environment variables** for API keys (Stripe, Azure Maps, etc.)
- **Build locally** for development and testing

## Setup

1. Clone this repository
2. Set up your environment variables for API keys
3. Run `flutter build web` to generate the web build locally
4. Deploy the `web/` folder to your hosting service

## Environment Variables Required

- `STRIPE_PUBLISHABLE_KEY` - Your Stripe publishable key
- `STRIPE_SECRET_KEY` - Your Stripe secret key (server-side only)
- `AZURE_MAPS_KEY` - Your Azure Maps subscription key

**Note**: This repository was cleaned to remove accidentally committed secrets. All sensitive data should be handled through environment variables or secure configuration management.
