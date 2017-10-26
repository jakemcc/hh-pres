
class: center, middle

# Better history in your shell

---

class: center, middle

# My Ideal

---

class: middle

# Browse local history with ⬆️ ⬇️

---

class: middle

# Browse local history with ⬆️ ⬇️
# Search global history

---

# hstr

![History Suggest Box](hh-animated-01.gif)

---

# .bashrc

```bash
# Whenever a command is executed, write it to a global history
PROMPT_COMMAND="history -a ~/.bash_history.global; $PROMPT_COMMAND"
```

```bash
# On C-r set HISTFILE and run hh
bind -x '"\C-r": "HISTFILE=~/.bash_history.global hh"'
```


---

class: middle

# Blog post: bit.ly/better-history
# hstr: github.com/dvorka/hstr
# Me: @jakemcc, jakemccrary.com


