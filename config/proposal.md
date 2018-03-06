# Jupyter User Config: Proposal for JupyterCon 2018

## Title

*Configuring Jupyter: using, understanding, and debugging Jupyter's config
systems*

## Description (400chars)

> brief overview for marketing purposes, max. length 400 characters—about 65 words

Jupyter's defaults make starting easy, but good defaults only go so far.
Eventually, everyone wants something to be different; they use configuration
settings to make it so. Jupyter's config systems are powerful and flexible,
but finicky and fragile, causing hard-to-debug issues. We will explain Jupyter's
config systems, how to use them, and how to debug them when something
(inevitably) goes wrong. 

## Abstract (3-6 paragraphs)

> (Longer, more detailed description (3-6 paragraph, bullet points welcome) of your presentation to help the program committee understand what you will cover. If your proposal is chosen, this is the description that will appear on the website. Note that our copywriters may edit it for consistency and O'Reilly voice.)

Jupyter's straightforward, out-of-the-box experience has been important for its
success in wide-spread adoption. But good defaults only go so far.

As much as the defaults encourage adoption, Jupyter's modular design and
powerful, flexible configuration systems inspire users' creativity and
enthusiasm. By enabling people to customise how they want their tools to work,
Jupyter's config systems allow people to determine their own computational
destiny. At the same time, with great power comes great fragility — the same
config files that enable user freedom and empowerment are a source of user
frustration and confusion. Because of how Jupyter's configuration systems work,
tracing down the source of a configuration issue can be an arduous task. 

Despite their crucial role in determining the overall user experience, Jupyter's
configuration systems have never been treated as a singular topic. In this talk,
we will do exactly that. We will provide our audience with an understanding for
how to think about Jupyter's config systems, how to use them productively, and
how to debug them when things (inevitably) break. This is all the more important
to do today, JupyterLab introduces new configuration systems and 
user-friendly interfaces for setting those configuration values.

The talk will be organised around concrete examples to illustrate the ideas needed to use, understand, and  Jupyter's configuration system
rather than describing high-level concepts. We will discuss topics such as:

- Jupyter's python-based configuration systems (via traitlets.config)
    - examples illustrating where configuration values can be set, and why you 
      would use each. E.g.,:
        - on the command line,
        - in configuration files
        - in programmatic code
    - examples showing functional differences between `.py` and `.json` config 
      files and why you would use each
    - examples demonstrating Jupyter's hierarchical semantics for setting, 
      inheriting and overwriting config values
    - examples explaining what it means to install, enable and disable
      serverextensions
        - example of how to set up a library so that when the library is 
          installed it automatically installs and enables its serverextensions
    - examples of how to use `jupyter_conf_search` to help when debugging 
      configuration issues by programmatically finding their source
- JupyterLab's configuration systems
    - examples illustrating Jupyterlab's hierarchical semantics for setting,
      inheriting, and overwriting configuration values at the system, user and
      …(sorry Darian, I am blanking on the third one) levels
    - examples of how to use themes and user display settings
    - examples of how to set custom keybindings
    - examples showing how users' layouts are saved and how to reset them
    - examples of how to enable and disable labextensions 

MP: Darian, I wasn't sure what all you would want to cover as concrete examples,
so I wrote a few things that came to mine


## Who is this presentation for?

> (Job titles/functions and/or experience, for instance)

Jupyter users, Jupyter extension developers (both serverextensions and
labextensions), Jupyter contributors 


## What's the takeaway for the audience?

> Main ideas and/or skills attendees will learn from your presentation

- How to set configuration values from the command line, via static files, and programmatically
- How to create new configuration options in Jupyter applications and extensions
- When to use different kinds of configuration files
- How to automatically enable serverextensions when pip installing a library 
- How to find configuration files that are currently in use
- How to use jupyter_conf_search to debug configuration issues 
- How to change the settings in jupuyterlab via the settings editor, the raw 
  json editor, or the configuration files themselves
- How to set custom keybindings
- How to reset stored layout information
- How to enable and disable labextensions (as a developer and a user), including 
  core jupyterlab extensions



## Is this session more conceptual or how-to?

How-to

## Prerequisite knowledge and/or requirements needed by attendees

> This information is crucial for attendees. Please describe what skills and knowledge attendees need to have in order to get the most from your talk.

- some knowledge of Jupyter 
- Familiarity with JSON will be helpful, but is not necessary. 
- Some idea of what a configuration file is will be helpful, but not necessary

## Special Equipment needs

> Note: Each presentation room will have a podium, projector, 16:9 screen, head table, microphone, ethernet connection, and wifi.


## Speaker videos
M: Pacer, M, Hamrick, J., & Avila, D. (2017) The Jupyter notebook as document: From structure to application. Jupytercon 2017, New York, NY. 
https://www.youtube.com/watch?v=V3cENs1UYQU&list=PL055Epbe6d5aP6Ru42r7hk68GTSaclYgi&t=158s&index=64

Darian:

## Reimbursement needs for travel or other conference-related expenses


## Speaker Bios

## Outlining
