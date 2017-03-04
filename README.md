# Neil Wong

### Job Objective

`Job nature`: Full-time 

`Expect occupation`: Game design/development

`Except industry`: Computer software, online game

`Expected salary`: Negotiable

`Current status`: in-service now, but considering changing a new environment

### Self-Evaluation

My 7 years working experience include one year enterprise development experience and four year online game server side development experience, one year UnrealEngine4 development.
I was mainly responsible for core module development and server side lead programmer of online game project in my previous jobs. I am able to solve technology difficulties with my professional knowledge all by myself. I would very like to join a responsible and creative team. 

###### Personal skills
1, Strong developer skills in C++ and JAVA, can develop server-side core of underlying module with JAVA and C++ independently.

2, Know C#, JavaScript, HTML, and have developed projects with these languages in 2009, but now, not familiar with them .

3, Experience with high load server, I designed and developed a TCP server-side engine independently in 2013, PCU(peak concurrent users) reached 2000 with single cloud host in the open beta, and CPU usage is about 40%, PCU have reached 5000 on single server in the stress testing.

4, Strong developer skills in UnrealEngine4, can develop general 3D game independently, e.g. FPS, MOBA, RTS and so on. Familiar with Particle, Lighting, UI, Network and GamePlay of UE4, and know Material of UE4.

###### Blog
http://www.dawnarc.com/


### Working Experience
2016/12 until now

`Suzhou Snail Digital Technology Co., Ltd. | C++ Developer`

Industry category: Online game | Enterprise nature: Private | Scale: 2000+ | Monthly salary: Confidentiality

Job description: Developing a sandbox PC game with workmates with UnrealEngine4. This project is based on the source of ARK.


2015/08 -- 2016/10 (14 months)

`Indie Game Development by myself | Game Designer & Developer`

Industry category: Indie game

Job description: Developing a RTS online game with UnrealEngine4 independently. Responsible for all programming of client-side and server-side, and also made a particle like “Arcane Missiles”. Involved in designing gameplay and art.


2012/11 -- 2015/08 (2 years 10 months)

`Shanghai TheBingo Information Technology Co., LTD | CTO`

Industry category: Online game | Enterprise nature: Private | Scale: 20-99 | Monthly salary: Confidentiality

Job description: Responsible for the development of server side infrastructures, games core logic as well as client’s network of the whole company. Control and guide company’s technical direction, along with interns coaching and mentoring.


2010/12 -- 2012/11 (2 years)

`Shanghai Dream2 Network Technology Co., LTD | Server-side Lead programmer`

Industry category: Online game | Enterprise nature: Private | Scale: 100-499 | Monthly salary: Confidentiality

Job description: Mainly responsible for Pockie Ninja server side engine maintenance and extension as well as game logic development


2010/03 -- 2010/08 (6 months)

`VanceInfo (Nanjing) Software Technology Co., LTD | Research and Development Department | R&D Engineer`

Industry category: Computer software | Enterprise nature: Listed company | Scale: over 10000 | Monthly salary: Confidentiality

Job description: Participate in Vodafone telecom and Singapore telecom system development


### Resume

#### Training experience

##### `Institution	Training`: e-Learning of 3D Art	
`Time`: 2017.01 until now	

`Content`: Maya and ZBrush

##### `Institution	Training`: Shanghai Lingxun Education
`Time`: 2010/08 - 2010/12

`Content`: C++ (network, MFC)

##### `Institution	Training`: Aptech-Yichang authorized training center
`Time`: 2008/08 - 2010/02

`Content`: JavaEE and .NET enterprise development


#### Working experience
		
##### `Company`: Suzhou Snail Digital Technology Co., Ltd.
`Time`: 2016/12 - till now

`Project`: ARK online game

`Technology`: UnrealEngine4

##### `Company`: Indie game development by myself
`Time`: 2015/08 - 2016/10

`Project`: RTS online game

`Technology`: UnrealEngine4 + libuv + protobuf + boost

##### `Company`: Shanghai TheBingo Information Technology Co., LTD
`Time`: 2014/05 - 2015/08

`Project`: Spinal Breakers server side

`Technology`: JavaSE7.0 + libuv + protobuf + MySQL

##### `Company`: Shanghai TheBingo Information Technology Co., LTD
`Time`: 2012/11 - 2014/04

`Project`: Cute Warrior server side

`Technology`: JavaSE7.0 + libuv + protobuf + MySQL   
			
##### `Company`: Shanghai Dream2 Network Technology Co., LTD
`Time`: 2012/07 - 2012/11

`Project`: Warblade server

`Technology`: ACE+boost+protobuf+SqlLite+MySQL+Python

##### `Company`: Shanghai Dream2 Network Technology Co., LTD
`Time`: 2010/12 - 2012/06

`Project`: Pockie Ninja server

`Technology`: JavaSE6.0 + IOCP + MySQL

##### `Company`: VanceInfo (Nanjing) Software Technology Co., LTD
`Time`: 2010/03 - 2010/08

`Project`: eReader System

`Technology`: GXT2.0 + BME(Huawei) + Oracle11g


#### Project description (from present to past)

##### ARK online game
programming language are C++ and Blueprint.

This project is based on <ARK: Survival Evolved>, and we do some works for inculturation in China. The game engine is UnrealEngine4.

RTS online game

programming language is C++, consider the performance on mobile devices, didn’t use Blueprint.

I had researched Unity3D for 2 months in the beginning, but I found that the performance and Materials of Unity is not perfect, then I start to learn UnrealEngine4. Beside the development of programming, I also learned and made few Particles with UE4, most Particles were bought on Unreal Market. all programming of client-side and server-side were did independently.

The network module of server-side was programmed with libuv, and integrated it with UE4. The network module of client-side was programmed with FSocket of UE4 API. Logic messages were encoded and decoded with protobuf. Version control system was git, and server-side of git was Gitblit. Building tool was cmake.

The works with UE4 that I finished independently include: performance optimization of UE4, e.g. CPU, GPUand memory; the replication of data and communications of TCP network; Multi-thread and synchronization in UE4; Integration in UE4 with C++ frameworks: boost, RekNet, protobuf; development of UI, include UMG, Slate and Canvas; server-side development for MOBA game server which was integrated with UE4 GameThread; programming B star pathfinding algorithm, and combine it with NavMesh of UE4 to achieve special logic; post processing of scene, include: Environment Lighting, Height Fog and so on; Version-to-Version migration of Android, include: Integration of protobuf-lite and UE4 in NDK mode.


##### Spinal Breakers online game server side
Network module was programmed with C++, other modules were programmed with Java.

Spinal Breakers’s server side architecture is basically the same as Cute Warrior. But it optimizes server side development tools, and modifies the previous constructive mechanism. Specifically, the new project uses maven instead of ant in the previous projects. Integration environment uses Jenkins. As the project's client logic all adopts the lua script to develop, and google official does not provide protobuf’s lua version to support, so the client communication protocol uses a third party open source framework of protobuf: protoc-gen-lua. 


##### Cute Warrior online game server side
Network module was programmed with C++, other modules were programmed with Java.

The program architecture of this project is similar to that of Pockie Ninja server, which includes connection server, game logic server, public data server, central data server, DB server. It adopts distributed architecture.

The network communication layer uses node.js underlying library libuv, so that the server side would support cross-platform. During the development, when I committed a bug in github for libuv, it was closed for no reason. But there is a serious point to the problem. 

The logical layer uses Java, as well as script. Compile these “scripts” at project initiation time through own tool interface of jdk, then manual load class file to the virtual machine. In that case, original JavaScript is replaced to improve the script performance. The logic layer and communication layer use JNI interface. The game can also be divided into multiple scene and a process can support multiple scene. A scene with large load pressure can adopt distributed processing through a process divided into a scene.

In contrast with network module of Warblade online game server-side, all dynamic memory allocation are pooled: according to PCU limitation configuration, allocating a large memory on server startup, all these memory don't need to destroy after using. It trades memory for time, and decreased CPU usage obviously, this is the key factor to implement thousands PCU load.


##### Warblade online game server side
Programmed with C++ and python.

The project includes gateway server, game logic server, cache server and database server, and uses distributed architecture. The network layer uses ACE framework, cache uses sqllite, database uses mysql, communication protocol uses google’s protobuf, script uses python (achieve C++ interface interaction through the support provided by boost). 

Within the game, every scene is a single process. UDP communication protocol is adopted among these processes to enhance the efficiency of network communication. Data formats in the game uses coded format provided by protobuf. When parse role data, directly decode these protobuf binary data as protobuf custom objects. When store role data, write to the hard drive through sqllite first, then store in mysql database at regular time. I participated in the development of server side underlying architecture and part of the game logic, as well as a small amount of client logic such as mall system.


##### Pockie Ninja online game server
Network module was programmed with C++, other modules were programmed with Java.

Pockie Ninja project includes connection server, game logic server, public data server, data center server and DB server, and it adopts distributed architecture. Its game server, public data server and central data server can scale under load, break into several services or merger, and deploy each service into physical server separately. Server communication module adopts IOCP. Both middleware and game logic uses Java, and middleware can call communication module through JNI. Game script document adopts JavaScript, which is executed by JDK script engine. And database is all made of the blob data type to reduce the DB maintenance complexity.

I was mainly responsible for the game logic writing and engine maintenance extension in the project. I accomplished SNS system all logics and several large-scale versions such as “Tail beast siege” independently. I also completed related tools development including DB data reader; server merge tool; central data server writing and cross-server battlegrounds system; as well as overseas multinational version support and maintenance. 


##### eReader system (Vodafone Telecom baseline version and Singapore Telecom customized version)
Programmed with Java.

The project consists of eleven systems including [Manager (management platform)],[Portal (client interface)],[Server (data access platform)],[CMS (content management platform)],[SDP (billing system)],[Timer (timing processing system)]. There are more than 30 people who participate in development and more than 10 people testing in the core group.

I was mainly responsible for GXT framework secondary encapsulation, Portal system environment establishment, Manager platform products and content online and offline; Timer platform timing billing and loan notification; Portal users’ action tracking, favorites, order; and the whole project requirements analysis, design and coding supported by daylight saving time. 

‘Manager’ includes more than 10 modules such as content division management, content management, product management, billing policy management, system account management, readers account management, client software management; ‘Portalapp’ is mainly responsible for handheld devices required authentication, HTTP message validation and business logic; ‘Timer’ performing tasks regularly, such as timing billing and loan notification; Server is responsible for database access. HTTP+XML or SOAP is adopted in different platforms to implement distributed communication. 

The deployment environment of this project is SUSE10+Oracle11g, which adopts distributed architecture and uses Agile Development and Hudson Continuous Integration development mode. BME is the company’s internal framework that integrating front end UI, database access and transaction management.


