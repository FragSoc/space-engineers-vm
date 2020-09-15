![](https://www.spaceengineersgame.com/uploads/2/1/9/6/21961362/2183352_orig.jpg)

# Space Engineers Ded. Server VM

A vagrant/virtualbox VM to run space engineers.
Will only work on unix systems.

Put your starting save in the `saves` direcetory, then run `vagrant up` to download, setup and run the server.

## Requirements

- Ansible
- Vagrant
- VirtualBox

## Resources

- Opens port 27016 for the server
- Reserves 8GB of RAM
- Binds the saves directory to the `saves` folder in this repo
