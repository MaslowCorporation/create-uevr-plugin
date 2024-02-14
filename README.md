
## create-uevr-plugin

This repo contains a MaslowGPT command that allows you create C++ UEVR Plugins.

How to use:

- Install the `MaslowGPT` npm package. More info here:

https://github.com/MaslowCorporation/MaslowGPT

You don't need to subscribe to the MaslowGPT API to use this tool. You can if you want ;-)

- Set your custom commands folder in MaslowGPT, with the 

```
npx maslow set-commands-folder
```

command.

- Install the create-uevr-plugin command to your MaslowGPT commands folder, with this command

```
npx maslow add-command-from-github
```

when asked what repo you want to install from, use this URL:

```
https://github.com/MaslowCorporation/create-uevr-plugin
```

- Use the `create-uevr-plugin` command in MaslowGPT, by using the

```
npx maslow run-command
```

command, and select `create-uevr-plugin` from the list of choices.

It will generate a folder containing a Visual Studio project containing your UEVR C++ plugin code. The README.md file in this generated folder will help get started, so you must READ IT. Everything is there for you to get started with VR Game Modding via UEVR.
