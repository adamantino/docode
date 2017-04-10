DoCode
============

A tool that automatically generates media files, such as videos, GIFs, and screenshots, from your JavaScript sketch file.

![IMG](add img here)

## Demo
You can check at more examples here https://mgs.github.io/docode/

---

## Requirements

• Node 6.9.4 or Higher -- https://nodejs.org/  
• ImageMagick --  https://www.imagemagick.org/script/download.php  
or
```

$ brew install imagemagick

```
---

## Intallation
Run the following commnand:

```

$ npm install docode -g

```


## Check that doCode was installed correctly:

```

$ docode

```

You might want to look into `config.json` to make change the port you want to use and set up a SSL certificate.

---

## Operations

**• Screenshot:**  -s or --screenshots  
**• Gif:**   -g or --gif  
**• Video:**    -v or --video (currently on development)    
**• Preview:**  -p or --preview (currently on development)  
**• Help:** -h or --help (currently on development)  

---

## Usage:
While in the project main folder, run the following command:

```

$ docode operation


```

A new folder with the screenshots/video/gif will be created at the same location.

---

## To generate for a project on another folder, run the following command

```

$ docode --screenshots + [path_to_project_main_folder]

```

---

## Uninstall

```

$ sudo npm uninstall -g docode

```

---


## License
>You can check out the full license [here](https://github.com/IgorAntun/node-chat/blob/master/LICENSE)

This project is licensed under the terms of the **MIT** license.
