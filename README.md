# vasile2k.github.io
### JobolanLand
I love rats <3
############################ CROW
Jaja Xaxa

<table>
    <tr>
        <td>Foo</td>
        <td>Foo</td>
        <td>Foo</td>
    </tr>
    <tr>
        <td>Bar</td>
        <td>Foo</td>
        <td>Baz</td>
    </tr>
    <tr>
        <td>Foo</td>
        <td>Foo</td>
        <td>Foo</td>
    </tr>
</table>

###### The Uaie is incoming...

```nasm
db uaie "uaie"
db cal "cal"
; In case resgisters are altered by interrupt 13h
popa
pusha
stc                        ; Set carry... if BIOS doesn't
int 13h
jnc search_directory
call reset_disk
jnc read_root_directory
mov si, disk_error
jmp error
```

###### ...the Uaie is no longer incoming

Maybe, nope?
!!!!!!!!!!!!
