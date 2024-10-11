# IBM Servers: info, troubleshooting, errors etc

![image](https://github.com/user-attachments/assets/ea976104-a852-4bb5-8ba1-8a7b7178b9f3)


# Integrated Management Module (IMM)
- Default username/password: ```USERID``` / ```PASSW0RD```
- Default IP (if DHCP fails): 192.168.70.125

## IMM Troubleshooting
### "Logging In"
- Use an older browser, Eg Firefox v50, which can be installed and run side by side with newer Firefox: https://ftp.mozilla.org/pub/firefox/releases/50.0.1/win64/en-US/Firefox%20Setup%2050.0.1.exe
- Set IMM to use HTTPS

## "UEFI Platform Initialization"
- Use PSU#1 only (aka do not use PSU#2 by itself)
- https://support.lenovo.com/us/en/solutions/ht110912-system-hangs-at-startup-with-message-uefi-platform-initialization-ibm-system-x

## Booting from USB
- F12 is the boot menu key
- GParted boots OK from USB, but DBAN, Windows struggles
- Set boot in BIOS as Legacy Only
- Win7 needs RAID drivers

## Hypervisor USB port

## Fans
https://old.reddit.com/r/homelab/comments/aa3xj7/ibm_systemx_3650_m2_fan_speed_control/
