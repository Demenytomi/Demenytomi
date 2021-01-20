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
### Languages
<a href = "https://github.com/"><img src = "https://upload.wikimedia.org/wikipedia/commons/1/18/ISO_C%2B%2B_Logo.svg" width = "30"> <img src = "https://upload.wikimedia.org/wikipedia/commons/7/7a/C_Sharp_logo.svg" width = "30"> <img src = "https://1.bp.blogspot.com/-fvbv9STbxrA/XS2C5q6q-gI/AAAAAAAAHtc/xcRKAakArcwKTo20DNuO05lq2L50nb7JACLcBGAs/s400/Pascal.jpg" width = "30">


![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=Demenytomi&show_icons=true&theme=radical)

![Profile views](https://gpvc.arturio.dev/Demenytomi)
