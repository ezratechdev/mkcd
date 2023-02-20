
# mkcd

A simple command to make a directory and cd into the same directory



Using your favourite editor edit the .bashrc file. You can do so by using nano as shown below

```bat
nano ~/.bashrc
```

Go to the section where you add aliases and functions / commands and add the code below

```bat
# User specific aliases and functions
mkcd(){
   mkdir "$1" && cd "$1"

}
```

## Usage

Source the bashrc file
```console
source ~/.bashrc
```

You can now head to your terminal and use the command as shown below

``` console
mkcd test
```
