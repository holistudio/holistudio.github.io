---
layout: post
title:  "Project Spaceship"
date:   2024-05-05 18:47:00
preview: /assets/img/preview_spaceship.png
---

![SPACESHIP!](/assets/img/preview_spaceship.png)

### What are we trying to do?

Imagine you start stacking a few Lego blocks and then an robotic arm* starts stacking blocks alongside you. Ideally, the robot's AI can intuitively pick up on what you are trying to build and suggest blocks towards your goal. Or even better, the AI's blocks inspire you to take your build into a different direction you never imagined beforehand!

What would it take to get such a human-AI co-creation system to work?
- How would we train the AI to to build different shapes, block-by-block step-by-step?
- How would we train the AI to recognize what shapes are being built, given only a few of blocks placed in front of it?

And on the other hand, how would it feel for human beings to interact with such an AI? 
- Could we build with the AI without any verbal communication or text prompts? 
- Would we really appreciate the blocks placed by the AI or get annoyed?
- Could we get inspired into new directions for making something, or just converge with the AI on a single shape?
- (Or will we let the AI take over since it seems so much more intelligent than us?)


### What is new about our approach?

Large language models, like ChatGPT, point to new ways of verbally communicating with AI. Generative AI, like Midjourney, point to new ways for designers to iterate and curate design options with text prompts.

But designers operate beyond the space of natural language. Design can be a language all on its own.

Current research on embodied AI focuses on related issues. How can AI develop a higher level reasoning and learn through multi-modal interactions with the world?

An embodied AI that can understand designers' implicit intents and directly manipulate design models' components may present a new kind of user experience with its own benefits and challenges. But we won't know what those benefits and challenges are until we really get there...


### If we succeed, what difference do we think it will make?

For now, I'll start by training an AI to build and identify shapes on [ShapeNet](https://huggingface.co/datasets/ShapeNet/ShapeNetCore). Then I'll make a Unity3D game where the user stacks blocks to make a common 3D shape and the AI can then stack a few more blocks. Hopefully the AI can correctly identify the shape being built and assists the user in completing that shape. This project will serve as a "toy data experiment" for an embodied AI co-creating with a human-in-the-loop.

But the same approach can one day lead to various AI co-creation applications for designers of all sorts: architects during concept design, industrial designers developing manufacturing sequences...or a kid just making their own spaceship!

![spaceship-guy](/assets/img/spaceship/lego_guy.gif)


### Excited?

This project is currently in progress on my [GitHub](https://github.com/holistudio/project-spaceship).

The dev log for this project can be found [here](https://github.com/holistudio/project-spaceship/blob/main/UPDATES.md).

Feel free to reach out and shoot me an email at daniel.bin.lu [at] gmail [dot] com.

### Footnotes

*This can happen in either the real-world with a robot arm stacking blocks OR a virtual/extended reality environment with 3D model blocks appearing wherever you/AI wants. For now, getting something working in a 3D game environment (i.e., Unity 3D desktop) is a good place to start.
