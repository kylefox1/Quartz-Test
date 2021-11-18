---
title: "ass'n stuff"
---


# Thoughts on models to follow

I think I have finally reached some insight on where to go now with the project since the PoC. 

To go over the big vision again or *defining the impact*, the goal is to:

-  **get people to realize the value of their data and exercise sovereignty over it and their vehicle/devices (a la right to repair movement) in a way that can also be sustainable (environmental- and health-wise)**

So, putting this in *theory of change (ToC) language*, this could be:

```markdown
Through publishing open source hardware and software for data manipulation of converted e-bikes, Bikestream will lead to cyclists (and people in general) to realize the value of their data and the benefits of modifying their vehicles and hardware at will. 
```

The models I have been looking at include: 

1. Pave Motors
2. Pony 
3. The Mobility Factory 
4. [CoopCycle](https://coopcycle.org/en/)
5. [Training plans](https://datadrivenathlete.com/cycling-workout-guide/)
6. [Lets do this](https://www.letsdothis.com/gb/road-cycling-events) (events)
7. [ADS-B Exchange ](https://www.adsbexchange.com/)
8. [Cycling Analytics](https://www.cyclinganalytics.com/)

I have been trying to crunch the model that I think will be the most approrpaite to achieve the goal above and provide sustinability to the Association, and I think that I have finally figured (or at least I hope so [😮‍💨](https://emojipedia.org/face-exhaling/)). 

I think the model that can work is a combination of CoopCycle and ADS-B Exchange, plus providing cycling analytics to people who want it.

Going with this model, I expect that revenue-generating activities can include:

1. Purchasing a preassembled BikePi (Raspberry Pi with the software and any additional hardware (e.g., sensors) for data manipulation and streaming via Streamr)
2. Providing cycling analytics through web or mobile app (or Jupyter notebooks) as a service
3. Taking a fee from sales of data from the Data Union `and renting of computing power?`
4. Training on developing databikes 
5. Purchasing parts for databike model standards (e.g., the Databike Zeta 001 (DBZ-001) standard)
6. Communications about alternative mobility through thought spaces
7. Freemium access to a database `I want to try making one with Datasette` of archived data
8. Minting NFTs certifying that the databike meets one of our databike model standards and can therefore join the Data Union `this one may be too hard to do?` 

`But before trying the above, it is best to do some fundraising 🙏`

The CoopCycle model comes in because we will provide the hardware and software to connect to the Data Union, but then leave it to individuals or organizations to decide what services or products to provide based on the Bikestream outputs.  This can allow for *federating* Bikestream and building a global coalition of data-driven cyclists. I think this also helps get around the *cost of fleet* problem as well.

Thus, people can provide any cycling-related service (e.g., bikesharing) local to their area (and we will also help out). Additionally, in this model, Bikestream acts as the data hub upon which other apps can be built on top of, such as [Training plans](https://datadrivenathlete.com/cycling-workout-guide/), bikesharing, social networks like [Strava](https://www.strava.com/), games like [Zwift](https://www.zwift.com/), or [Events](https://www.letsdothis.com/gb/road-cycling-events). 

This will provide a *global design* that can be *locally implemented*. 

I think then the mobile or web app for Bikestream should just be for cycling analytics then. Based on [Cycling Analytics](https://www.cyclinganalytics.com/), most of the parts needed are things that can be added to a converted e-bike (the DBZ-001 has all of these parts except for the power meter) or found on a pre-assembled e-bike. I am undusre if I can make something this good anytime soon, but I can definitely start working on building my cycling analytics skills (or just use their API to start, 🤣).  

Based on [Pave Motors](https://www.pavemotors.com/platform), we can subscribe to the data from the Data Union and then provide analytics through the mobile or web app to users of Bikestream. I am also thinking of giving users the option of also storing their data on their own cloud or local storage, but I am unsure how hard this is to do. 

So on the crowdfunding side of things, I think it is best to pursue:

1. BikePi: a Raspberry Pi developed to be secured to a bike's frame and connect to Streamr, `can also be a more powerful single board computer (SBC)`
2. Cycling Analytics mobile/web app: an app to conduct analytics on cycling data, *and possibly* 
3. Databike Design: a bike CAD design that comports with the databike standard that is low cost to build (will probably just be a frame or just parts to add a BikePi to a frame)


# Random Idea

## Real-world Zwift

- using Bikestream, make a real-world Zwift where people across the world race on routes with similar road surfaces and geographies

```markdown

# Unorganized Thoughts
`Organized thoughts are up above`
Model to follow for Bikestream is federation like CoopCycle plus ADS-B Exchange (and add bike data to a Datasette) and cycling analytics (look at providers and copy the metrics they put out). Membership cost pays for BikePi and a conversion kit (maybe only for user/developer members). Make revenue from selling data and BikePi, and minting NFTs of bikes, and training/setup, and newsletter? 

  

Still need a mobile app (maybe just for cycling analytics; look at other mobile cycling analytics apps) 

  

Can crowdfund for the mobile app

  

People can still develop other apps with our database on Datasette though (they should develop training plans and events and plug it into our app)

  

Mention selling data as part of Ass'n in Bikestream docs. And need to have converted bike reviewed before adding to to data union

Have Bikestream be a nonprofit coop subsidiary? or become its own coop that becomes a member of the association under user/developer class, similar to CoopCycle (Ass'n keeps all infrastructure, and to access it people need to become members?)

Build mobile app MVPs with Adalo?

Look at [https://gomat.co/acerca-de-mat.html](https://gomat.co/acerca-de-mat.html)

**
```

# 2021-11-17 Update

Also looking at [Polypoly Cooperative](https://polypoly.coop/en-de/cooperative) as a potential model. Specifically, I was looking at [Polypoly Enterprise](https://polypoly.com/en-gb/technology).

> develops decentralised EDGE computing solutions.

![](Pasted%20image%2020211117163606.png)

I think this is also possible for us too if we develop BikePis with more powerful single board computers (SBCs) that can run AI/ML programs such as a [Jetson Nano](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/jetson-nano/). 

So this means the product model before is still pretty good. 

![](Pasted%20image%2020211117162255.png) 

or [image](https://polypoly.org/static/7dec194205858870897921a1baa2da59/b6761d9e-0e21-4c03-b6e2-9a30bbf3d6a6_F_Coop-Enterprise-interplay.svg)

I also like this graphic as well. And this made me think of the fact that we are also providing computing power with our BikePi that can be used for [edge computing](https://www.ibm.com/cloud/what-is-edge-computing) solutions.  This is also better for the [environment](https://thenextweb.com/news/data-centers-generate-the-same-amount-of-carbon-emissions-as-global-airlines) because the data does not need to be stored at a data center for computations (the data can be stored on the BikePi, but it may be best to avoid because of the limited data storage size on single board computers (SBCs). Alternatively, this can be done (and is already avoided) with Streamr, and we can get a mobile connection via Helium.). 

This can also be something that can be developed by third parties as well. 

