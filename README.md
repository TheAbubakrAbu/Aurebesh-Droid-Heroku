# Aurebesh Droid — Heroku Deployment

This repository contains the **Linux-ready Aurebesh Droid Discord Bot binary** and configuration needed to deploy the bot to **Heroku** using this [Binary Buildpack](https://github.com/heroku/heroku-buildpack-static).

[**Add Aurebesh Droid to Your Server**](https://discord.ly/aurebesh-droid)

Created by **Abubakr Elmallah** on **June 28, 2025**.

## Features

- Aurebesh translation commands (`/translate`, `/alphabet`)
- Jedi & Sith Holocrons (`/holocron`, `/holocron_jedi`, `/holocron_sith`)
- Instant Aurebesh PNG rendering for translated text
- Built using [D++](https://dpp.dev) in modern C++

## Deploy to Heroku

1. **Clone this Repository**

```bash
git clone https://github.com/TheAbubakrAbu/Aurebesh-Droid-Heroku.git
cd Aurebesh-Droid-Heroku
````

2. **Create and Configure the Heroku App**

```bash
heroku create aurebesh-droid --stack=heroku-22
heroku buildpacks:set https://github.com/jaymecd/heroku-buildpack-binary.git
```

3. **Set the Discord Bot Token**

```bash
heroku config:set DISCORD_TOKEN=your_token_here
```

4. **Deploy the Binary**

```bash
git push origin main
```

## Full Source Code

To view or contribute to the full C++ source:

**[Main Repo: github.com/TheAbubakrAbu/aurebesh-droid](https://github.com/TheAbubakrAbu/aurebesh-droid)**

## Privacy & Data

**Aurebesh Droid** respects your privacy:
- **No Personal Data Collected** – Only temporary game data is stored.
- **Secure & Compliant** – Fully adheres to Discord’s Terms of Service and Privacy Policy.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code, but please provide attribution.

## Feedback

I would love to hear your thoughts and suggestions! Feel free to open an issue or contact me.

## Contact

For feedback, feature requests, or questions, feel free to reach out:
- **Email**: ammelmallah@icloud.com
- **Website**: [abubakrelmallah.com](https://abubakrelmallah.com/)
- **LinkedIn**: [linkedin.com/abubakr](https://www.linkedin.com/in/abubakr-elmallah-416a0b273/)

Created by **Abubakr Elmallah**