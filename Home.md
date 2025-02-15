# RSBot [v2.9.9](https://github.com/SDClowen/RSBot/releases/latest)

Welcome to the RSBot Wiki!  
Contents are subject to major change, as there have been 8 major releases since the wiki's initial write. More text will be added to describe each specific option.

## Links

- If you have any feedback or suggestions visit the [Discord](https://discord.gg/MuY5ejEU3r).
- If you'd like to report bugs you've encountered, use [GitHub](https://github.com/SDClowen/RSBot/issues).
- [Repo](https://github.com/SDClowen/RSBot)
- [FOSSA](https://app.fossa.com/projects/git%2Bgithub.com%2FSDClowen%2FRSBot?ref=badge_shield)
- [LICENSE](https://github.com/SDClowen/RSBot/blob/master/LICENSE)
- [Facebook](https://www.facebook.com/rsbotofficial)
- [Sponsor the project!](https://www.buymeacoffee.com/sdclowen)

## Supported clients

| Region          | Version                            |
|:----------------|:-----------------------------------|
| Japanese Old    | JSRO_SL                            |
| Thailand        | Blackrogue 100                     |
| Thailand        | Blackrogue 110                     |
| Vietnam         | vSRO 188                           |
| Vietnam         | vSRO 193                           |
| Vietnam         | vSRO 274                           |
| Taiwan          | TSRO 110                           |
| Chinese         | cSRO/-R                            |
| Global          | iSRO (International Silkroad)      |
| Turkey          | TRSRO                              |
| Korean          | KSRO                               |
| Rigid           | iSRO (International Silkroad 2015) |
| ~~Chinese Old~~ | ~~MHTC~~                           |
| ~~Japanese-R~~  |                                    |

## FAQ

### How to run multiple clients (easily)

Create new profiles for each character you want to open for demonstration purposes.
Let's say you name them 1 through 8.

To launch a new bot instance with the new profiles while starting the bot, you've to pass in the name of the profile as an argument to the executable.
Here are some ways to do this:

### 1 Terminal

Run
`..\RSBot.exe <1-8>`

### 2 Scripts

You can create a batch script like so:

```bat
START "" RSBot.exe 1
timeout /t 1 /nobreak
START "" RSBot.exe 2
timeout /t 1 /nobreak
START "" RSBot.exe 3
...
```

> [!IMPORTANT]
> The delay between launching each bot instance is required because of some initialization conflicting with each other.
> Increase the delay if your computer is slow,

### 3 Shortcuts

1. Create a shortcut pointing to the executable
2. Go to the properties of the shortcut
3. On the line `Target` append profile name `..\RSBot.exe <1-8>`
4. Launch each profile using the shortcuts

### Client gets stuck when issued to train

Disable `Enable collision detection` from `Map` subsection

## Contributors of the Wiki

### Main writer/maintainer of the wiki

[Egezenn](https://github.com/Egezenn)
