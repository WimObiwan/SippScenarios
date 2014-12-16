## SIP Registration

### uas-REGISTER-auth.xml
Server side handling of REGISTER, with authentication.
Realm is `sip.obiwan.be`.
Any username/password will do.

Example:
```
sipp -sf uas-REGISTER-auth.xml -log_file sipp.log -trace_logs -p 9999 -i 192.168.1.132
```
