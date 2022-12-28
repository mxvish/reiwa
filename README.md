# reiwa
Date command to display Gegnal year(only for Reiwa era).


# Usage
```sh
sh reiwa.sh
```

# Difference between date command

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

# Need alias?
- Use this.
```sh
alias reiwa="echo `date "+%a %h %d %T %Z"` "令和"$(bc <<< $(date +%Y)-2018)"年""
```
