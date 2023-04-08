A fork of onlyfans-scraper 
It has been optimized to make it more feature complete with dc's onlyfans script
A matter of fact with the right settings transitioning between the two scripts should be a easy enough process

In addition there are numerous filtering features to control exactly which type of content you want to scrape.
Though it is not complete check out the changes.md file for some general changes that have been made

<h3>DISCLAIMERS:</h3>
<ol>
    <li>
        This tool is not affiliated, associated, or partnered with OnlyFans in any way. We are not authorized, endorsed, or sponsored by OnlyFans. All OnlyFans trademarks remain the property of Fenix International Limited.
    </li>
    <li>
        This is a theoritical program only and is for educational purposes. If you choose to use it then it may or may not work. You solely accept full responsability and indemnify the creator, hostors, contributors and all other involved persons from any any all responsability.
    </li>


  ## Description:
  command-line program to download media, and to process other batch operations such as liking and unliking posts.
    

![CopyQ nsUBdI](https://user-images.githubusercontent.com/67020411/227816586-fb685959-cd3f-45af-adea-14773b7154f9.png)



## Installation

### Recommended python3.9 or python3.10


# Windows: 
```
pip install ofscraper
```
or 

```
pip install git+https://github.com/excludedBittern8/ofscraper.git 
```

#  macOS/Linux
```
pip3 install ofscraper
```
or
```
pip3 install git+https://github.com/excludedBittern8/ofscraper.git 
```

## Authentication

You'll need to retrive your auth information 
    
https://github.com/excludedBittern8/ofscraper/wiki/Auth



# Usage

Whenever you want to run the program, all you need to do is type `ofscraper` in your terminal:

Basic usage is just to run the command below

```
ofscraper
```

![image](https://user-images.githubusercontent.com/67020411/230732583-dd064665-a59e-4714-92e7-393893061ac0.png)
  
 Select "Download content from a user" is all your need to get started with downloading content
    
  
 See: https://github.com/excludedBittern8/ofscraper/wiki/Menu-Options 
 
 For more information about the other menu option

 ## Advanced Usage
    
 For those who are comfortable ofscraper has numerous commandline options.
 A matter of fact in many cases you can skip the the menu prompts, and have the script run by itself
 
  https://github.com/excludedBittern8/ofscraper/wiki/command-line-args
    
  
# Issues
Open a issue in this repo, or you can mention your issue in the discord

https://discord.gg/zRXgb5Nv
    
## Common
### Status Down
      
This typically means that your auth information is not correct, or onlyfans signed you out.
### 404 Issue 
    
This could mean that the content you are trying to scrape is no longer present. It can also indicate that model has deleted her account, and it is no longer accesible on the platform
    
 ### Request taking a long time
   If a request fails ofscraper will pause and try again a few times. This can lead to certain runs taking longer and points.

 ## Known Limitations
 - 1000 likes is the max per day
    
    

# Migrating from DC script

You will need to change the settings so that the metadata option is compatible with your current folders
Additionally you might want to set the save_path, dir_path, and filename so they output similar outputs

The metadata path from dc's script is used for duplicate check so as long as your set the right path.
Files won't download a second time

https://github.com/excludedBittern8/ofscraper/wiki/Migrating-from-DC-script
https://github.com/excludedBittern8/ofscraper/wiki/Config-Options
https://github.com/excludedBittern8/ofscraper/wiki/Customizing-save-path

Ask in the discord or open an issue if you need help with what to change to accomplish this



# Discord

https://discord.gg/zRXgb5Nv
    
    

  
    









