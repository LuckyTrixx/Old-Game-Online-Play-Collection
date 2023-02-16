# Dungeon Siege

- Method of Play: LAN-Mode over Public-IP
- Needs port forwarding
- Steam/GOG Version does need "zonematch=true" command line argument.
  - Steam:
    - Rightclick on Dungeon Siege in your Library
    - hover over "Manag"
    - click "properties"
    - under "General" find "Launch Options"
    - enter "zonematch=true"
    - close
  - GOG: TBD

## Port forwarding

6073 - UDP

2300 - 2400 UDP

		  - For Fritzbox users: Set "Port an Gerät" to 2300 - 2400 and "Port Extern gewünscht" to 2300.

## Connecting

![Important](../../res/important.png)

When Starting the game for the first time, upon entering or hosting a Multiplayer match, a Firewall message will pop up, if the Game can access the firewall.
Tab out of the Game (Alt + Tab) and give the Permission. If the Game crashes when Tabbing back in, just start it again, your firewall-Choice is saved and you won't be asked again.

### Host

LAN-Play: Host server normally  Give your friends your public ipv4 IP. To find it, go to https://www.whatismyip.com/

##  Connect

Connect via LAN play over direct-IP. get the Host's public IP.

