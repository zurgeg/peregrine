# The Boot Process

When you push the power button, the Wii immediately launches boot0 on the Starlet core. Boot0 doesn't do much but make sure that Boot1 hasn't been modified, and then loads it. (Note: If the hash is zeroed out, this check is skipped). Then, boot1 is loaded. Boot1 initializes the DDR3 RAM in the Wii, checks boot2 and loads it up.&#x20;

TODO: FINISH

