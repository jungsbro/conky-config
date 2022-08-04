# **conky-config**
<br>

# **FolderTree**
```bash
# ==============================================================================
.conky/                         #
    conky.desktop               # for autostart
    conky.sh                    # /usr/bin/conky.sh
    copyconky.sh                # shellscript for copying
# ------------------------------------------------------------------------------
.git/                           #
# ==============================================================================
.conkyrc                        # conkyrc for debian
# ------------------------------------------------------------------------------
.conkyrc_ct7                    # conkyrc for CentOS7
# ------------------------------------------------------------------------------
README.md                       #
# ==============================================================================
```
---
<br><br>


# **Installation**
1. Install conky
```bash
sudo apt install -y conky;
```
<br>

2. Clone conky-config
```bash
git clone https://github.com/jungsbro/conky-config.git ~/github/conky-config;
cp -f ~/github/conky-config/.conkyrc ~;
sudo cp -f ~/github/conky-config/.conky/conky.desktop /etc/xdg/autostart/;
sudo cp -f ~/github/conky-config/.conky/conky.sh /usr/bin/;
```
<br>

3. Execute conky
```bash
conky &
```
<br>

---
<br><br>