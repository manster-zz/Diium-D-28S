## dtb file for Diium D-28S ArkOS (U8 version)

Credit goes to **mcasoo** from discord.

## Update (20.04.25
>  I managed to kill analog stick input, and updated the dtb for D28S. no need to set deadzone max any longer.
> * flash ArkOS for U8
> * overwrite dtb with this one
> * delete all *.bmp on sd root (especially battery related infographic)
> * boot

## Instructions
> * flash ARKOS FOR U8 (not K36) and replace dtb (d28s has a vertical lcd like U8)****
> * sound ok, ports keymapping is ok, esc key(FN key) can be assigned.****
> * OTG(wifi) doesn't work (OTG is not working on stock Emuelec as well. It has only one USB port named DC/OTG, I am sure it's fake)****
> * need to kill analog stick input on every apps. (retroarch-deadzone max, ppsspp-keymapping etc...) it has no rockers but I couldn't neutralize them on dtb.

ArkOS (use U8 version): https://github.com/AeolusUX/ArkOS-K36
