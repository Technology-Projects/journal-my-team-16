# Detecting Suspicious Activity

## Objective

Learn about **detective security controls**.

---

## Step 1 – View authentication logs

```bash
sudo cat /var/log/auth.log
```

## Step 2 – Search for login attempts
```bash
grep "Failed password" /var/log/auth.log
```

## Step 3 – View recent logins
```bash
last
```

## Questions
- What information appears in authentication logs?
- Why are logs important in cybersecurity?
- What might indicate suspicious activity?


## Deliverables
Include screenshots of:
- authentication logs
- failed login search results