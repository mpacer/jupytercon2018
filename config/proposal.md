# Jupyter User Config: Proposal for JupyterCon 2018

## Title

*Making Jupyter your own: user configuration across the Jupyter ecosystem*

## Description (400chars)

> brief overview for marketing purposes, max. length 400 characters—about 65 words

Jupyter's defaults make starting easy, but good defaults only go so far. We want
to enable users to go beyond the defaults and make Jupyter their own through
Jupyter's powerful, flexible configuration systems. But these systems can be
subtle and complicated, resulting in hard-to-debug issues. We will explain
Jupyter's config systems, how to use them, and how to debug if something
goes wrong. 

## Abstract (3-6 paragraphs)

> (Longer, more detailed description (3-6 paragraph, bullet points welcome) of your presentation to help the program committee understand what you will cover. If your proposal is chosen, this is the description that will appear on the website. Note that our copywriters may edit it for consistency and O'Reilly voice.)

Jupyter's straightforward, out-of-the-box experience has been important for its
success in wide-spread adoption. But good defaults only go so far. In this talk,
we want to empower users to go beyond the defaults and make Jupyter their own.

As much as the defaults encourage adoption, Jupyter's modular design and
powerful, flexible configuration systems inspire users' creativity and
enthusiasm. By enabling people to customise how they want their tools to work,
Jupyter's config systems allow people to determine their own computational
destiny. At the same time, with great power comes great fragility — the same
config files that enable user freedom and empowerment are a potential source of
user frustration and confusion. Because of how Jupyter's configuration systems
work, tracing down the source of a configuration issue can be an arduous task. 

Despite their crucial role in determining the overall user experience, Jupyter's
configuration systems have never been treated as a singular topic. In this talk,
we will do exactly that. We will provide our audience with an understanding for
how to think about Jupyter's config systems, how to use them productively, and
how to debug them when things (inevitably) break. This is all the more important
to do today, JupyterLab introduces new configuration systems and 
user-friendly interfaces for setting those configuration values.

The talk will be organised around concrete examples and demos to illustrate the
ideas needed to use, understand, and debug Jupyter's configuration system. Some
topics will be demonstrations of Jupyterlab UIs, while others will show the role
of configuration across a number of Jupyter libraries, including `nbconvert`,
the `notebook` server, `jupyterlab-latex`, and `traitlets.config`.

We will discuss topics such as:

- Jupyter's Python-based configuration systems (via traitlets.config)
    - How to set, and why you would set configuration settings…
        - on the command line,
        - in configuration files,
        - or, in programmatic code.
    - The many scopes of configuration, and how to use them to your advantage.
    - What `serverextension`s are, how to install/enable/disable them 
    - How to build configurable API handlers and non-configurable API handlers 
      that can still use configuration files.
    - How to use `jupyter_conf_search` to help you hunt down configuration 
      issues.
- JupyterLab's configuration systems
    - How to use themes.
    - How to set custom keybindings.
    - How to save and manipulate user sessions, *i.e.*, JupyterLab workspaces.
    - How to enable and disable `labextension`s.
    - How to reason about Jupyterlab's hierarchical semantics for creating
      defaults and allowing overrides.

## Who is this presentation for?

> (Job titles/functions and/or experience, for instance)

Jupyter users, Jupyter extension developers (both `serverextension`s and
`labextension`s), Jupyter contributors 


## What's the takeaway for the audience?

> Main ideas and/or skills attendees will learn from your presentation

- How to set configuration values from the command line, via static files, and programmatically.
- How to create new configuration options in Jupyter applications and extensions
- How to automatically enable `serverextension`s when `pip install`ing a library .
- How to find configuration files that are currently in use.
- Best practices for exposing configuration to a notebook, Tornado-based API handler for the Jupyter server.
- How to use `jupyter_conf_search` to debug configuration issues. 
- How to change in JupyterLab settings within the lab user interface.
- How to use themes and custom keybindings.
- How to reset stored layout information and create saved workspaces.
- How to enable and disable `labextension`s (as a developer and a user), including 
  core JupyterLab extensions



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

## Reimbursement needs for travel or other conference-related expenses


## Speaker Bios
Afshin Darian is one of the co-authors of JupyterLab. He has been active in the open source community for several years.

M Pacer is a Jupyter core developer at the Berkeley Institute for Data Science (BIDS) focusing on the intersection between Jupyter and scientific publishing (with an eye toward constructing a total scientific record that is more amenable to machine learning techniques). M holds a PhD from UC Berkeley, where their research used machine learning and human experiments to study casual explanation and causal inference, and a BS from Yale University.


## Outlining
