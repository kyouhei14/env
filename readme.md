## Local Development
> [!CAUTION]
> This is only for .env main source is private, please note that it's only allowed for personal use
> **Commercial use is not recommended**

#### 1. Environment Variable file setup
1. Copy all the contents of `.env.example` into a new file called `.env`


#### 2. Backend Repository (Consumet API)
> [!TIP]
> If you already have a backend URL from somewhere, you can skip this step and go to step 3

1. Clone the backend repository and install the dependencies:
```bash
$ git clone https://github.com/consumet/api.consumet.org.git
$ cd api.consumet.org
$ npm install # Or yarn install
```

2. Start the backend server
```bash
$ npm start
```

3. Put your backend URL into the `NEXT_PUBLIC_CONSUMET_URL` variable in the `.env` file

#### 3. Frontend Repository (Hirako)
1. Clone this repository and install the dependencies:
```bash
$ git clone 
$ cd 
$ npm install # Or yarn install
```

2. Start the development server
```bash
$ npm run dev
```
4. Open the project in your browser:
```
http://localhost:3000
```

#### Extra Steps (OPTIONAL)
- If you want, you can host a CORS proxy. The recommended CORS proxy for this project is this one: [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere). You can host this on vercel and save the link into the `NEXT_PUBLIC_CORS_REQUEST_LINK` variable in the `.env` file
- You can turn on your own website tracking with Google Analytics, go to https://analytics.google.com/ and follow their setup instructions. Save the Tracking ID into the `NEXT_PUBLIC_GA_TRACKING_ID` variable in the `.env` file
- You can turn on your own website tracking with Umami, go to https://umami.is/ and follow their setup instructions. Save the Website ID into the `NEXT_PUBLIC_UMAMI_WEBSITE_ID` variable in the `.env` file
- You can turn on live customer communication with Tawk.to, go to https://tawk.to and follow their setup instructions. Save the Property ID and Widget ID into the `NEXT_PUBLIC_TAWKTO_PROPERTY_ID` and `NEXT_PUBLIC_TAWKTO_WIDGET_ID` variables, respectively

## Credits
- [Consumet API](https://github.com/consumet/api.consumet.org) for all anime details and sources
- [Anilist](https://anilist.co/) was used to provide extensive episode details and statistics

## License
This project is licensed under the GNU General Public License v3.0 - see the [License](https://github.com/kyouhei14) file for more details

## Contact
Thanks for checking my project out

If you have any questions or feedback, go to my [website](rajveer.is-a.dev) and pick your preferred method of contact. You can also join the community Discord server I made down below:

[![Discord Banner]([https://discordapp.com/api/guilds/1128820150846632026/widget.png?style=banner2](https://discord.c99.nl/widget/theme-1/936851463672573952.png))](https://discord.gg/portmafia)
