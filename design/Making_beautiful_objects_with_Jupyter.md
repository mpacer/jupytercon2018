# Making beautiful objects with Jupyter

## Description:

Jupyter displays a rich array of media types out-of-the-box. In this talk, we
will describe how to use these capabilities to their full potential. We will
show how to add rich displays to existing and new Python classes. We will also
show you how to customise the way notebooks are converted to other formats.
These skills will enable anyone to make beautiful objects with Jupyter.

## Abstract:

Jupyter displays a rich array of media types out-of-the-box. In this talk, we
will describe how to use these capabilities to their full potential. We will
show how to add rich displays to existing and new Python classes. We will also
show you how to customise the way notebooks are converted to other formats.
These skills will enable anyone to make beautiful objects with Jupyter.

The talk will focus on specific examples. We will focus on examples that
illustrate concrete skills that you can immediately use to create beautiful
objects with Jupyter. Some of these examples are:

- how to enhance the display objects and classes in the notebook
    - by adding metadata to any output via `IPython.display`
    - by adding custom `_repr_*_` methods 
    - by using updatable displays
- libraries that enable new kinds of displays, including:
    - `vdom`: a library for React-like declarative layouts
    - `display_xml`: a library for displaying highlighted, indented XML
- how to convert notebooks into custom objects using `nbconvert`, which allows:
    - hiding prompts and code cells to show only the output figures
    - html where you can toggle whether individual code cells are visible
    - pdfs with support for non-Latin alphabets

To give a basis for understanding the examples, we will also cover a few
underlying concepts: 

- what mimetypes are and how to use them
- Jupyter's display mechanisms/protocol
    - output metadata
    - mimetype display priorities & outputs with multiple mimetypes 
    - `_repr_*_` methods, especially 
        - `_repr_html_`: for html displays 
        - `_repr_mimebundle_`: for custom mimetypes and multiple mimetypes
- how `nbconvert` works
    - designing and using custom templates
    - custom exports using configuration options
    - format-specific mimetype display priorities
    - `pip install`able 3rd-party exporters

## Who is this presentation for?

Jupyter users, Python library developers, or anyone who wants to use beautiful
objects to communicate with Jupyter.

## What's the takeaway for the audience?

> Main ideas and/or skills attendees will learn from your presentation

- What mimetypes are, and how they are used in the Jupyter display protocol.
- How to create Python classes with rich displays.
- How to provide multiple outputs with multiple mimetypes using 
  `_repr_mimebundle_`.
- How to update displays using `display_id`s.
- How to use `vdom` to create declarative layouts in Python.
- How to use `pygments` as part of a `_repr_*_` method for highlighting text.
- How to design and use custom templates for `nbconvert`.
- How to hide code cells and prompts in exported formats. 
- How to provide mimetype specific output metadata.

## Is this session more conceptual or how-to?

How-to

## Prerequisite knowledge and/or requirements needed by attendees

> This information is crucial for attendees. Please describe what skills and knowledge attendees need to have in order to get the most from your talk.

- A basic understanding of Python classes and methods (we'll be using them a
  lot).

## Expertise expected

Intermediate  

## Speaker videos
Pacer, M, Hamrick, J., & Avila, D. (2017) The Jupyter notebook as document: From structure to application. Jupytercon 2017, New York, NY. 
https://www.youtube.com/watch?v=V3cENs1UYQU&list=PL055Epbe6d5aP6Ru42r7hk68GTSaclYgi&t=158s&index=64


## Speaker bios

M Pacer is a Jupyter core developer at the Berkeley Institute for Data Science (BIDS) focusing on the intersection between Jupyter and scientific publishing (with an eye toward constructing a total scientific record that is more amenable to machine learning techniques). M holds a PhD from UC Berkeley, where their research used machine learning and human experiments to study causal explanation and causal inference, and a BS from Yale University.

