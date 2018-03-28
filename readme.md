### tada68 keyboard layout

### Changes from the default

##### layer 0
- make the `caps` key send `esc` when tapped and activate `layer 1` when hold
- put the `tilda` key instead of `esc`
- put the `delete` key instead of `tilda`
- add `play/pause` media key instead of `right control`

##### layer 1
- add vim-like arrow keys to `jkl;`
- add volume controls to `asd`
- add win lock to `Super` key

### Layout preview
![test](https://i.imgur.com/34TSAAq.png)

### Using it
Since this is in a separate repo for now you have to clone it to
`qmk_firmware/keyboards/tada68/keymaps/<name>`

Then run the below command to generate the `FLASH.bin` file
`$ make tada68:<name>:flashbin`

Of course replacing `<name>` with the name you wish to use for the keymap
