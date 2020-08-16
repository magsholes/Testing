---
layout: post
title:  "Photoshop Workflow Tips"
date:   2020-08-08 10:44:00 -0600
featured-image: PS-tips-thumbnail.jpg
featured-image-alt: The Simplest Ways to Speed Up Your Photoshop Workflow
categories: [journal]
tags: 
---

Here are a few of my favorite shortcuts, secrets, and tips that I frequently use to speed up my workflow.

### 1. Quick Brush Resizing

Most people know the shortcut for increasing or decreasing your brush size without having to manually fiddle with the brush settings—right square bracket `]` to increase and left square bracket `[` to decrease. That's great, but there's a better way that gives you even more control. 

With the brush tool selected (or eraser tool, or clone stamp tool, or any other tool with an adjustable diameter and hardness) hold down `Control`, hold down `Option`, and click and hold. You'll see a red shape that represents your brush.

While still holding down your mouse, drag the cursor left to shrink the diameter and right to increase it. Moving your cursor up or down will adjust the hardness.

<img class="single no-border" src="../../../../assets/images/PS-tips-brush-resize.gif" alt="Resize Brush" />

---

### 2. Mask Tight Corners with Brush Tool

For a lot of people, the pen tool is the go-to for cutting out an image from its background, but I personally prefer using the brush tool for masking when possible. It feels more natural to me, and I find it especially useful for soft edges. But once you run into a tight corner to cut out, the brush tool can be a little awkward to use. Here's an example of a corner that would be easy for the pen tool to handle but maybe not so much the brush tool:

No matter how tiny you shrink the brush, it's impossible to get in those corners without it looking weird. The trick to making it work is stupidly simple: basically, over-mask, then go back and paint the subject back in.

Another option that I've been using more and more is to mask the opposite of how you normally would—mask out the subject instead of the background, then simply invert the mask when you're done.

---

### 3. Realistically Mask Fur/Hair

This trick is really similar to the first one in that you over-mask and then paint something back in, but it gets a little more involved by using a custom brush to "paint" the hair or fur back in. First, draw a shape similar to this with the pen tool:

Using the marquee tool, select your shape, then go to `Edit > Define Brush Preset`. Name it whatever you want, then go over to the brush settings panel (`Window > Brush Settings` if yours isn't already displayed) and fiddle around with the scatter settings. Here's what my settings look like:

Then, using this new brush with these settings, paint the hair back in until it looks natural.

You can save the specific settings for this brush through the Brush Settings panel menu and use it later.

---

### 4. Custom Shortcuts

With any fresh install of Photoshop, the first thing I do is set up custom shortcuts that significantly speed up my workflow. You can create these shortcuts by going to `Edit > Keyboard Shortcuts` These are of course custom but here are the ones that I use daily:

- Flatten Image
<br />`Cmd + Shift + F` 
<br />*(overrides default preset)*
- Trim
<br />`Cmd + Shift + 0`
- 