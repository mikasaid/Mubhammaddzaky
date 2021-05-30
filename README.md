You're probably aren't going to take the time to read this document if you're not interested, but there are a lot of nice side effects caused by learning how to create quality screencasts.

Communicating more effectively - At Envy Labs we produce screencasts for our clients all the time. Whether it's demoing a new feature or for a presentation for an invester, they're often much more effective and pleasent than a phone call or screen sharing.

To Become a Teacher - There is no more noble a profession than passing on knowledge. There is a great deal of knowledge in the world and with the technology we now have available combined with the tools in this screencast, anyone can teach better than 99% of the people out there.

To Make Money Teaching - If you join the Code School screencasting team we'll pay you to create quality casts. At the bottom of this document we'll tell you how to submit an audition video.

To Work with Us - We're creating a system where you'll work with our team to polish your work and improve your screencasting skills.

A Side Note on Composition
When teaching technology concepts there is always a certain amount of theory. You might call this, the "Idea" or "Intent" of the code. On most typical screencasts all that the viewer sees is the instructor's screen. Thus when theory is discussed many times the listener stops watching and is forced to listen. This is typically where people start to fall alseep. To combat this, I'm employing two different strategies:

Use of slides - Slides are the perfect medium for teaching concepts. In many of my videos I avoid showing desktop all together, since I can focus the user on just the code I'm talking about.

Facetime - Humans are attracted to faces. When it comes time to explain an idea or concept, seeing someone's face speaking to them can capture their attention more frequently.

This tutorial will show how to use both these techniques to create effective educational content.

Stuff you'll need
Webcam or USB Camera - In order to really be effective at screencasting you need to show yourself, so you need a webcam, or USB camera. You're going to want to show yourself. A built in camera is fine, that's what I like to use.

Screenflow or Camtasia - Both of these products have free trials, but you'll eventually want to buy a copy of one of them for ($99). I prefer Screenflow at the moment. However, don't worry about going out and buying it immediately. If you're trying out for the Code School Screencasting team, instead of sending me video you can just zip up your screenflow file (from the trial app) and send that instead of a video file.

USB Microphone - Quality audio for screencasts is really important, even more than quality video. Which is why I recommend getting a USB Microphone if you're really serious about this stuff. If you want to try out for our Screencasting team though, feel free to skip purchasing one and just use what you have for now.

Patience - Just like learning a new web framework for creating web applications, please have patience as you work through this framework and create your own screencast for the first time. Know that there's always room to improve, and anything you submit for the first time, I'll probably have some small revisions needed before it goes live.

Scripting
To create effective screencasts you need to have an effective script or outline of what you want to cover.

Outlining - Outlines can be as simple or complex as you need them to be. Here is an outline of a screencast which covers how to use the css3button gem.

Assumptions, Problem, & Solution - Keynote slides

This screencast assumes you're familiar with Rails basics. It's beginner.
"So you're working on an application, and it has crappy buttons." Show boring scaffolding.
Show css3buttons. "You want pretty buttons like these"
"Enter css3buttons gem, created by Nicholas Bruning." Show github page for css3buttons and give credit to the authors.
Demo - Show some code

Show steps needed to implement css3buttons in a Rails app.
WIN
Show advanced usage - Keynote slides

Show different icons, styles, colors, and button groups
Challenge - Keynote Slides

Give the viewers a challenge which uses the buttons.
Figure out all your code - This is where you figure out all code you're going to show during the screencast along with your base app.

A. Find or create a good base app to work with. I recommend doing is starting either with a empty Rails app with a few scaffolds, or a real basic Rails app like Nerd Factory.

B. Create a copy of your starting point, and label one directory "-before" and one "-after". This idea came from Ryan Bates's RailsCasts. His demo app for episode #264 was called "todo"

before and after directories

C. Go through the app in your "-after" directory, making modifications and taking notes as to what you're doing along the way. Obviously you don't want to demonstrate something too complex. It's better to show a short entertaining demo than to be completely thorough. Here is an example for the CSS3Butttons screencast of what my code script looks like as I modified the "demo-after" directory.

Inside Gemfile add - 'gem css3buttons'
$ bundle
$ rails g css3buttons
$ rails s
Place before stylesheet declarations in layout <%= css3buttons_stylesheets %> Reason is that it includes a reset stylesheet. If you don't want to use the reset.. <%= css3buttons_stylesheets :include_reset => false %>
/app/views/users/_form.html.erb - line 31 - button_submit_tag
/app/views/users/index.html.erb - (on new - line 29) button_link_to add_button_link_to # Talk about resolution...
Then show CSS3 Github Buttons on browser. (on edit) pill_button_link_to, pill_button_link_to, pill_button_link_to negative_button_link_to edit_button_link_to, remove_negative_button_link_to
remove th and tds and do "<%= button_group do %>"
These notes may not make sense to you, since I gave myself just enough notes so I can reproduce the changes once I start filming the actual screencast. It's important at this stage to TEST out everything you're going to show so once you start recording, everything will go as planned (with any luck).

Review - If you'd like feedback from me or the community, this would be the time to do it. Throw your script into an email or a github gist. This is obviously the best time for feedback, before you started constructing any of the materials for the cast itself.You're probably aren't going to take the time to read this document if you're not interested, but there are a lot of nice side effects caused by learning how to create quality screencasts.

Communicating more effectively - At Envy Labs we produce screencasts for our clients all the time. Whether it's demoing a new feature or for a presentation for an invester, they're often much more effective and pleasent than a phone call or screen sharing.

To Become a Teacher - There is no more noble a profession than passing on knowledge. There is a great deal of knowledge in the world and with the technology we now have available combined with the tools in this screencast, anyone can teach better than 99% of the people out there.

To Make Money Teaching - If you join the Code School screencasting team we'll pay you to create quality casts. At the bottom of this document we'll tell you how to submit an audition video.

To Work with Us - We're creating a system where you'll work with our team to polish your work and improve your screencasting skills.

A Side Note on Composition

When teaching technology concepts there is always a certain amount of theory. You might call this, the "Idea" or "Intent" of the code. On most typical screencasts all that the viewer sees is the instructor's screen. Thus when theory is discussed many times the listener stops watching and is forced to listen. This is typically where people start to fall alseep. To combat this, I'm employing two different strategies:

Use of slides - Slides are the perfect medium for teaching concepts. In many of my videos I avoid showing desktop all together, since I can focus the user on just the code I'm talking about.

Facetime - Humans are attracted to faces. When it comes time to explain an idea or concept, seeing someone's face speaking to them can capture their attention more frequently.

This tutorial will show how to use both these techniques to create effective educational content.

Stuff you'll need

Webcam or USB Camera - In order to really be effective at screencasting you need to show yourself, so you need a webcam, or USB camera. You're going to want to show yourself. A built in camera is fine, that's what I like to use.

Screenflow or Camtasia - Both of these products have free trials, but you'll eventually want to buy a copy of one of them for ($99). I prefer Screenflow at the moment. However, don't worry about going out and buying it immediately. If you're trying out for the Code School Screencasting team, instead of sending me video you can just zip up your screenflow file (from the trial app) and send that instead of a video file.

USB Microphone - Quality audio for screencasts is really important, even more than quality video. Which is why I recommend getting a USB Microphone if you're really serious about this stuff. If you want to try out for our Screencasting team though, feel free to skip purchasing one and just use what you have for now.

Patience - Just like learning a new web framework for creating web applications, please have patience as you work through this framework and create your own screencast for the first time. Know that there's always room to improve, and anything you submit for the first time, I'll probably have some small revisions needed before it goes live.

Scripting

To create effective screencasts you need to have an effective script or outline of what you want to cover.

Outlining - Outlines can be as simple or complex as you need them to be. Here is an outline of a screencast which covers how to use the css3button gem.

Assumptions, Problem, & Solution - Keynote slides

This screencast assumes you're familiar with Rails basics. It's beginner.

"So you're working on an application, and it has crappy buttons." Show boring scaffolding.

Show css3buttons. "You want pretty buttons like these"

"Enter css3buttons gem, created by Nicholas Bruning." Show github page for css3buttons and give credit to the authors.

Demo - Show some code

Show steps needed to implement css3buttons in a Rails app.

WIN

Show advanced usage - Keynote slides

Show different icons, styles, colors, and button groups

Challenge - Keynote Slides

Give the viewers a challenge which uses the buttons.

Figure out all your code - This is where you figure out all code you're going to show during the screencast along with your base app.

A. Find or create a good base app to work with. I recommend doing is starting either with a empty Rails app with a few scaffolds, or a real basic Rails app like Nerd Factory.

B. Create a copy of your starting point, and label one directory "-before" and one "-after". This idea came from Ryan Bates's RailsCasts. His demo app for episode #264 was called "todo"

before and after directories

C. Go through the app in your "-after" directory, making modifications and taking notes as to what you're doing along the way. Obviously you don't want to demonstrate something too complex. It's better to show a short entertaining demo than to be completely thorough. Here is an example for the CSS3Butttons screencast of what my code script looks like as I modified the "demo-after" directory.

Inside Gemfile add - 'gem css3buttons'

$ bundle

$ rails g css3buttons

$ rails s

Place before stylesheet declarations in layout <%= css3buttons_stylesheets %> Reason is that it includes a reset stylesheet. If you don't want to use the reset.. <%= css3buttons_stylesheets :include_reset => false %>

/app/views/users/_form.html.erb - line 31 - button_submit_tag

/app/views/users/index.html.erb - (on new - line 29) button_link_to add_button_link_to # Talk about resolution...

Then show CSS3 Github Buttons on browser. (on edit) pill_button_link_to, pill_button_link_to, pill_button_link_to negative_button_link_to edit_button_link_to, remove_negative_button_link_to

remove th and tds and do "<%= button_group do %>"

These notes may not make sense to you, since I gave myself just enough notes so I can reproduce the changes once I start filming the actual screencast. It's important at this stage to TEST out everything you're going to show so once you start recording, everything will go as planned (with any luck).

Review - If you'd like feedback from me or the community, this would be the time to do it. Throw your script into an email or a github gist. This is obviously the best time for feedback, before you started constructing any of the materials for the cast itself.
