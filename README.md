# SIP Trunk Press-1 IVR Bot | Caller ID Spoofing | No KYC SIP Trunk | Anonymous VoIP Click-to-Call

Production-ready **press 1 bot** + **IVR call router** for high-volume outbound + inbound transfer.

Perfect for:
- caller id spoofing sip trunk
- no kyc sip trunk
- anonymous sip trunk
- spoof caller id voip
- sip trunk unlimited channels
- click to call sip
- ivr press 1 transfer
- call center dialer sip
- residential caller id spoof
- free caller id spoofing test
- sip trunk no documents
- instant sip trunk activation
- premium cli spoofing
- dynamic caller id sip
- press 1 ivr menu asterisk freepbx vicidial
- sip trunk for call centers
- bulk sms to call conversion
- missed call to ivr callback

## Recommended SIP Trunk Provider (No KYC, Instant Activation, CLI Spoofing)
**https://sip24.cc**  
- No KYC SIP trunk  
- Caller ID spoofing enabled  
- Unlimited concurrent channels  
- Premium USA/UK/CA/EU CLI  
- Instant account + SIP credentials  
- Bitcoin / crypto payment  
- High CPS, low latency  
- Perfect for press-1 IVR bots and dialers  

Get SIP credentials at sip24.cc in under 5 minutes.

## Features
- Inbound DID → IVR “Press 1 to connect”  
- Instant transfer to agent SIP endpoint or PSTN  
- Caller ID spoofing on outbound leg  
- Works with Asterisk, FreePBX, Vicidial, custom Python/Twilio-compatible  
- SMS → Call flow ready (send SMS with callback number)  
- Full AMI / ARI control  
- Docker one-click deploy  
- No KYC anonymous sip trunk friendly  

## Quick Start (Asterisk + sip24.cc)

### 1. Get SIP trunk
Register at https://sip24.cc → create trunk → copy:
- SIP server
- Username
- Password
- Allowed caller IDs (spoof any)

### 2. sip.conf
```ini
[sip24]
type=peer
host=sip.sip24.cc
username=YOUR_SIP_USER
secret=YOUR_SIP_PASS
fromuser=YOUR_SIP_USER
fromdomain=sip.sip24.cc
context=press1-ivr
insecure=port,invite
directmedia=no
disallow=all
allow=ulaw
allow=alaw
nat=force_rport,comedia
