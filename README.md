# EDRs

This repo contains information about EDRs that can be useful during red team exercise.


# patch_syscall_dynamically.c

This proof-of-concept is resolving the syscall ID dynamically no need to check the version running on the remote host. To get the information on disk (not tampered) a call to `CreateFileMapping` and `MapViewOfFile` Windows APIs is performed. The DLL is then parsed to retrived the data and used to patch the live code.

# EDRs Hooked APIs

Want to contribute simply run `hook_finder64.exe C:\windows\system32\ntdll.dll` and submit the output.

### CrowdStrike hooked ntdll.dll APIs

[CrowdStrike hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/crowdstrike.txt)

### SentinelOne hooked ntdll.dll APIs

[SentinelOne hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/sentinelone.txt)

### Cylance hooked ntdll.dll APIs (Thanks to Seemant Bisht)

[Cylance hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/cylance.txt)

### Sophos hooked ntdll.dll APIs

[Sophos hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/sophos.txt)

### Attivo Deception hooked ntdll.dll APIs

[Attivo hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/attivo.txt)

### CarbonBlack hooked ntdll.dll APIs (Thanks to Hackndo)

[CarbonBlack hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/carbonblack.txt)

### Symantec hooked ntdll.dll APIs (Thanks to CarsonSallis)

[Symantec hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/symantec.txt)

### DeepInstinct hooked ntdll.dll APIs (Thanks to P0chAcc0)

[DeepInstinct hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/deepinstinct.txt)

### Morphises hooked ntdll.dll APIs

[Morphisec hooks list](https://raw.githubusercontent.com/Mr-Un1k0d3r/EDRs/main/morphisec.txt)


## Credit

Mr.Un1k0d3r RingZer0 Team
