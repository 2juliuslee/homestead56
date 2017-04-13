# Laravel Homestead PHP5 / PHP56

### Homestead With PHP 5.6
This will create a virtualbox with name "homestead-56". You may change the virtualbox name in "scripts/homestead.rb".

```## Configure A Few VirtualBox Settings
    config.vm.provider "virtualbox" do |vb|
      vb.name = settings["name"] ||= "homestead-56"
```


### Installation
```git clone https://github.com/2juliuslee/homestead56.git```

```cd ~/homestead56```

```vagrant up```