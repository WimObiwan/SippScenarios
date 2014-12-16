## SIP Registration

### uas-REGISTER-auth.xml
Server side handling of REGISTER, with authentication.
Realm is `sip.obiwan.be`.
Any username/password will do.

Example:
```
sipp -sf uas-REGISTER-auth.xml -log_file sipp.log -trace_logs -p 9999 -i 192.168.1.132
```

### uac-INVITE
Client side call

Example:
```
sudo sipp -sf uac-INVITE.xml -log_file sipp.log -trace_logs -i 192.168.1.132 192.168.1.80 -s 0032123456789 -rp 10000 -r 1
```

### (default uas scenario)

Example:
```
sipp -sn uas -i 192.168.1.132 -p 9998
```
