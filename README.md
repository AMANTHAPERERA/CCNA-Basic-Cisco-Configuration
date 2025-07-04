# **CCNA-Basic-Cisco-Configuration**
<br>

## In this task , I'm configuring basic Cisco configuration using  Cisco routers.(In this practical I'm using Cisco 1841 Routers)

### As the first step open the packet tracer and drag  2x Cisco 1841 routers to the screen and label them with your preference  (For now I'm labeling with **COLOMBO** and **KANDY**)

![Labling Routers](/images/lable.png)

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
<br>

## MOTD Banner
### MOTD (message of the day) banner is a message that used as a welcome message or used to aware someone about important things. 
### Imagine  in network admin hopes to resign and he want to aware the future network admin about configuration details (Branches ) 
### or any important messages (Authorization -who can access or who cannot) of ongoing routers. 

![banner](images/banner1.png)

### Any of them ( I'm applying it on Colombo router )

<br>
    
    COLOMBO>enable
    COLOMBO#
    COLOMBO#configure terminal
    COLOMBO(config)#
    COLOMBO(config)#banner motd #WELCOME TO COLOMBO#
    COLOMBO(config)#

<br>

### Try with yourself

<br>

    enable
    configure terminal
    banner motd #WELCOME TO COLOMBO#

<br>

# 2. Adjusting Date & Time
### Eventhough date and time configuration ia an optional task  , that helps us in many occasions such as troubleshooting network device synchronizing accurate logging and much more.

### Any of them (I'm applying it on Colombo router)

    COLOMBO#clock set ?
     hh:mm:ss  Current Time
    COLOMBO#clock set 10:42:00 4 jul 2025


### Try it yourself & Check

    COLOMBO#clock set hh:mm:ss Day Month Year
    COLOMBO#show clock
    


   


