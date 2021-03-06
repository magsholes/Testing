---
layout: post
title:  "Photoshop Workflow Tips"
date:   2020-08-20 04:34:42 -0600
featured-image: PS-tips-thumbnail.jpg
featured-image-alt: The Simplest Ways to Speed Up Your Photoshop Workflow
categories: [journal]
tags: 
---

Here are a few of my favorite shortcuts, secrets, and tips that I frequently use to speed up my workflow.

### Quick Brush Resizing

Most people know the shortcut for increasing or decreasing your brush size without having to manually fiddle with the brush settings—right square bracket `]` to increase and left square bracket `[` to decrease. That's great, but there's a better way that gives you even more control. 

With the brush tool selected (or eraser tool, or clone stamp tool, or any other tool with an adjustable diameter and hardness) hold down `Control`, hold down `Option`, and click and hold. You'll see a red shape that represents your brush.

While still holding down your mouse, drag the cursor left to shrink the diameter and right to increase it. Moving your cursor up or down will adjust the hardness.

<img class="single no-border" src="../../../../assets/images/PS-tips-brush-resize.gif" alt="Resize Brush" />

---

### Mask Tight Corners with Brush Tool

For a lot of people, the pen tool is the go-to for cutting out an image from its background, but I personally prefer using the brush tool for masking when possible. It feels more natural to me, and I find it especially useful for soft edges. But once you run into a tight corner to cut out, the brush tool can be a little awkward to use. Here's an example of a corner that would be easy for the pen tool to handle but maybe not so much the brush tool:

<img class="no-border" src="../../../../assets/images/PS-tips/corner-mask-1.jpg" alt="Use Brush to Mask Tight Corners" />

No matter how tiny you shrink the brush, it's impossible to get in those corners without it looking weird. The trick to making it work is stupidly simple: basically, over-mask, then go back and paint the subject back in. To make it easier to see where to mask the subject back in, use the Properties panel to decrease the mask's density, then bring it back to 100% when you're done. Here's an example of how I over-masked and lowered the density to see where to mask it back in. 

<img class="no-border" src="../../../../assets/images/PS-tips/corner-mask-2.jpg" alt="Use Brush to Mask Tight Corners" />

Final Product:

<img class="no-border" src="../../../../assets/images/PS-tips/corner-mask-3.jpg" alt="Use Brush to Mask Tight Corners" />

Another option that I've been using more and more is to mask the opposite of how you normally would—mask out the subject instead of the background. Then, with the mask selected, press `Cmd + i` to invert the mask and reveal the subject.

---

### Realistically Mask Fur/Hair

This trick is really similar to the first one in that you over-mask and then paint something back in, but it gets a little more involved by using a custom brush to "paint" the hair or fur back in. Here's an example where I've masked an image but we need more realistic fur.

<img class="no-border" src="../../../../assets/images/PS-tips/mask-fur-1.gif" alt="Masking Fur" />

First, <a href="../../../../assets/images/PS-tips/fur.abr">download this brush preset</a> I've created and install it. This is what we'll use to simulate the furry edges we masked out. Then, using this  brush, paint the hair back in until it looks natural. Adjust the diameter and angle as needed, and just play around with it until you get an effect that works for your image. Here's where I ended up:

<img class="no-border" src="../../../../assets/images/PS-tips/mask-fur-2.jpg" alt="Masking Fur" />


---

<!-- ### 4. Custom Shortcuts

With any fresh install of Photoshop, the first thing I do is set up custom shortcuts that significantly speed up my workflow. You can create these shortcuts by going to `Edit > Keyboard Shortcuts` These are of course custom but here are the ones that I use daily:

- Flatten Image
<br />`Cmd + Shift + F` 
<br />*(overrides default preset)*
- Trim
<br />`Cmd + Shift + 0`


You can also save a set of custom shortcuts to import later.
-  -->

### Custom Workspace

One of the fastest ways to speed up your workflow is to make sure everything is always where you expect it to be. Sometimes when Creative Cloud updates apps, they have new panel configurations that they deem more efficient or something I guess. But for me, the fastest way to work is the way that I'm used to. So in all CC programs I use (not just Photoshop), I have a custom workspace saved that I can always go back to. 

Once you have all of your panels and tools arranged the way you like, click the `Choose a Workspace` icon in the top right corner of the window.

<img class="no-border" src="../../../../assets/images/PS-tips/custom-workspace-1.jpg" alt="Custom Workspace Menu" />

You'll see some pre-made workspaces in this menu, but any custom ones will appear here as well once saved. From this menu, select `New Workspace...`. 

<img class="no-border" src="../../../../assets/images/PS-tips/custom-workspace-2.jpg" alt="Custom Workspace Menu" />

In the dialog that pops up, name your workspace whatever you'd like. Photoshop defines a "workspace" as the visibility and placement of your panels, but you also have the option to include your tool configurations and keyboard shortcuts, which I've included here in mine.

<img class="no-border center" src="../../../../assets/images/PS-tips/custom-workspace-3.jpg" alt="Custom Workspace Menu" />

Once that's saved, you'll always be able to select your workspace and even reset it if you change things around and want to go back to how you had it originally. 

