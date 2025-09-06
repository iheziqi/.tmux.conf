## 🚀 Installation

1. **Install tmux** (if not already installed):

   ```bash
   sudo apt update && sudo apt install tmux -y
   ```

2. **Clone TPM (Tmux Plugin Manager):**

   ```bash
   git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
   ```
   
3. **Clone This Repo:**
  
   ```bash
   git clone https://github.com/iheziqi/.tmux.conf
   ```

4. **Copy the `.tmux.conf` file** into your home directory:

   ```bash
   cp .tmux.conf/.tmux.conf ~/
   ```

5. **Start tmux**:

   ```bash
   tmux
   ```

6. **Install plugins** (inside tmux, press):

   ```
   prefix + I   (Ctrl + a, then Shift + i)
   ```

---

## ⚙️ Configuration

### Prefix Key

* Changed tmux prefix from `Ctrl+b` → `Ctrl+a`.

### Pane Management

* Vertical split: `prefix + |`
* Horizontal split: `prefix + -`
* Resize panes with Vim keys:

  * `prefix + h` → resize left
  * `prefix + l` → resize right
  * `prefix + k` → resize up
  * `prefix + j` → resize down
* Maximize/restore pane: `prefix + m`

### Reload Config

* Reload tmux config without restarting:

  ```
  prefix + r
  ```

### Mouse Support

* Mouse enabled: click to select panes, resize with drag, scroll.

### Copy Mode (Vi Style)

* Enter copy mode: `Ctrl + [`
* Start selection: `v`
* Yank (copy): `y`
