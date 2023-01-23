<div align = "center"><img src="https://cdn.discordapp.com/attachments/871054615737671730/873094665124065290/eternar_256.png"></div>


```assembly
section	.text
	global _start
_start:
	mov	edx, len
	mov	ecx, msg
	mov	ebx, 1
	mov	eax, 4
	int	0x80
	mov	eax, 1
	int	0x80

section	.data

msg	db	'Hi there 👋', 0xa
len	equ	$ - msg
```

![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=Demenytomi&show_icons=true&theme=radical)

![Profile views](https://gpvc.arturio.dev/Demenytomi)
