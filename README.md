# iPhone Model Info

JSON File with all Apple iPhone Device Type and Color Codes

To add please use the following formats:

## Models Object

```{ 
    "<deviceType>" : "<Model Name>"
    }```

For example:
```{
    "iPhone12,3" : "iPhone 11 Pro"
    }```

## Color Object

```{
 "<deviceType>" : {
     "<color1Identifier>" : "Color 1",
     "<color2Identifier>" : "Color 2", 
     etc....
 }
}```

For example
``` {
    "iPhone12,3" : {
        "1" : "Space Grey", 
        "2" : "Silver",
        etc...
    }
}```

To find the deviceType and  color, run the following command from terminal. Note: You must have Apple Configurator 2 installed and install the command line tools

`cfgutil -f get cfgutil -f get color deviceType`

