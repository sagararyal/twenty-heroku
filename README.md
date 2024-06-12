# Twenty CRM - One-Click Deploy to Heroku

Deploy Twenty CRM to Heroku with one click:

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?button-url=https://github.com/sagararyal/twenty-heroku&template=https://github.com/sagararyal/twenty-heroku)

## Prerequisites

- [Heroku Account](https://signup.heroku.com/)

## Deployment Steps

1. Click the **Deploy to Heroku** button above.
2. Fill in the required app name and settings.
3. Click **Deploy App** at the bottom of the page.
4. Wait for the app to deploy and click **View** to see it in action.

## Environment Variables

The following environment variables are automatically set during deployment:

- `ACCESS_TOKEN_SECRET`
- `LOGIN_TOKEN_SECRET`
- `REFRESH_TOKEN_SECRET`
- `FILE_TOKEN_SECRET`
- `SERVER_URL`
- `FRONT_BASE_URL`
- `PG_DATABASE_URL`
- `NODE_ENV`

## Additional Configuration

After deployment, you may need to configure additional settings or add-ons depending on your usage.

---

For any issues or contributions, please open an issue or pull request.