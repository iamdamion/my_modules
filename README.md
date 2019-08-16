## <p align="center">Custom Python Modules</p>   
<p align="center"> Created by Damion V. Demeter</p>   

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/b7521b9839c6464e9f70bb7c5b70d6e0)](https://app.codacy.com/app/iamdamion/my_modules?utm_source=github.com&utm_medium=referral&utm_content=iamdamion/my_modules&utm_campaign=Badge_Grade_Dashboard)
[![Build Status](https://travis-ci.org/iamdamion/my_modules.svg?branch=master)](https://travis-ci.org/iamdamion/my_modules)    

A collection of scripts that can be used as modules. Some useful, some completely aesthetic.

## Script List ##
1. custom_colors.py   

* Color palettes because I am sick of looking them up per project. Ripped off the R idea of a dictionary, but corrected the colors.   
* Each is a dictionary. Currently available: 'wes_a' & 'contrasty' (contrasty unfinished).   

* Usage:   
 ```
 import os,sys
 my_modules = os.path.expanduser(<path to where you are storing the modules here>)
 sys.path.append(my_modules)
 from custom_colors import wes_a

 # colors can now be called from the movie, or the set as a list, or individually
 # examples:
 wes_a['Rushmore'][0] # This will pull the first color in the rushmore palette
 wes_a['Rushmore'] # this will give you the list of colors in the rushmore palette
 ```

Available Colors:     
![](https://github.com/iamdamion/my_modules/blob/master/wes_color_palettes.jpg) 

2. natural_sort.py   
 - Sorts strings to human readable. Example: 10 will go after 9, not after 1.

 * Usage:
 ```
 import os,sys
 my_modules = os.path.expanduser(<path to where you are storing the modules here>)
 sys.path.append(my_modules)
 from natural_sort import natural_sort

 natural_sort(<your list of strings here>)

 # This will return a naturally sorted version of your list. 
 ```   
     

