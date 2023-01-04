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

There was just nothing he could have done in this situation. I felt I had seen everything at SAP, and even though I would change departments, this would not satisfy my needs (may it be the subject and monetary). Don't get me wrong. **SAP is a superb employer** - otherwise, I would have never stayed for such a long time, but in terms of technology and scale, I was looking for something different.

Being involved and responsible for many SAP "Cloud" projects, I was always fascinated by the foundations SAP has built its software on top of the "hyperscalers." And that's what I was most interested in.

But curious by nature, I also wanted to avoid being locked in project development for years and stuck in a silo. That was what I loved in my job; we had to deal with multiple projects that needed help, and we always had to tackle different problems based on entirely different business and use cases. But there was also a personal lack of...

## ...trust in the future

With almost six months of distance, it is now easier to talk about the future of SAP. I do not have a crystal ball and do not want to predict what will happen, but I have one or two (or three) opinions. Don't get me wrong. **There are VERY talented people making decisions at SAP**, but with almost ten years involved in multiple cloud products, there are certain things that I see with a lot of criticism.   
  
And once again, it is MY opinion, and there might be a HELL of arguments that will say otherwise, but:

1. **SAP Neo should have never lost focus by SAP**

   Neo was and IS good. It has a lot of constraints, but it also hides complexity and scale behind hem. Yes. People are limited to Java and UI5, but the intention of Neo never was to allow the developer to build the next Netflix on this stack; it was instead acting as an extension of existing on-premise systems to create small transactional apps that will put apps in the cloud and replace existing ABAP apps to be used with modern browsers and mobile devices. And that was clear. The SDK was sufficient. The stack for building these apps might have been limited, but good enough to build your stuff fast and easily. But the best thing, IMHO, was the tight integration with services like database, user management, cloud connector, Fiori Launchpad, and the dispatcher supporting AuthN/Z.

   **"Gosh, but there was a complete vendor lock-in here!"**

   Guys, we are talking about an extension to a stack **THAT IS** a complete vendor lock-in by nature. People PAY for this vendor lock-in because they want clear direction, support, and reliability.

   There is a market and always will be to make it easy to develop small frontends with an optional semi-complex backend that will act as a proxy or an extension to an on-premise system. No-code/Low Code is NOT the answer to this.

   Google is doing a great job with App Engine, and then we also have Netlify; with that said, SAP Neo could have been the SAP option for customers to get the same seamless experience here.

   SAP Neo offered this experience with its integrated Launchpad service, a dispatcher taking care of AuthN/Z and connections, and a clear path for a developer to go. There is a reason why SE80 is still the way for many SAP developers because it is precisely this: One tool suite that supports the whole life cycle of the application someone is building. 

     
   Not less. Not more:

   > Hey, here is an SDK. We know it has flaws and gives you some constraints, but it works the way it is. And if there is a problem we will take care of it! 

   I LOVE that SAP is putting a lot of effort into open-source and empowering the community to participate. But open source should instead be part of the foundation of what users can see (despite open protocol standards). The ultimate goal is to get people onto the cloud and give them the feeling they are still moving in an SAP ecosystem (in a positive way) and NOT in a system branded as SAP with a lot of glue code between open source components.
2. **Hyperscaler and resilient integration services in favor of SAP BTP (supported by excellent SDKs)  
     
   **SAP BTP wants too much. While SAP Neo was made for a specific use case within its boundaries, SAP BTP seems to have lost focus. ****
3. **Reduction and complete shutdown of MANY other products**