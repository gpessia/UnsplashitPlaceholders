# Unsplash.it Placeholders

This package contains basic HTML placeholder from [unsplash.it](https://unsplash.it/) for Sublime Text 

### Installation 
- Open Prefences -> Browse Packages from the menu.
- Clone this repository or download and unpack the zip package to the 'Users' directory.


### Triggers

**``uns``** for ``<img src="https://unsplash.it${1:/g}/${2:200}/${3:300}">`` rendered as
```html
<img src="https://unsplash.it/g/200/300">
```

---
__``uns-r``__ for ``<img src="https://unsplash.it${1:/g}/${2:200}/${3:300}?random">`` rendered as
```html
<img src="https://unsplash.it/g/200/300?random">
```

---
__``uns-l``__ for ``<img src="https://unsplash.it${1:/g}/${2:200}/${3:300}/list">`` rendered as
```html
<img src="https://unsplash.it/g/200/300/list">
```

---
__``uns-i``__ for ``<img src="https://unsplash.it${1:/g}/${2:200}/${3:300}?image=${4:0}">`` rendered as
```html
<img src="https://unsplash.it/g/200/300?image=0">
```

---
__``uns-b``__ for ``<img src="https://unsplash.it${1:/g}/${2:200}/${3:300}?blur">`` rendered as
```html
<img src="https://unsplash.it/g/200/300?blur">
```

---
__``uns-g``__ for ``<img src="https://unsplash.it${1:/g}/${2:200}/${3:300}?gravity=${4:east|north|south|west|center}">`` rendered as
```html
<img src="https://unsplash.it/g/200/300?gravity=east">
```