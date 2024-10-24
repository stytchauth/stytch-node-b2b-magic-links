# Stytch: Node.js B2B Magic Links Demo

This is a quickstart example project for getting up and running with B2B
authentication. This project includes:

- Email Magic Links
- Sessions
- Google OAuth

## Setup

### Prerequisites

- Node `^20.14.0` (an `.nvmrc` file is present if you use NVM).
- Created an account with Stytch and have access to the Stytch Dashboard.
  - The Project ID and Secret associated with your Stytch Project (accessible from the dashboard).

#### 1. Clone the repository.

```shell
git clone git@github.com:stytchauth/stytch-b2b-node-quickstart.git
```

#### 2. Populate environment variables.

First, copy the `.env` file template:

```shell
cp .env.template .env
```

Then populate `STYTCH_PROJECT_ID` and `STYTCH_SECRET` with the secret variables obtained
from your dashboard.

#### 3. Install dependencies.

```shell
npm i
```

#### 4. Start the server.

```shell
npm run server
```

## Next steps

This example app showcases a small portion of what you can accomplish with Stytch. Next, explore adding additional login methods, such as [SSO](https://stytch.com/docs/b2b/guides/sso/initial-setup).

## Get help and join the community

#### :speech_balloon: Stytch community Slack

Join the discussion, ask questions, and suggest new features in our ​[Slack community](https://stytch.com/docs/resources/support/overview)!

#### :question: Need support?

Check out the [Stytch Forum](https://forum.stytch.com/) or email us at [support@stytch.com](mailto:support@stytch.com).
