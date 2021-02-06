# Supported Executors & Games

```
- Free Supported Executors -
[+] KRNL [90% Support *]
[+] Fluxus [50% Support]

- Paid Supported Executors -
[+] Synapse X [100% Support] - Recommended!
[+] Protosmasher [90-100% Support]
[+] Sirhurt/Asshurt [90-100% Support]
[+] Sentinel [50% Support]

[*] Script-Ware [Unknown Support (new exploit)]

*May encounter instability, but works.
```

## NEEDED FOR SCRIPT-WARE

```lua
local Environment = getgenv()

Environment.http_request = http.request
Environment.KRNL_LOADED = true
Environment.get_thread_context = getidentity 
Environment.set_thread_context = setidentity 

local check_caller = Environment.checkcaller 

Environment.checkcaller = function() 
    if game.PlaceId == 185655149 then 
        return true 
    end 

    return check_caller()
end
```

```
- Supported Games -
[+] Phantom Forces
[+] Lumber Tycoon 2
[+] Welcome To Bloxburg
[+] RoBeats
[+] Adopt Me
[+] Ragdoll engine
[+] Strucid
[+] Tower Of Hell
[+] Prison Life 2
[+] Bad Business
[+] Sound Space
[+] Many more coming soon!
```