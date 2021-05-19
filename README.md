# Liferay Storybook Server

Runs storybook to test components inside of a liferay-portal module. Currently setup to test components in `portal-search-tuning-blueprints-admin-web`.

## Setup

1. Update paths in `.env` to your current environment.
1. Update `../../liferay-portal-master/portal/` relative paths in `./storybook/preview.js` to where the portal root is located.
