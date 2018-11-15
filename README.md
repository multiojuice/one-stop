# one-stop
A place to see what personal projects I am working on, have worked on, and plan to work towards

This list was started in September of 2018.
## Index
[November 2018](#november-2018)
- [Personal Website](#personal-website)
- [C++ video games](#cpp-video-games)
- [solo](#solo)
- [random vine](#random-vine)

[October 2018](#october-2018)
- [VlocChain v2](#vlocchain-v2)
- [solved](#solved)
- [byebye](#byebye)

[September 2018](#september-2018)
- [LSMP](#lsmp)
- [nand2tetris](#nand2tetris)
- [web-mess](#web-mess)
  
## November 2018
### Personal website
#### Status: [in progress]
#### Summary
I have started programming, designing, and writing content for my personal website. I am actually super stoked about this. I am not too good at designing things, but I am excited about writing all the content for it. The website is going to hold all of my projects, experience, and thoughts in the forms of writings! It is in progress but I hope it turns out well!
#### Technologies
- Javascript
- React
- Styled Components

The repository is located [here](https://github.com/multiojuice/personal-website)

### CPP video games
#### Status: [in progress]
#### Summary
A series of video game tutorial implementations that all focus around learning C++. I knew a bit about C++ before this, I used it once or twice and I also read a ton of the documentation on a bus ride, but this was my first long experience. In the process, I also learned a bit about [SFML](sfml-dev.org). The games are decently fun and pretty simple, but they will be playable soon!
#### Technologies
- C++
- SFML

The repository is located [here](https://github.com/multiojuice/cpp-game-tutorials)

### Solo
#### Status: [back burning]
#### Summary
This was my first attempt at using GraphQL on the backend side. This is to be a service that the user hits with a query and it will fetch data from all different media sources, in what seems to be one swoop for the user. Services I had in mind were Spotify, Vimeo, Soundcloud, DailyMotion, Youtube and others among them. The finshed state of this project would serve useful to my other project [LSMP](#lsmp). I have only used Go-lang a few times, but it ended up confusing me a bit when I got into the go + graphql, so I may end up using C++ for this instead.
#### Technologies
- Go
- GraphQL

The repository are for the service is located [here](https://github.com/multiojuice/) and the client is [here](https://github.com/multiojuice/solo-client)


### random vine
#### Status: [completed]
#### Summary
random vine is a command line tool/application that will output the text and description of a random vine from the social media platform vine. It is setup like the unix tool `fortune`, so the vines must be manually put into the app. So let's see some PRs!
#### Technologies
- C

The repository is located [here](https://github.com/multiojuice/random-vine)
 
## October 2018
### VlocChain v2
#### Status: [in progress]
#### Summary
A video streaming service that utilizes an open and decentralized network with blockchain like ideas, to store and serve the videos. The network is powered by computers that run our `holder` software, this software uses websockets to stream and take in data. The front-end is a multi-page react web app. Lastly, the backend, which keeps track of where each video is held, acts as a router between the web app and the holders, and keeps track of other things like users and views. These three components together make for a unique and completely usable video streaming system.
#### Technologies
- Javascript
- React
- Node.js
- Websockets
- Rest
- DASH like video streaming
- FFMPEG
- Express.js

The repositories are located [here](https://github.com/VlocC)

### Solved

### byebye
#### Status: [complete]
#### Summary
A command line tool that will kill or end any list of processes that the user puts in the .byebyerc file. I was getting tired of having to end Visual Studio Code, multiple tmux sessions, Chrome, my terminal instance, spotify, etc, at the end of my development session. This is easily configurable and works on multiple systems. Also, I used this project as an introduction to golang!
#### Technologies
- Golang

The repository is located [here](https://github.com/multiojuice/byebye)

## September 2018
### LSMP
#### Status: [finishing touches]
#### Summar
A React application, that runs at lsmp-lsmp.a.csh.rit.edu. This is an app that displays multiple media search results based on one search. All services are playable from this same webpage. Some of these services include, Spotify, Soundcloud, Vimeo, Youtube, and several others.
#### Technologies
- Javascript
- React
- Hosted on an OpenShift
- Powered by tons of public RESTful APIs :)

The repository is located [here](https://github.com/multiojuice/lsmp)

### nand2tetris
#### Status: [back burning]
#### Summary
A long term project that I am activly working on every so often. The project is based off of (nand2tetris.org)[nand2tetris.org]. The basic idea of the project is to build a PC with a working OS, the catch is that you start with only nand gates. The first few modules in the project tackle the hardware part, so creating several different gates out of just the nand gate, then we create an ALU, RAM, and a CPU (this is all done in hardware descirption language and in simulators). The second half of the project is the programming part. Using ASM, you create an OS and your own compiled language to write a version of tetris on your computer, in your OS, in your own language. This project is focused around self-learning and nothing but the resources to learn is given to you throughout the project. Currently, I am in the later stages of the hardware half of this project.
#### Technologies
- Hardware desciription language
- Hardware simulators
- Assembly
- Virtual machine simulators
- And I guess Nand gates?

The repository is located [here](https://github.com/multiojuice/nand2tetris)


### web-mess
#### Status: [complete]
#### Summary
A quick weekend project that utilizes web-sockets and just plain old javascript event handlers to create a free for all, real time, jet fighting game. The game is honestly quite fun (especially if you're on the east coast where the server lives) and simple. The development taught me much more about plain javascript and how these beefy and popular frameworks do the magic that they do.
#### Technologies
- Javascript
- Socket.io

The repository is located [here](https://github.com/multiojuice/web-mess)
