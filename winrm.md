# winrm

## metasploit
- `auxiliary/scanner/winrm/winrm_auth_methods`. **discovery module** that determines
  - whether or not WinRM is listening
  - what authentication methods are supported
    - **basic.** disabled by default
    - **negotiate.** default for non-domains; uses NTLM for workgroups, Kerberos for domains
    - **kerberos.** default for domains
  - [source code](https://github.com/rapid7/metasploit-framework/blob/master//modules/auxiliary/scanner/winrm/winrm_auth_methods.rb)
- `auxiliary/scanner/winrm/winrm_cmd`. instantiate a shell; has a limited time to live
- `exploit/windows/winrm/winrm_script_exec`. more automated method for obtaining a shell

## crackmapexec

## references
- [Abusing WinRM with Metasploit](https://blog.rapid7.com/2012/11/08/abusing-windows-remote-management-winrm-with-metasploit/)
- [Microsoft Negotiate Protocol](https://docs.microsoft.com/en-us/windows/win32/secauthn/microsoft-negotiate)
- [MSDN: Windows Remote Management](https://docs.microsoft.com/en-us/windows/win32/winrm/portal)
