---
layout: blog_post
title:  "AECTech Hackathon Takeaways"
date:   2023-11-04
---


I had a lot of fun this past weekend at the <a href="https://www.aectech.us/hackathon-archive">AEC Tech Hackathon</a> at NYC. I really appreciated the open format of the hackathon. The whole event started with an "open mic" - anyone could walk up to the microphone at the front of a large room and pitch an idea they wanted to work on in the next 24 hours. Teams would organically form around the big ideas that more people were interested in. At the end, the presentations showed a wide range of ways of using AI in AEC applications.

Yes hackathons are a great place to share solutions. But they seem like an even better place to share problems. So I came away from the event with a lot of takeaways regarding both the promises and challenges of AI in the architecture, engineering, and construction industry.


**Boring is the new sexy:** From the open mic, it was clear a lot of people just wanted an LLM or app to do something very time consuming and boring - rename all the rooms in a Revit model, review submittals, or help track progress on jobsite. The challenges didn't sound very "sexy" or "cool" but addressing them could have profound impact on people's productivity. To paraphrase Mostapha Roudsari, "Automating names of rooms is boring, but automating that inside Revit is exciting!"

**Generative AI renders all you need:** Generative image models like DALL-E and Midjourney were interpreted by media outlets as "creative AI" - something that could augment the creative process of artists, creators, and designers. Some architects I spoke to admitted they were more interested in giving those generative image models a screenshot of their grayscale concept 3D model to output realistic 3D renders. Effectively, they saw generative image AI as just a time-saving replacement for the 3D rendering engine they typically use to show realistic images to clients.

**Is AEC data AI-ready?:** Now that machine learning models have demonstrated capabilities on more general purposes (think YOLO for object recognition), now those in AEC tech want to re-purpose them for specific AEC needs. I met a software engineer in a window manufacturing company who wanted to use AI to help catalogue their shop drawings. I saw this as a matter of finding an image classification model like YOLO and fine tune it via transfer learning on labeled CAD drawings...and that would've taken more than 24 hours for sure. Those in Big Tech envision that other businesses can one day buy a general "off-the-shelf" AI model that can be fine tuned for specific industries. Until that day arrives, those in the AEC industry may still need to take a hard look at the data they have and decide whether it's "AI-ready." Taking the window manufacturing company's CAD drawings as an example: are the parts of the drawing clearly labeled/annotated? Will the AI misinterpret those labels? Are any of the parts mislabeled? AI developers will have to figure out how "off-the-shelf" AI model can catch human mistakes in the dataset, and AEC developers will have to figure out if their datasets are of sufficient quality.

**A Universal Assistant but for AEC:** A similar desire seemed to be expressed in a lot of projects that tried to control ChatGPT for automating BIM workflows. One project called itself Clippy and notably kept prompting ChatGPT until it's coding solution actually worked on Revit. So while AEC folks want an AI tailored specifically to the AEC industry, they also seem to want a general purpose AI to be a "really smart AEC intern" that helps out with anything they come across in their workday. So in line with that future vision of an AEC company purchasing AI off the shelf, AEC folks need a clear understanding of what they really need from that AI and clarify what efforts are needed to re-train and specialize that AI for AEC needs.

**AEC + XR = TBD:** There seemed to be only one VR project in the whole hackathon. I don't think this means VR is dead, but the AEC industry's enthusiasm for VR seems a bit dormant right now. My bold prediction remains that once <a href="https://arxiv.org/abs/2103.04918">Embodied AI</a> takes off, it'll be really fun to interact with AI in VR while designing built environments. Right now the AEC industry is still not sure how useful the Apple Vision Pro will be, even if AEC tech folks totally get the idea of spatial computing. Something to keep an eye out in future AEC hackathons!


PS

It also helped that I worked on a project, FURN-E, that won the **Best Open Source Hack** category of the hackathon!

As an architect explores design options with images from generative AI like DALL-E, FURN-E can detect furniture objects in those images and automatically suggest links to similar real-world products for procurement from manufacturers in subsequent construction phases of the project.

![FURN-E data pipeline](/assets/img/hackathon/data_pipeline.png)

Knowing this kind of tool can be repurposed in many other ways by designers looking to make generative AI images into a physical reality, we have made this project available on <a href="https://github.com/orgs/TeamZombies/repositories">Github</a>

