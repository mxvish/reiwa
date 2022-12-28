# reiwa
Alternative date command to display Gegnal year(only for Reiwa era).

# Contents

<a href="#usage">Usage</a><br>
<a href="#difference-between-this-and-date-command">Difference between this and date command</a><br>

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
