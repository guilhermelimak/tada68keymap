## Custom qmk_firmware tada68 layout
Just some keymap changes over the default tada68 layout using [qmk_firmware](https://github.com/qmk/qmk_firmware/)

### Changes from the default

##### layer 0
- Make the `caps` key send `esc` when tapped and activate `layer 1` when hold
- Put the `tilda` key instead of `esc`
- Put the `delete` key instead of `tilda`
- Add `play/pause` media key instead of `right control`

##### layer 1
- Add vim-like arrow keys to `jkl;`
- Add volume controls to `asd`
- Add win lock to `Super` key

### Layout preview
Layout preview for layers 0 and 1
![Layers 0 and 1](https://i.imgur.com/34TSAAq.png)
(the json used to generate this preview is on the `KLE` folder on this repo)

### Using it
Since this is in a separate repo for now you have to clone it to
`qmk_firmware/keyboards/tada68/keymaps/<name>`

Then run the below command to generate the `FLASH.bin` file
`$ make tada68:<name>:flashbin`

Of course replacing `<name>` with the name you wish to use for the keymap
