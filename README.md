# Tinyinfo-Website
This Repository contains the Homepage for Tinyinfo

Feel free to host your own instance.

## How to host the Website?
Apache:
1. Make sure you have git installed (Try ```$ git --version```)
2. Go into the ```/var/www/html``` folder
3. Clone the Repository with ```$ sudo git clone https://github.com/Lion-Craft/Tinyinfo-Website.git```
4. Create a folder named "```Tinyinfo```" in the html folder (```/var/www/html/Tinyinfo```)
5. Copy all files in the cloned folder (```Tinyinfo-Website```) into the "```Tinyinfo```" folder with ```$ sudo cp var/www/html/Tinyinfo-Website/* var/www/html/Tinyinfo/```

To update the Website run the following commands in the cloned folder (should be ```/var/www/html/Tinyinfo-Website):

```
$ sudo chmod +x update.sh
$ sudo ./update.sh
```
