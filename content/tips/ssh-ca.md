+++
date = '2026-01-06T11:14:31-05:00'
draft = true
title = 'SSH CA - How to add?'
+++
Based on openssh environment

# 1. Copy an SSH CA certificate file

# 2. Edit `sshd_config` file
```
/etc/ssh/sshd_config
```

# 3. Add CA certificate location
```
TrustedUserCAKeys [PATH]
```

# 4. `systemctl restart`