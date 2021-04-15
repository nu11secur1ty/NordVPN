# NordVPN
- Running in background with user hit log in log 
```bash 
bash running_client_terminal_background.sh > nord.log 2>&1 &
```
-  Stop and kill the service
```bash
kill $(pgrep -f openvpn)
```
BR @nu11secur1ty
