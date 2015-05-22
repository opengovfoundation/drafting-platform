**Currently a work in progress**

# Policy Drafting Platform
**A drafting environment based on Etherpad built for and with legislative policy drafters**

[demo](http://drafting-demo.opengovfoundation.org)

[TL;DR skip to plugins and installation]()

*Or*

[Get Involved]()

## What are we trying to solve?

The status of policy document editing on the web today only focuses on aesthetics - bold, underline, italics, etc.  This is a very shallow representation of more complex documents such as legal codes or policy documents.  The markings on these documents have meaning, and the meaning is much more important than the font weight.  The web and semantic markup gives us the ability to capture this meaning behind the scenes while keeping the drafting process simple for the author.

## What are we building?

Authors will be able to draft in an environment that feels like what they’re used to - word processors such as MS Word.  The platform, however, will have an understanding of the document context.  The editor will understand citations to legal codes, amendments, and other domain-specific elements and simplify connecting inter-related documents.  It will also provide the final product in a multitude of formats including Word documents, PDFs, HTML, and even XML.

## How are we building it?

We're developing a number of plugins for [Etherpad](https://github.com/ether/etherpad-lite) to customize the tool to be tailored for policy drafting.  The plugins and installation guide are listed below.

## Current Plugin List

* [ep_comments_page](https://github.com/JohnMcLear/ep_comments)
* [ep_page_view](https://github.com/ether/ep_page_view)
* [ep_br_to_p](https://github.com/codingisacopingstrategy/ep_br_to_p)
* [ep_real_time_chat](https://github.com/JohnMcLear/ep_real_time_chat)
* [ep_context](https://github.com/JohnMcLear/ep_context)
* [ep_define](https://github.com/JohnMcLear/ep_define)
* [ep_reference](https://github.com/JohnMcLear/ep_reference)
* [ep_indent_context](https://github.com/JohnMcLear/ep_indent_context)
* [ep_table_of_contents]('https://github.com/JohnMcLear/ep_table_of_contents)
* [ep_spellcheck](https://github.com/johnmclear/ep_spellcheck)
* [ep_mammoth](https://github.com/JohnMcLear/ep_mammoth)
* [ep_text_statistics](https://github.com/JohnMcLear/ep_text_statistics)
* [ep_headings2](https://github.com/johnmclear/ep_headings2)
* [ep_align](https://github.com/johnmclear/ep_align)
* [ep_print](https://github.com/JohnMcLear/ep_print)


## Installation

1. See the [Etherpad Installation Instructions](https://github.com/ether/etherpad-lite#installation) on how to get the platform up and running.
1. To install our specific plugins, run
  `npm install ep_comments_page ep_page_view ep_br_to_p ep_real_time_chat ep_context ep_define ep_reference ep_indent_context ep_table_of_contents ep_spellcheck ep_mammoth ep_text_statistics ep_headings2 ep_align ep_print`




## Contribute / Get Involved




## Other Resources

[Our original platform pitch Hackpad](https://hackpad.com/Drafting-Platform-Elevator-Pitch-ZM6PnXffVjJ)
[Our User Stories Hackpad](https://hackpad.com/Drafting-Platform-User-Stories-dJsawc36A9t)
