# Modified version from SonixFlasherC

## Update on README
- This repo was fork from https://github.com/SonixQMK/SonixFlasherC for our project.

## Changed :
- Switch OEM device to Sonix Boot Loader then update firmware from bootloader  


### Add Command
- `--xvidpid -x`     Set VID for device to receive reboot 

### Add Option  
- `--reboot -r`      Request bootloader reboot in OEM firmware (options: sonix, evision, hfd, chicony) 
   
### Usage Examples

- **Flash firmware to device VID/PID 04F2/25A0 with ROM bootloader VID/PID 0x0c45/0x7040:**
  ```
    sonixflasher --xvidpid 04f2/25a0 --reboot chicony --vidpid 0c45/7040  --file fw.bin

  ```

## License
Follow README.md