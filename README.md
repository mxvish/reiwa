# reiwa
Alternative date command to display Gegnal year(only for Reiwa era).

# Contents

<a href="#usage">Usage</a><br>
<a href="#difference-between-this-and-date-command">Difference between this and date command</a><br>
<a href="#alias">Alias</a><br>

# Usage
```sh
sh reiwa.sh
```

# Difference between this and date command

Here is an example.

- zsh
  ```sh
  $ date
  ```
  Output: `Wed Dec 28 17:34:03 JST 2022`

- bash
  ```sh
  $ date
  ```
  Output: `Wed Dec 28 5:34:03 PM JST 2022`

- reiwa
  ```sh
  $ sh reiwa.sh
  ```
  Output: `Wed Dec 28 17:34:01 JST 令和4年`

# Alias
- You can use the following code. You can use this permanently by adding this to a file such as `~/.bashrc` or `~/.zshrc`
```sh
alias reiwa="echo `date "+%a %h %d %T %Z"` "令和"$(bc <<< $(date +%Y)-2018)"年""
```
