# Tiling
a basic tool to tile windows with xdotool on 21:9 ultrawides

xfce inbuilt tiling support was too restrictive

## Install
1. Put the script somewhere
1. Make it executable

## Usage
1. Setup keyboard shortcuts to the ``` script <arg> ``` (e.g. ``` tiling left-top ```)

If you are using XFCE you can run ``` tiling xfce-install ``` which will run xfconf-query and install the default key layout

## Layouts/Sizes (+any combination)
```
 size (%)      args                            key combo
 ------------------------------------------------------------------------------

 33/50 x 6     [left|mid|right][top|bottom]    <Super>KP_[123789]
 +---------++---------++---------+
 |         ||         ||         |
 |         ||         ||         |
 |         ||         ||         |
 +---------++---------++---------+
 +---------++---------++---------+
 |         ||         ||         |
 |         ||         ||         |
 |         ||         ||         |
 +---------++---------++---------+

 33/100 x 3    [left|mid|right]-full           <Super><Primary>KP_[1-3]
 +---------++---------++---------+
 |         ||         ||         |
 |         ||         ||         |
 |         ||         ||         |
 |         ||         ||         |
 |         ||         ||         |
 |         ||         ||         |
 |         ||         ||         |
 |         ||         ||         |
 +---------++---------++---------+

 66/100 x 1    [left|right]-2t                 <Super><Primary>KP_[46]
 +---------++--------------------+
 |/////////||                    |
 |\\\\\\\\\||                    |
 |/////////||                    |
 |\\\\\\\\\||                    |
 |/////////||                    |
 |\\\\\\\\\||                    |
 |/////////||                    |
 |\\\\\\\\\||                    |
 +---------++--------------------+

 100/50 x 2    [top|bottom]-full               <Super><Primary>KP_[58]
 +-------------------------------+
 |                               |
 |                               |
 |                               |
 +-------------------------------+
 +-------------------------------+
 |                               |
 |                               |
 |                               |
 +-------------------------------+

 50/100 x 2    [left|right]-full               <Super>KP_[46]
 +--------------+ +--------------+
 |              | |              |
 |              | |              |
 |              | |              |
 |              | |              |
 |              | |              |
 |              | |              |
 |              | |              |
 |              | |              |
 +--------------+ +--------------+

 100/100       full                            <Super>KP_5
 +-------------------------------+
 |                               |
 |                               |
 |                               |
 |                               |
 |                               |
 |                               |
 |                               |
 |                               |
 +-------------------------------+
```
