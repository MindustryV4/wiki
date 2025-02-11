# Getting Started

Getting started with Mindustry is easy. This article covers how to install Mindustry on different platforms and situations. 

## Typical Setup

This is your typical, run-of-the-mill setup process.

### Desktop

1. Visit the game's [releases page](https://github.com/Acemany/MindustryV4/releases), then download a copy of the game from there. **The latest build is `alpha-63`, which we refer to as Build 63.**
2. If you have JRE already installed (which is recommended), you can also run `java -jar desktop-release.jar` on Windows and Linux.

### Android

Download .apk file from [releases page](https://github.com/Acemany/MindustryV4/releases) and install it.

### iOS

No.

## For Contributors

If you would like to contribute to the game's source code, the best way to go is to compile the game yourself or use the builds provided [here](https://github.com/Acemany/MindustryV4Builds/releases/). To compile it yourself:

1. If you haven't already, install at least JRE and JDK 8. 
2. Open a terminal in the root directory, then run these commands: 
    1. For Windows:
        1. Running: `gradlew desktop:run`
        2. Building: `gradlew desktop:dist`
    2. For Linux:
        1. Running: `./gradlew desktop:run`
        2. Building: `./gradlew desktop:dist`
    3. For Server builds, replace `desktop` with `server`. Example: `./gradlew server:run`

## For aspiring server hosts

Please keep in mind that doing this does not make you automatically cool. **Use the local LAN feature if you only want to play with one or two friends.**

A dedicated Linux or Windows machine is **highly** recommended for this.

1. If you haven't already, install at least JRE and JDK 8.
2. Download the desired server release from [BE builds](https://github.com/Acemany/MindustryV4Builds/releases/), or compile one yourself. 
3. Open a terminal or TTY session then change `cd` to the directory the JAR is placed in.
4. Run `java -jar server-release.jar`. The commands are explained in the `help` command.

If you have come this far, you should already have the skill and time to be able to port-forward if you need to.

If you do not know how to port-forward, Google "portforward your-router instructions", "your-router" being your router's model. **Portforwarding will require you to have access to your router's admin settings, which will usually be password-protected.** If you do not have access, use LogMeIn Hamachi. To find your IP, Google "what is my IP".

### NEVER SHARE YOUR PUBLIC IP WITH THE PUBLIC, UNLESS YOU ACKNOWLEDGE THE IMPLICATIONS OF DOING SO!

Your public IP is tied to your household, and if it falls into the wrong hands, it can be used to **easily** find your approximate location, even down to the city or block you live in. There is more that can happen; such as DoS attacks, data and information exploitation and collection, and unwanted access to other open ports in your network. **Exercise caution, do your research, and use a VPN if possible.**

If you would like to host a public server for public use, it is recommended that you use a domain name or DNS service to mask your IP a little bit, or use a cloud service e.g. Amazon AWS which is much safer.
