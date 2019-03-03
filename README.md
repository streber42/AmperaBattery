# AmperaBattery
Information on using the Chevy Volt / Opel Ampera Battery BMS
## Original Contributors:
Tom de Bree, Damian Maguire

### Further contributions by:
- Liam O'Brien
- swoozle (diyelectriccar.com)
- jontscott (diyelectriccar.com)

## Forum Threads
- https://www.diyelectriccar.com/forums/showthread.php/2012-chevy-volt-battery-93101p59.html
- https://www.diyelectriccar.com/forums/showthread.php/attempting-hack-chevy-volt-drivetrain-107946p6.html

## Communications with the BECM K16 (Battery Energy Control Module) 500kbps CAN bus
Connector X1 on the BECM K16 ()
- 1 - Black - Ground
- 2 - Red - 12V
- 3 - White/Black - CAN_Low
- 4 - Light Blue - CAN_High
- 9 - Black - Ground
- 14 - Brown/Red - 12V
- 15 - Orange/Yellow - 12V
- 16 - Light Green/Light Blue - 12V

## Communications with the module slave boards
## via the 125kbps Internal Network CAN bus

Connector X2 on the BECM K16
- 9 = 5V
- 10 = Ground
- 11 = CAN_Low
- 12 = CAN_High
