to enter a Cisco switch recovery system is different froma  routers recovery system called rommon so on the switch hold the mode button at the front of the switch while booting you want to be sure you are consoled into the device using these configs [[Consoling]] you will boot into a system with a switch: option now you want to run these commands. ```
flash_init

```arduino
del flash:config.text
```


```css
del flash:vlan.dat
```




```
boot
```

