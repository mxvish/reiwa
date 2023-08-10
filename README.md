# reiwa
Alternative date command to display [Regnal year](https://en.wikipedia.org/wiki/Regnal_year)(only for Reiwa era).

# Contents

- [Usage without installation](#usage-without-installation)
- [Installation](#installation)
- [Usage](#usage)
- [Difference between this and date command](#difference-between-this-and-date-command)

# Usage without installation
```sh
curl -s https://raw.githubusercontent.com/mxvish/reiwa/main/reiwa.sh | sh
```

# Installation
- Using wget
```sh
wget https://raw.githubusercontent.com/mxvish/reiwa/main/reiwa.sh
```

- Using git    
```sh
git clone https://github.com/mxvish/reiwa.git
mv reiwa/reiwa.sh .
```

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
