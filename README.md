# keyboard-layout
## linux
```
cp nimaslayout >> ~/usr/share/X11/xkb/symbols/nima
```
Then you have to update the `sudo vim /usr/share/X11/xkb/rules/evdev.xml` with the following, add it near the other English keyboards.
```
<layout>
 <configItem>
   <name>nima</name>
   <shortDescription>en</shortDescription>
   <description>English (nima)</description>
   <languageList>
      <iso639Id>eng</iso639Id>
   </languageList>
 </configItem>
 <variantList/>
</layout>
```

## windows
download keyboard layout creator.

Load the source file.

then go to Project > build DLL and setup package


# layout
### Normal mode
![Normal](images/normal.png)

### Shift mode
![withShift](images/withShift.png)
