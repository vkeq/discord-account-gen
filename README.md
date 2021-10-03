# discord-account-gen

## ❗Prerequisites❗
- [Node.js](https://nodejs.org/en/download/)
- A code editor [VSC](https://code.visualstudio.com/) , [atom](https://atom.io/) , [Sublime Text 3](http://www.sublimetext.com/) , [Codespaces](https://github.com/features/codespaces)

## Set-Up

**1.** Open Command Promp
> `WINDOWS` and search `CMD`

 **2.** Clone the repo:
 > `git clone https://github.com/eryycr/discord-account-gen.git`

**3.** extract the .zip file

**4.** open the folder in cmd:
> `cd discord-account-gen-main`

**5.** open setup.bat:
> `wait until the CMD window closes automatically`

**6.** edit settings:
> ```
   // Settings
  const captchakey = ''
  const PROXY_ADDR = ''
  const PROXY_USERNAME = ''
  const PROXY_PASSWORD = ''
  const BROWSER_CONFIG = {
    args: [
      '--no-sandbox',
      '--disable-setuid-sandbox',
      '--disable-infobars',
      '--window-position=0,0',
      "--proxy-server=" + PROXY_ADDR,
      '--window-size=1600,900',
    ],
    defaultViewport: null,
    ignoreHTTPSErrors: true,
    headless: false,
  }
> ```
