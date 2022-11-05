+++
date = 2022-11-04T23:00:00Z
draft = true
title = "Why I left SAP after so many years"
[comments]
host = "mastodon.retr0.party"
id = 23213123123123123
username = "jeff"

+++
![](/uploads/hand-853188_1280.png "Good bye")

> Are you really sure? Can I do anything to change your mind? 

That was one of the sentences my manager asked me as I told him I would resign from SAP after more than 15 years to leave for another employer. And to be honest, there was no chance to change my mind because I had already struggled a long time before about the next steps in my career and life. 

There was just nothing he could have done in this situation. I felt I had seen everything at SAP, and even though I would change departments, this would not satisfy my needs (may it be the subject and monetary). Don't get me wrong. **SAP is an awesome employer** - otherwise, I would have never stayed for such a long time, but in terms of technology and scale, I was looking for something different. 

Being involved and responsible for many SAP "Cloud" projects, I was always fascinated by the foundations SAP has built its software on top of the "hyperscalers". And that's what I was most interested in. 

But curious by nature, I also wanted to avoid being locked in project development for years and stuck in a silo. That was what I loved in my job we had to deal with multiple projects that needed help, and we always had to tackle different problems based on completely different business and use cases. But there was also a personal lack of...

## ...trust in the future

With 3 months of distance, it is now easier to talk about the future of SAP. I do not have a crystal ball and do not want to predict what will happen, but I have one or two (or three) opinions. Don't get me wrong. **There are VERY talented people making decisions at SAP**, but with almost 10 years involved in multiple cloud products, there are certain things that I see with a lot of criticism. And once again, it is MY opinion, and there might be a HELL of arguments that will say otherwise, but:

1. **Neo should have never been deprecated.**  
     
   Neo was good. It had a lot of constraints, but it was also hiding complexity and scale behind them. Yes. People were limited to Java and UI5, but the intention of Neo never was to allow the developer to build the next Netflix on this stack; it was rather acting as an extension of existing on-premise systems to create small transactional apps that will put apps in the cloud and replace existing ABAP apps to be used with modern browsers and mobile devices. And that was clear. The SDK was sufficient. The stack for building these apps might have been limited, but good enough to build your stuff fast and easily. But the best thing IMHO was the tight integration with services like database, user management, cloud connector, Fiori Launchpad, and the dispatcher supporting AuthN/Z.   
     
   "Gosh, but there was a complete vendor lock-in here!"  
     
   Guys, we are talking about an extension to a stack THAT is a complete vendor lock-in by nature. People PAY for this vendor lock-in because they want clear direction and support. 
2. **Hyperscaler and resilient integration services in favor of SAP BTP (supported by awesome SDKs)**
3. **Reduction and complete shutdown of MANY other products**