# Layouts 

Please work on following layouts and decide the minimum CSS required to be implemented to achvieve the following layouts.

Please visit the site for reference: http://themes.bootstrapessentials.com/headers

### Default 
```
header>div.container>brand{Brand}+form>input[type="search"]^nav>button[toggle][xs]{&#9776;}+ul>li*4>a{Item $}^^^^^^main>h1{Hello World!}^footer
```

### Static
```
header>nav>button[toggle][xs]{&#9776;}+brand{Brand}+ul>li*4>a{Item $}^^form>input[type="search"]^^^main>h1{Hello World!}^footer

header>nav>div.container>button[toggle][xs]{&#9776;}+brand{Brand}+ul>li*4>a{Item $}^^form>input[type="search"]^^^^main>h1{Hello World!}^footer
```

### Fixed
```
header[fixed]>nav>button[toggle][xs]{&#9776;}+brand{Brand}+ul>li*4>a{Item $}^^form>input[type="search"]^^^main>h1{Hello World!}^footer

header[fixed]>nav>div.container>button[toggle][xs]{&#9776;}+brand{Brand}+ul>li*4>a{Item $}^^form>input[type="search"]^^^^main>h1{Hello World!}^footer
```

### Justified
```
header>center>brand{Brand}^nav[justified]>button[toggle][xs]{&#9776;}+ul>li*5>a{Item $}^^^^^main>h1{Hello World!}^footer
```

### 2 line Split
```
header>div.container>brand{Brand}+form>input[type="search"]^button{Cart}+nav>button[toggle][xs]{&#9776;}+ul>li*4>a{Item $}^^^^^^main>h1{Hello World!}^footer
```

### 2 line Joined
```
header>nav>div.container>button[toggle][xs]{&#9776;}+brand{Brand}+form>input[type="search"]^button{Cart}+ul>li*4>a{Item $}^^^^^^main>h1{Hello World!}^footer
```

### Navmenu Only
```
aside>brand{Brand}+form>input[type="search"]^nav>ul>li*4>a{Item $}^^^^main>h1{Hello World!}^footer
```

### Navbar with Navmenu
```
header[fixed]>nav[sidebar]>button[toggle][xs]{&#9776;}+brand{Brand}+form>input[type="search"]^ul>li*2>a{Icon $}^^^^aside[sm][md][lg]>nav>ul>li*4>a{Item $}^^^^main>h1{Hello World!}^footer
```

### Navbar with Hidden Navmenu
```
header[fixed]>nav[sidebar]>button[toggle]{&#9776;}+brand{Brand}+ul>li*4>a{Item $}^^form>input[type="search"]^ul>li*2>a{Icon $}^^^^aside[hidden]>nav>ul>li*4>a{Item $}^^^^main>h1{Hello World!}^footer
```

### Navmenu within Container
```
header>nav>button[toggle][xs]{&#9776;}+brand{Brand}+ul>li*4>a{Item $}^^form>input[type="search"]^ul>li*2>a{Icon $}^^^^main>aside>nav>ul>li*4>a{Item $}^^^^div.content^^footer
```

### Fulscreen menu toggler (Marketing Site)
```
header>button[toggle][xs]{&#9776;}+brand{Brand}^^^aside[hidden]>nav>ul>li*4>a{Item $}^^^^^^main>h1{Hello World!}^footer
```