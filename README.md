# **CCNA-Basic-Cisco-Configuration**
<br>

## In this task , I'm configuring basic Cisco configuration using  Cisco routers. (In this practical I'm using Cisco 1841 Routers)

### As the first step open the packet tracer and drag  2x Cisco 1841 routers to the screen and label them with your preference  (For now I'm labeling with **COLOMBO** and **KANDY**)
<br>

![Labling Routers](/images/labled.png)

<br>

## Now I'm gonna split this task into below sections<br>

1. **Initial configuration { host name , MOTD banner (optional) }**
2. **Adjusting date and time**
3. **Assigning IP addresses with a description**
4. **Configuring  Passwords / Breaking Passwords / Recovering Passwords**

<br>

# 1. Initial Configuration
 <br>

 ### Guess what?  Imagine we have a brand new / reset router to configure , then we have to do some essential configuration for over convenience .
 ### It's more important to configure ***host name*** for our convenience. Imagine we have to work with more than 2 routers , We are confusing ourselves when we  need to identify them each.
 ### As I mentioned we have already labeled our routers as “COLOMBO” and  “KANDY” respectively. 
 ### For host name configuration , I'm using following configuration commands on both routers.

<br>

### COLOMBO Labled Router                                                                                                                            

 	Router>
    Router>enable
    Router#
    Router#configure Terminal
        Enter configuration commands, one per line.  End with CNTL/Z. 
    Router(config)#
    Router(config)#
    Router(config)#hostname COLOMBO
    COLOMBO(config)#


### Try it yourself
    
    enable
    configure terminal
    hostname COLOMBO

### KANDY Labled Router                                                                                                                            

 	Router>
    Router>enable
    Router#
    Router#configure Terminal
        Enter configuration commands, one per line.  End with CNTL/Z. 
    Router(config)#
    Router(config)#
    Router(config)#hostname KANDY
    KANDY(config)#


### Try it yourself
    
    enable
    configure terminal
    hostname KANDY



   


