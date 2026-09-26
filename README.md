My strange localhost tutorial
made by atpied

Versions patched:
0.347
0.348

Tools needed:
x32dbg
HxD

only for localhost, very unsecure!!

do this for player:
1. search for trust check and double click on this one that just says "Trust Check Failed" (not "%s Trust Check Failed)
2. look up for the first instruction jne
3. jmp it
4. search for --rbxsig2, double click at the first result
5. look up for something like push ebp (this is lower ret 14 or idk)
6. change it to ret
7. search for Non-trusted Base  URL used. HttpRbxApiService is only for Roblox API calls and double click
8. look up and find instruction with jne
9. jmp it
10. done

do this for rcc:
1. do all fixes that you made for player
2. that's all for x32dbg, now open HxD
3. ctrl+f and paste 00 68 74 74 70 73 00
4. replace it with 00 68 74 74 70 00 00
5. done

congratz i hope i helped u
