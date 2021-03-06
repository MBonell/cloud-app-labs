# StackEntrance Application Laboratory

Welcome to the OpenStack Cloud App Lounge!  Below you will find the second app lab challenge.  Each lab is a playful way to see if you have what it takes to be a ['Cloud Application Engineer'](/cloud-application-engineer.md) - the future of apps. 

Before you being, don't forget to [setup your laptop with the OpenStack powered cloud of your choice](/prereq). 

![your own personal keys to datacentres around the world!](https://pbs.twimg.com/media/ClAqiubUoAAEK4p.jpg)

# Context for completing the lab:
 1. Because of EU Safe Harbour laws the cloud application you have just built requires that it be run from two different European countries.  Fortunately, OpenStack has numerous OpenStack powered clouds in Europe which you can choose from to run your cloud app.  
 2. By building your cloud app on multiple clouds you are helping assure your app is not locked to a single cloud operating (infrastructure) system.  
 3. Get accounts on two (or more) OpenStack-powered clouds and place your details in a set of instructions which will automatically give you a programmatic entrance to each cloud, i.e. create a clouds.yaml file for use by the os-cloud-config.py (see 'ingredients' below), and ask for help.
 4. Demonstrate you can get access to both clouds via the same cloud configuration instructions

# Lab learning objectives _(by completing this lab you will know how to...)_
 - [x] ...find the API endpoints for each OpenStack cloud so you can control the datacentre via command line (instead of clicking buttons on a dashboard).
 - [x] ...maintain login credentials for multiple clouds worldwide via a single secure file (clouds.yaml)
 - [x] ...connect to 2+ or more OpenStack powered clouds so you can build applications at the datacentre of your choosing.
 
# Win StackerPoints for completing this lab:
  - Show that you have connected to two different datacenters by tweeting two public (IPs) HTTP URLs which can be pinged by one of our [Cloud App Lab Pros](https://docs.google.com/presentation/d/1RBtAOjxmUh97fXrJlowvqVNmq2-8FxvBIHx2Dts1Jh8/pub?start=true&loop=false&delayms=2000).  Use the hashtag [#CloudApp](https://twitter.com/hashtag/cloudapp) to get the attention of a pro.
  - Ask for one of the Cloud App Lab Pros to verify that these two URLs are publically pingable by giving your tweet a "❤".  You will get +5 StackerPoints for each different datacentre/cloud to which you connect.
  - Once you have solved your lab and had it +1'd then head to the _cloud app lab_ lounge to show your evidence to receive your Stacker points.
  - Once you have collected enough lab points, you can [turn them into Stacker swag!](/StackerPoints)

# Ingredients you'll need to complete the lab:
  - [ ] You'll need [accounts on each cloud you are going to use](/prereq.md).  Hint: if the cloud you are using is a native OpenStack cloud then you should be able to find the endpoints via the dashboard: Compute > Access & Security > API Access.  [Discover OpenStack-powered clouds you can control worldwide](https://www.openstack.org/marketplace/public-clouds/).
  - [ ] Find the API endpoints for the clouds you want to work with via (http://docs.openstack.org/developer/os-client-config/vendor-support.html).  Hint:  `cloud_config = os_client_config.OpenStackConfig().get_all_clouds()`
  - [ ] [Install the os-cloud-config library so your laptop can talk to any OpenStack cloud in the world](http://docs.openstack.org/developer/os-cloud-config/installation.html).  Hint: save your cloud credentials in a clouds.yaml file for ease of use.
  
# Lab pros who can help you complete the lab 

Open Source is about knowing *who* as much as it is about knowing *what*.
Stuck on this lab, need some help to solve?  [Ping one of our Cloud App Lab Pros on Twitter/IRC](https://docs.google.com/presentation/d/1RBtAOjxmUh97fXrJlowvqVNmq2-8FxvBIHx2Dts1Jh8/pub?start=true&loop=false&delayms=2000)

Recommended cloud app pros who can help (click the link to send them a tweet):

 - ["Hi @PilgrimStack, could I get some help with using the @OVH datacentre with my clouds.yaml file?"](http://ctt.ec/Y3eka)
 - ["Hi @PetterLundKNA how do I get access to @CityCloud datacentre, could I get some help with this clouds.yaml file in the #CloudApp lounge?"](http://ctt.ec/dUw0B)
 - ["Hi @Code_Sean wondering if you could provide me help with getting access to the @DataCentred cloud for the #OpenStack #CloudApp lab?"](http://ctt.ec/gZa51)
 - ["I can haz help @BrunouyVanMorel in using the @Internap datacentre via my clouds.yaml file?"](http://ctt.ec/JDpBP)
 - ["If I wanted to get access to mulitple Mirantis engineered clouds @IgorMarnat, how might I do so with clouds.yaml?"](http://ctt.ec/l2kHJ)

# Solving the lab
Having trouble?  Sit back and watch someone else solve the lab challenge ;-)

[![Watch how to connect to an OpenStack-powered cloud with OS-Cloud-Config.py library and a clouds.yaml file with your authentication details](http://img.youtube.com/vi/7s7LKdih2vA/0.jpg)](http://www.youtube.com/watch?v=7s7LKdih2vA)


