# WordPress Plugin Deploy Helper 🤾🏽‍♂️🚀
Helps to easily zip all files and folders to be ready for plugin install, the WordPress way.

Also for extraction to wordpress-org folder for auto deploy :), don't get?
https://github.com/10up/action-wordpress-plugin-deploy for more info.

### Donation
**Donate link:** I do not mind a token for ordering **Pancakes 🥞**, so you can <a href="https://rave.flutterwave.com/pay/preciousomonze" target="_blank">__Drop something for your boy 🤓 🥳__</a>

### Note
Make sure you put this file in your plugin parent directory.

Will think of doing an update for flexible file structure later 💆🏽‍♂️, can't stress 💅.

Also try to make your code sniffer ignore this file, e get why(There's a reason) ⚠️😁.

So basically, I was kind of tired when coding this, so it doesn't follow standards to the core, but you'll be fine, still good enough fam.

### Installation
#### Requirements
This requires **PHP** `>= 5.6` I know it's an obvious requirement 🤡.

#### Suggestions
You might enjoy this more using `npm package` installer, it's what i used to easily execute my cmd. e.g `npm run compress-zip`, you'll see a sample json in the repo.

Putting it in a `bash script` won't be bad also, whichever works for you.

### Command line usage

` php zipper_file.php --param1=values --param2=value1,value2 `

It takes in parameters via the **Command Line Interface(CLI)**

### Command Line Parameters
Command line options

    -h, --help                  Print usage information.
                                `--help options` for details on available options.
    -V, --version               Print version number.
    -p, --parse <options>       Specify parser options:
