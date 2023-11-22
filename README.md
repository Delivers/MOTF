# MOTF
Museum of the Future Dubai



# Install Remoter


- Make sure the user logged-in on the target PC is "Administrator" and has a username/pwd which you're setting in the Remoter
- Enable access to the Admin shares. Via regedit, set:

1. Click Start, click Run, type regedit, and then press ENTER.
2. Locate and then click the following registry subkey:
3. HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System
4. If the LocalAccountTokenFilterPolicy registry entry doesn't exist, follow these steps:
5. On the Edit menu, point to New, and then select DWORD Value.
6. Type LocalAccountTokenFilterPolicy, and then press ENTER.
7. Right-click LocalAccountTokenFilterPolicy, and then select Modify.
8. In the Value data box, type 1, and then select OK.
9. Exit Registry Editor.
10. Requires a restart to take effect!


- Turn on File and Printer Sharing
- Check if Remote Procedure Call (RPC) is running (Services App).
- If executing commands remotely works, but is very slow (it should be instant!), try with all firewalls disabled

