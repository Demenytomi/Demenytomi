<div align = "center"><img src="https://cdn.discordapp.com/attachments/871054615737671730/994049548911648830/web.png?ex=66db0109&is=66d9af89&hm=982a82d2e2c9b60c8c7dc2373b6bf674414bcb387906c9d5560f29d3fc12b8af"></div>


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

<!--- ![Github Stats](https://github-readme-stats.vercel.app/api?username=Demenytomi&show_icons=true&theme=radical) --->
<!--- ![](http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Demenytomi&theme=2077) --->
![](http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Demenytomi&theme=2077)
![](http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Demenytomi&theme=2077)
![](http://github-profile-summary-cards.vercel.app/api/cards/stats?username=Demenytomi&theme=2077)
![](http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Demenytomi&theme=2077&utcOffset=8)

![](https://komarev.com/ghpvc/?username=Demenytomi)
