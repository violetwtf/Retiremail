<p align="center">
  <img src="https://violet.lgbt/Retiremail.png">
</p>

# Retiremail
A small script to notify users of retired email accounts. I made this because I needed it to use it myself, for violet.wtf, but feel free if you want to use it, too.

## Try it yourself!
Below is a table of addresses you can email, and the config values present with them on a live server. Email any, or all of them, if you want to see Retiremail in action!

Address | Personal | Suspended | GitHub
--- | --- | --- | ---
<rm-demo-personal@violet.wtf> | true | false | null
<rm-demo-suspended@violet.wtf> | true | true | null
<rm-demo-project@violet.wtf> | false | false | null
<rm-demo-github@violet.wtf> | false | false | `violetwtf/Retiremail`

## Prerequisites
* Mail server
* Retired mail account(s)
* SendGrid API key

## Installation
Clone the repository
```
git clone https://github.com/violetwtf/retiremail
```
Install the dependencies
```
npm i
```
Edit the configuration file to your liking
```
cd retiremail
nano config.json
```
Start the application
```
node .
```

## License
Retiremail is licensed under the MIT license. See [LICENSE.md](https://github.com/violetwtf/Retiremail/blob/master/LICENSE.md)

## Support
[Create an issue](https://github.com/violetwtf/retiremail/issues/new), [a pull request](https://github.com/violetwtf/retiremail/pulls), or an email to <retiremail@violet.wtf>.
