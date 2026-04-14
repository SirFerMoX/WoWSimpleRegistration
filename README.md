# 🌍 Blizzlike Simple Registration Page for TrinityCore/AzerothCore/AshamaneCore/CMangos

Create a versatile website for your game server with this easy-to-use script, featuring compatibility with major server cores.

Supported Cores:

- [AzerothCore](http://azerothcore.org)
- [TrinityCore](http://TrinityCore.org)
- [AshamaneCore](https://github.com/AshamaneProject/AshamaneCore/)
- [CMangos](https://github.com/cmangos/)

### ⭐ If you liked the project, feel free to give it a shining star. ⭐

<a href="https://github.com/SirFerMoX/BlizzSimpleRegistration">
   <img title="Star on GitHub" src="https://img.shields.io/github/stars/masterking32/WoWSimpleRegistration.svg?style=social&label=Star">
</a>
<a href="https://github.com/SirFerMoX/BlizzSimpleRegistration/fork">
   <img title="Fork on GitHub" src="https://img.shields.io/github/forks/masterking32/WoWSimpleRegistration.svg?style=social&label=Fork">
</a>

## 🖱️ Prerequisites

Ensure PHP version 8.0 or higher is installed and the following extensions are enabled:

- [GMP Extension](https://www.php.net/manual/en/book.gmp.php)
- [GD Extension](https://www.php.net/manual/en/book.image.php)
- [ZIP Extension](https://www.php.net/manual/en/book.zip.php)
- [Soap Extension](https://www.php.net/manual/en/book.soap.php)
- [Mbstring Extension](https://www.php.net/manual/en/book.mbstring.php)
- [PDO Extension](https://www.php.net/manual/en/book.pdo.php)
- [PDO-MySQL Extension](https://www.php.net/manual/en/ref.pdo-mysql.php)

## ⚙️ Installation Guide (Last version - PHP 8)

1. Fulfill the above prerequisites on your server.

2. Obtain the project files:

   - Download and unzip the project, or clone it using Git:

     ```bash
     git clone https://github.com/SirFerMoX/BlizzSimpleRegistration
     ```

3. Install [Composer](https://getcomposer.org/download/).

4. Navigate to the project directory and then go to the `application/` directory.

5. Run the following command to install the required dependencies:

   ```bash
   composer install
   ```

6. Navigate to the `application/config/` directory and rename the file `config.php.sample` to `config.php`.

7. Edit the newly renamed `config.php` file, inserting your server details. Note that if using the "Image Captcha" feature, PHP's GD2 module must be enabled.

8. Once the configuration is complete, your registration page should be operational.

# 🪛 Debugging

Encountering a blank page can be a common issue, typically indicating a hidden error that needs to be diagnosed. To facilitate troubleshooting, enable `debug_mode` in the configuration file.

Here’s how to enable debug mode:

- Open the `config.php` file.
- Locate the `$config['debug_mode']` parameter.
- Set it to `true` to enable debug mode.

⚠️ **Important: Remember to disable debug mode** once you have resolved the issues. Debug mode should be set to `false` before deploying the website in a production environment or going live. This helps to ensure security and performance are not compromised.

## ✅ Features

1. **Registration Page**: Accommodating a wide range of game versions, including Vanilla, TBC, WotLK, MoP, WoD, Legion, BFA, and TWW.
2. **Online Players Status**: Check who's online on the server, with support for multiple realms.
3. **Leaderboards**: Display top players based on Playtime, Kills, Honor Points, Arena Points, and Arena Teams across different realms.
4. **Connection Guide**: Step-by-step ‘How to connect’ page for new players.
5. **Contact Form**: Accessible ‘Contact us’ page for inquiries and support.
6. **Multiple Themes**: Choose from various templates such as Light, Icecrown, Kaelthas, Advance, and Battle for Azeroth.
7. **Password Management**: Facilities to change (as of April 10, 2019) and recover passwords (as of May 31, 2019).
8. **Vote System**: Engage your community with a voting system (added on April 3, 2020).
9. **Captcha Integration**: Protect your site with HCaptcha/Recaptcha v2/Cloudflare Turnstile (since July 27, 2020).
10. **Two-Factor Authentication (2FA)**: Add an extra layer of security with 2FA (introduced on July 28, 2020).
11. **Multilingual Support**: Making the site accessible to a global audience with support for various languages (added on September 10, 2020), including:
    - 🇬🇧 English
    - 🇮🇷 Persian
    - 🇮🇹 Italian
    - 🇨🇳 Chinese Simplified
    - 🇹🇼 Chinese Traditional
    - 🇸🇪 Swedish
    - 🇫🇷 French
    - 🇩🇪 German
    - 🇪🇸 Spanish
    - 🇰🇷 Korean
    - 🇷🇺 Russian
    - 🇵🇹 Portuguese

- Allowed multiple accounts to share one email address for non-battle.net servers.
- Changed the user identification method from email to username for password change and restoration features on non-battle.net servers.
- Added the option to enable or disable the display of top players and online players.

## 🖼️ Screenshots

### Advance Template

![Advance Template Screenshot](https://raw.githubusercontent.com/masterking32/WoWSimpleRegistration/master/screenshots/a-bfa-min.jpg)

### Battle for Azeroth Template

![Battle for Azeroth Template Screenshot](https://raw.githubusercontent.com/masterking32/WoWSimpleRegistration/master/screenshots/b1.jpg)

### Light Template

![Light Template Register Page Screenshot](https://raw.githubusercontent.com/masterking32/WoWSimpleRegistration/master/screenshots/1.jpg)

### IceCrown Template

![IceCrown Template Home Page Screenshot](https://raw.githubusercontent.com/masterking32/WoWSimpleRegistration/master/screenshots/i1.jpg)

### Kael'thas Template

![Kael'thas Template Home Page Screenshot](https://raw.githubusercontent.com/masterking32/WoWSimpleRegistration/master/screenshots/k1.jpg)

Looking for more visuals? [Browse additional screenshots here.](https://github.com/masterking32/WoWSimpleRegistration/tree/master/screenshots)

## ⬇️ Credits

### 🧑‍💻 Programming

- **Lead Developer**: [Amin.MasterkinG](https://masterking32.com)

**Contributors:**
- [Phentora](https://github.com/Phentora)
- [imsamdez](https://github.com/imsamdez)
- [rescr1pt](https://github.com/rescr1pt)
- [masoudr](https://github.com/masoudr)
- [jkcgs](https://github.com/jkcgs)
- [funjoker](https://github.com/funjoker)
- [eshamwatajevian](https://github.com/eshamwatajevian)
- [den13501](https://github.com/den13501)
- [PowerpuffIO](https://github.com/PowerpuffIO)

### 🫂 Translations

- **English/Persian**: [Amin.MasterkinG](https://github.com/masterking32)
- **Italian**: [Helias](https://github.com/helias)
- **Chinese Simplified/Traditional**: [Coolzoom](https://github.com/coolzoom), [oiuv](https://github.com/oiuv)
- **Swedish**: [Kitzunu](https://github.com/Kitzunu)
- **French**: [Kalorte](https://github.com/Kalorte)
- **German**: [DuelistRag3](https://github.com/DuelistRag3)
- **Spanish**: [xjose93](https://github.com/xjose93)
- **Korean**: [KOREAFTP](https://github.com/KOREAFTP)
- **Russian**: [Haeniken](https://github.com/Haeniken)
- **Portuguese**: [xnexuiz](https://github.com/xnexuiz)

Heartfelt thanks to all the contributors for their invaluable support and contributions to this project.
