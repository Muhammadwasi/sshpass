sshpass
=======

If you need to login to a server that, for whatever reason, has public key auth disabled, you can use this script
to automate login via username and password.

Your password will be stored in the appropriate keyring backend. (e.g. Keychain on Mac OS X)

Requirements: 

1. First, install Python2 by downloading from [here](https://www.python.org/downloads/).
2. Then, you need to install following modules either using `pip` or `easy_install`.
    * `pip install pexpect`
    * `pip install keyring`
    <br/>OR
    * `easy_install  pexpect`
    * `easy_install keyring`
