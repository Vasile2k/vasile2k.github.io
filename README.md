# vasile2k.github.io
### JobolanLand
I love rats <3

<table>
    <tr>
        <td>Foo</td>
        <td>Foo</td>
        <td>Foo</td>
    </tr>
    <tr>
        <td>Foo</td>
        <td>Foo</td>
        <td>Foo</td>
    </tr>
    <tr>
        <td>Foo</td>
        <td>Foo</td>
        <td>Foo</td>
    </tr>
</table>

'''nasm
        ; In case resgisters are altered by interrupt 13h
	popa
	pusha

	stc                        ; Set carry... if BIOS doesn't
	int 13h

	jnc search_directory
	call reset_disk
	jnc read_root_directory

	mov si, disk_error
	jmp error '''

Maybe, nope?
!!!!!!!!!!!!
