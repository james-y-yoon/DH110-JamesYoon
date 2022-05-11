# Assignment 06: Interface Design

James Yoon

Digital Humanities 110: User Experience and Design (S'22)

# Summary

This UX project aims to make Ultimate-Guitar easier to use and relevant for both beginner and advanced users. I want to provide enough context to the app so that beginner users can get a sense of how guitar and music theory works, while still allowing for flexibility so that advanced users can focus on the tasks that apply to them. Last week, I created a low-fidelity prototype on paper so that I could focus the content of each wireframe and the overall layout. This week, I focused on interface design and *how* the buttons and modules I created last week will look on a phone/mobile screen.

This assignment consisted of four steps:

- Digitizing my wireflow from last week on Figma.
- Deciding on a layout using Figma's grid system.
- Testing different fonts, shapes, and colors.
- Doing an impression test with another person for feedback.
- Checking color accessibility through color contrast.

# Digitized Wireflow

[My digitized wireflow can be found here under "Wireflow".](https://www.figma.com/file/yUsEoH8TuOMggfTpZ1Buwf/Ultimate-Guitar-A06?node-id=107%3A96)

Given the size of the wireflow, all subsequent interface tests were done with the home page (labeled "homepage") on Figma.

# Interface Tests

## Layout

During the digitization process, I focused on the layout of the screens. Using the homepage as the case study, I created a grid pattern consisting of 9 rows and 1 column. 9 rows seemed appropriate, since it allowed enough room and spacing for modules or links to guitar tabs without overloading the user with too much information. Given that I created this prototype on a mobile frame, I chose 1 column to minimize clutter.

The grid parameters are below:

- **ROWS**: 9 rows, 0 margin, 20 gutter
- **COLUMNS**: 1 column, 20 margin

My reasoning behind choosing 20 pts as my margin was for consistency with the gutter as well as being approximately ~40% of the text size of the headings (32pt). This margin size is close to the recommended size (half the size of the text size), and giving just slightly more margin room than expected might make the app seem cluttered.

## Typography

For the rest of the interface tests, I created duplicates of the homepage. [All of these wireframes can be found on Figma here.](https://www.figma.com/file/yUsEoH8TuOMggfTpZ1Buwf/Ultimate-Guitar-A06?node-id=104%3A96)

The first row of four screens consisted of homepage-prociono-libre-franklin; homepage-koulen-libre-franklin; homepage-crimson-pro-inter; and homepage-oswald-prociono. Each screen was named according to *homepage-headingtextfont-subheading/bodytextfont*. As thus, the fonts are summarized below.

| Screen      | Heading Font | Subheading/Body Font | 
| ----------- | ----------- | -----------------|
| homepage-prociono-libre-franklin      | Prociono (Serif)      | Libre Franklin (Sans-Serif) |
| homepage-koulen-libre-franklin   | Koulen (Display, Sans-Serif)        | Libre Franklin (Sans-Serif) |
| homepage-crimson-pro-inter   | Crimson Pro (Serif)        | Inter (Sans-Serif) |
| homepage-oswald-prociono   | Oswald (Display, Sans-Serif)        | Prociono (Serif) |

For the body fonts, Libre Franklin and Inter are very similar sans-serif fonts, while Prociono is a serif font that may convey more of a formal, academic feel. For the headings, all four screens have heading fonts that are quite different from the body fonts, which will help with distinguishing which is which. As with the body font, Prociono and Crimson Pro might convey more of an academic tone, while Koulen and Oswald are more informal. 

Koulen is all upper-case, which may impact readability. However, since it would only be used for headers, it wouldn't be as inaccessible as if it were used for body text.

## 

