---
layout: post
title: "The unexpectedly wonderful sensation of conforming an edit using Difference blend mode."
microblog: false
guid: http://davids.micro.blog/2022/12/01/the-unexpectedly-wonderful.html
post_id: 1741255
date: 2022-12-01T20:00:00-0800
lastmod: 2025-01-29T02:29:13-0800
type: post
categories:
- "Editing"
images:
- https://davids.micro.blog/uploads/2022/f9521a25ab.gif
- https://davids.micro.blog/uploads/2022/3f48ad4525.gif
- https://davids.micro.blog/uploads/2022/808bd01b2c.gif
photos:
photos_with_metadata:
url: /2022/12/01/the-unexpectedly-wonderful.html
---
In my video editing work, sometimes I need to make sure two videos match up perfectly, frame to frame. This could be for a variety of reasons, but today it was because I was conforming an edit that was done in Premiere Pro, to finish it with color and audio in DaVinci Resolve. “[Conforming](https://blog.frame.io/2019/03/29/conforming-with-resolve/)” encompasses a lot of things, but for my purposes it basically means, “Did this timeline make it ok from one program to the other? Did anything break? Are all the shots lining up?

I usually start by firing off an export from the original app as a reference video, and lay that reference video on top of my imported timeline in Resolve. Then, I change its blend mode to “Difference.” That does exactly what you’d think – it highlights the differences between the top and bottom clips in the timeline. So when I watch back the program, I should hope to see nothing but blackness, because everything matched up perfectly, right? …right?

![](https://davids.micro.blog/uploads/2022/f9521a25ab.gif)

Shoot. Here I had a clip that used [Premiere’s “Modify → Interpret Footage” workflow](https://helpx.adobe.com/premiere-pro/using/organizing-assets-project-panel.html#change_the_frame_rate_of_a_clip) for slow motion, something that doesn’t carry over via XML to Resolve[^1]. So I slowed my 30 FPS clip down to 80% and started slipping it left and right, frame by frame, until the most satisfying moment:

![](https://davids.micro.blog/uploads/2022/3f48ad4525.gif)

Ahhhh.

Conforming can be an annoying, frustrating experience at times, so I think it’s important to take a bit of joy in moments like these. Plus, sometimes clips with Difference blending that are slightly off sync can yield some cool results when in motion:

![](https://davids.micro.blog/uploads/2022/808bd01b2c.gif)

[^1]:	If you’re still using this workflow, I highly recommend just learning to slow things down in the timeline by percentages. ☺️ There’s a whole bunch of issues in Premiere related to using Modify → Interpret Footage for slow mo. If you edit in Final Cut you’re lucky because there’s a command for automating that! Search for “Automatic Speed” in the keyboard shortcut customization window and bask in Apple’s occasional rightdoing with FCPX.
