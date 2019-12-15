[![cf Version Shield](https://img.shields.io/badge/dynamic/json?color=brightgreen&style=plastic&logo=GitHub&label=version&query=tag_name&url=https%3A%2F%2Fapi.github.com%2Frepos%2FAdamDanischewski%2Fcf%2Freleases%2Flatest)](https://api.github.com/repos/AdamDanischewski/cf/releases/latest) [![cf deb package available](https://img.shields.io/badge/deb-package-orange?style=plastic&logo=Ubuntu)](https://github.com/AdamDanischewski/cf/raw/debian/cf_head_all.deb) [![Awk programming language](https://img.shields.io/badge/awk-lang-blue?style=plastic)](https://pement.org/awk/awk1line.txt)

# cf 
### cf custom colors piped filenames w/Truecolor sRGB
`cf` improves the commandline user experience by adding extensive filename
coloring capabilities via pipelines. `cf` colorizes mapped file extensions
to a Truecolor sRGB triplet - maintaining consistency across environments.

`cf` is fast, efficient and works out-of-the-box with colorful presets.

To get started using `cf` - just install and run `cf -A` to add an `ls` alias.

Then if you wish to customize run `cf -C` to create a user config file.

#### Usage: 
![cf usage ss](https://raw.githubusercontent.com/AdamDanischewski/cf/assets/cf_usage_ss_1.png)

#### Man page:
![cf man page](https://raw.githubusercontent.com/AdamDanischewski/cf/assets/cf_man_ss_1.png)

#### Out of the Box Defaults - Screenshot: 
![cf ss](https://raw.githubusercontent.com/AdamDanischewski/cf/assets/cf_ss_1.png)

#### Installation: 
You can install cf via the included `install.bsh`.<br>
> To install, clone the repository and run: 
```shell 
$> ./install.bsh
```
> To remove, run: 
```shell
$> ./install.bsh -R 
```
Or, if you use Debian/Ubuntu you can use the packaged [deb](https://github.com/AdamDanischewski/cf/raw/debian/cf_head_all.deb).
> Download the latest packaged deb, make sure you are in the same directory as the downloaded deb and run: 
```shell 
$> sudo dpkg -i cf_head_all.deb
```
