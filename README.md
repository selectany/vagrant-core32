# vagrant-core32 

Vagrant setup based on Core project from TinyLinux v5.0.1.
Built against Virtual Box Guest Addins v4.2.18.

Currently vagrant box is about 23Mb - really tiny and fast!

## Getting Started

- Install VirtualBox = v4.2.18([Download](https://www.virtualbox.org/wiki/Downloads))
- Install Vagrant >= v1.34 ([Download](http://downloads.vagrantup.com/))

## Usage

- Clone a copy of this repository to your local system or download it zipped.
- Navigate to main directory (where Vagrantfile resides) with your terminal and run `vagrant up`.

After all you should be able to visit [http://localhost:8888](http://localhost:8888)

## TODO:
- mysql is still not ported for TinyCore 5.0.1, so for now you have use sqlite3
- apache2-mod-php is installed, but php-cli is still not ported, also.

Enjoy!
