# Coding-Class

## Resources
- Khan Academy
  - [Intro to HTML/CSS: Making webpages](https://www.khanacademy.org/computing/computer-programming/html-css)
- Udacity
  - [School Of Programming](https://www.udacity.com/school-of-programming)
- Free Code Camp
  - [Full Curriculum](https://learn.freecodecamp.org/)


## Code Snippets
- Welcome To My World!
  - [Sante Fe College](https://www.sfcollege.edu/)
  - ```
    document.querySelector('#hero h1').innerHTML = "Welcome to <span>JESSE'S WORLD</span>"
    ```
- University Of Florida Takeover, Part 1
  - [University of Florida](http://www.ufl.edu/about/)
  - ```
    document.querySelector('.header .logo').style.backgroundColor = '#6f1f32'
    document.querySelector('.aux-menu-wrap').style.backgroundColor = '#dec997'
    document.querySelector('.main-menu-wrap').style.backgroundColor = '#6f1f32'
    document.querySelector('.btn-search').style.backgroundColor = '#6f1f32'
    document.querySelectorAll('.main-menu-wrap .main-menu-link').forEach((item) => {item.style.color='#dec997'})
    document.querySelector('.landing-page-hero-full h1').style.textShadow = "2px 3px 2px#6f1f32"
    document.querySelector('.landing-page-hero-full h1').innerText = "GO SEMINALS!"
    document.querySelector('.landing-page-hero-full h1').style.fontSize = '10rem'
    ```
- University Of Florida Takeover, Part 2
  - [University of Florida](http://www.ufl.edu/about/)
  - ```
    document.querySelector('.header .logo').style.backgroundColor = '#6f1f32'
    document.querySelector('.aux-menu-wrap').style.backgroundColor = '#dec997'
    document.querySelector('.main-menu-wrap').style.backgroundColor = '#6f1f32'
    document.querySelector('.btn-search').style.backgroundColor = '#6f1f32'
    document.querySelectorAll('.main-menu-wrap .main-menu-link').forEach((item) => {item.style.color='#dec997'})
    document.querySelector('.landing-page-hero-full h1').style.textShadow = "2px 3px 2px#6f1f32"
    document.querySelector('.landing-page-hero-full h1').style.fontSize = '5rem'
    document.querySelector('.landing-page-hero-full h1').innerHTML = '<marquee>GO SEMINALS! \
    &nbsp;&nbsp;&nbsp;&nbsp;GO SEMINALS!&nbsp;&nbsp;&nbsp;&nbsp;GO SEMINALS!&nbsp;&nbsp;&nbsp;&nbsp;GO SEMINALS! \
    &nbsp;&nbsp;&nbsp;&nbsp;GO SEMINALS!&nbsp;&nbsp;&nbsp;&nbsp;GO SEMINALS!&nbsp;&nbsp;&nbsp;GO SEMINALS! \
    &nbsp;&nbsp;&nbsp;GO SEMINALS!&nbsp;&nbsp;&nbsp;GO SEMINALS!</marquee>'
    ```

- You look like Kobe!
  - [Kobe's Wiki Page](https://en.wikipedia.org/wiki/Kobe_Bryant)
  - ```
    document.querySelector('a[href="/wiki/File:Kobe_Bryant_warming_up.jpg"] img').src = "https://avatars0.githubusercontent.com/u/37995847?s=400&u=9f638c17a677688d4d0efe36d149ec3dbed63e1c&v=4"
    document.querySelector('a[href="/wiki/File:Kobe_Bryant_warming_up.jpg"] img').style.height = 'auto'
    document.querySelector('a[href="/wiki/File:Kobe_Bryant_warming_up.jpg"] img').style.width = 'auto'
    ```
- Where did the picture come from?
  - [My Picture](https://avatars0.githubusercontent.com/u/37995847)
