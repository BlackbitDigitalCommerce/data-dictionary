Data Dictionary
======
Creates a diagram of the current datamodel inside Pimcore.

![Sceenshot](https://thumb.ibb.co/c2Vsvf/Screenshot-2018-10-17-at-23-46-00.png)

## Install

Install the bundle with composer:

```
COMPOSER_MEMORY_LIMIT=3G composer require youwe/data-dictionary
```

## Results

You can get the flow by going to the setting (gear icon) -> Show current dataflow. Then a new tab wil be opened with the flow.

Or you can get the flow directly going to the following url: 
[http://<localhost>/admin/data-dictionary/](http://<localhost>/admin/data-dictionary)

Remember to change the *localhost* to your own pimcore name.

You should see something like this:

![Example](https://image.ibb.co/dF71pU/image.png)


## Todo
- [ ]  Create a diagram with all the classes, attributes and relations;
    - [x] Classes;
    - [x] Attributes;
    - [x] Relations (basic);  
    - [ ]  Create specific elements for specific cases:
        - [x]  Object Bridge
        - [x]  Bricks
        - [ ]  Block;
        - [ ]  Field collection;
        - [ ]  Tables;
        - [ ]  Classificationstore
- [ ] Generate textual documentation;
    - [ ] Create links between the diagram and the documentation;
    
