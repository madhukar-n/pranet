# Dependencies

## For Debian based linux distro (Ubuntu)
```sudo apt install hugo node golang```
## For MacOS
```brew install hugo node golang```

## Desc. about each sub-directory

- ```/assets``` : contains /images and /css
- ```/archetypes``` : contains markdown files to describe the skeleton of the content of each type
- ```/content``` : contains the raw website information in md files which Hugo places into relevant HTML files.
- ```/data``` : contains toml files.Each file act as a list that can be iterated
- ```/layouts``` : layouts contain the base html and go templates that use the ```/content```, ```/data``` to generate html pages
- ```/public ``` : this subdirectory is generated in when ```hugo server``` is run.

## To add a new lab member(ref. existing ones)

- Create a directory on his/her name inside ```/content/people```
- Create a new file ```index.md``` in the directory and structure the information as per ```people.md``` in /archetypes
- Copy the image into the directory and rename it to ```[name].jpg```

### Note:
Delete the ```/public``` and run hugo server to generate new ```/public``` directory 





