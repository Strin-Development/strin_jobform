# strin_jobform
FiveM ESX Job Form Script

#### Job Form for every FiveM RP server. Easy and simple to configurate!

### Requirements:

- es_extended
- esx_identity (jsfour-register works too as it is basically the same thing)
- esx_phone (gcphone works too as it is basically the same thing)
- discord webhook

### Configuration:

#### (Client) Form Config:

- police = Job (name) for the form
- pos = Position for 3d text to draw.
- label = Label for the form (3D text + NUI)
```lua
FORMS = {
    police = {
        pos = vector3(440.83834838867,-981.13397216797,30.689332962036),
        label = 'LSPD Form'
    },
    ambulance = {
        pos = vector3(298.89642333984,-584.50939941406,43.26086807251),
        label = 'EMS Form'
    }
}
```

#### (Server) Webhook Config:

- police = 'webhook url'
- ESX_VERSION = 1.1 -- change to 1.1 or 1.2
```lua
ESX_VERSION = 1.1
WEBHOOKS = {
    	police = '',
	ambulance = ''
}
```

### Features:
- Add as many forms as you want!
- Easy configuration.
- Nice UI.
- Discord Embed Messages

### Showcase: 
- Form UI

![Form UI](https://imgur.com/dbRgofc.png)

- Discord Message

![Embed Message](https://imgur.com/s43hql6.png)


**My development discord (Join for more releases and information)** https://discord.gg/SP6ypNmJcp

You can edit this script as much as you want. Don't re-publish or sell this script. Thank you.
