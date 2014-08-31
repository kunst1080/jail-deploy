jail-deploy
===

jail-deploy is a wrapper script of qjail(8) for deployment of jail environments with user-flavor.

You can deploy jail environment with your flavor which is owned by normal user, and you can maintain flavors with VCS.

## Platform
FreeBSD 10.0

## Getting Started
1. Install qjail:

  ```bash
  pkg install qjail
  man qjail-intro
  man qjail
  man qjail-howto
  ```

2. Clone this scripts:

  ```bash
  git clone git://github.com/kunst1080/jail-deploy.git
  ```

3. Please read my Usage:

  ```bash
  $PATH_TO_THIS/jail-deploy
  ```

This script requires root control for qjail(8) and cp|mv|write for /usr/jails/.
Using this scripts, you have to use su or sudo.

## License
The MIT License

