# esx_boatshop
Boat Shop based on ESX

I did NOT create the Code. I only edited the esx_vehicleshop code to create this new shop. This code unlike most other versions out there do NOT interfere with the Original esx_vehicleshop.

This Boat Shop works just like esx_vehicleshop. However tho instead of Players buying Cars they can Buy/Sell Boats. I created this because i couldn't find a Boat Shop Script & instead of waiting for others i went ahead & did it myself. 

The personal boat menu can be opened with /pb (like the vehicle shop /pv command).

# Requirement:

* Auto mode (everyone can buy vehicles from the dealer)
  * No need to download another resource

* Player management (the car dealer job): billing, boss actions and more!
  * [esx_society](https://github.com/ESX-Org/esx_society)
  * [esx_billing](https://github.com/ESX-Org/esx_billing)
  * [esx_addonaccount](https://github.com/ESX-Org/esx_addonaccount)
  * [esx_addoninventory](https://github.com/ESX-Org/esx_addoninventory)
  * [cron](https://github.com/ESX-Org/cron)
  
* Boat Garage
  * [esx_eden_boatgarage](https://github.com/HumanTree92/esx_eden_boatgarage)

# Download & Installation

1) CD in your resources/[esx] folder
2) Clone the repository
3) Import `esx_boatshop.sql` in your database
4) Add this in your `server.cfg`:

```
start esx_boatshop
```
5) If you want player management you have to set `Config.EnablePlayerManagement` to `true` in `config.lua`


# Credits/Original Code
* [ESX-Org](https://github.com/ESX-Org)
  * [esx_vehicleshop](https://github.com/ESX-Org/esx_vehicleshop)

# Other
If you like this please check out some of my other stuff like
* [esx_aircraftshop](https://github.com/HumanTree92/esx_aircraftshop)
* [esx_boatshop](https://github.com/HumanTree92/esx_boatshop)
* [esx_eden_aircraftgarage](https://github.com/HumanTree92/esx_eden_aircraftgarage)
* [esx_eden_boatgarage](https://github.com/HumanTree92/esx_eden_boatgarage)
* [esx_eden_garage](https://github.com/HumanTree92/esx_eden_garage)
* [esx_panicbutton](https://github.com/HumanTree92/esx_panicbutton)
* [FiveM_CustomMapAddons](https://github.com/HumanTree92/FiveM_CustomMapAddons)
