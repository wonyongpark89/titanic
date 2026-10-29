---
name: Remembering Titanic
description: A shared enquiry across science, history and place.
colors:
  ink: "#203f32"
  paper: "#f8f5ef"
  muted: "#516457"
  blue: "#d1dcff"
  lime: "#ebf788"
  rule: "#c6ccc1"
  footer: "#e9ecdf"
  primary-hover: "#355746"
  secondary-hover: "#bdcbf4"
typography:
  display:
    fontFamily: "'DM Sans', sans-serif"
    fontSize: "clamp(46px, 6.6vw, 92px)"
    fontWeight: 800
    lineHeight: 1.06
    letterSpacing: "-0.04em"
  heading:
    fontFamily: "'DM Sans', sans-serif"
    fontSize: "clamp(32px, 3.6vw, 48px)"
    fontWeight: 700
    lineHeight: 1.12
    letterSpacing: "-0.035em"
  body:
    fontFamily: "'DM Sans', sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.65
  control:
    fontFamily: "'DM Sans', sans-serif"
    fontSize: "16px"
    fontWeight: 700
rounded:
  pill: "100px"
  filter: "30px"
spacing:
  section: "90px"
  section-mobile: "48px"
  gutter: "48px"
  gutter-mobile: "22px"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    typography: "{typography.control}"
    rounded: "{rounded.pill}"
    padding: "17px 26px"
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
  button-secondary:
    backgroundColor: "{colors.blue}"
    textColor: "{colors.ink}"
    typography: "{typography.control}"
    rounded: "{rounded.pill}"
    padding: "17px 26px"
  button-secondary-hover:
    backgroundColor: "{colors.secondary-hover}"
  filter:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.filter}"
    padding: "10px 21px"
  filter-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
---
# Design System: Remembering Titanic

## Overview
**Creative North Star: "A shared enquiry"**

A friendly editorial education site that connects classroom resources with educational research. Cream, bold green lettering and periwinkle annotations adapt the user's supplied reference; real project photography anchors the design in collaborative learning.

**Key Characteristics:**
- Equal prominence for teaching resources and research.
- Real workshop photography and preserved partner identities.
- Generous typography, flat colour fields and clearly divided lists.

## Colors
Paper is the default canvas and ink carries text and primary actions. Blue marks research and shared enquiry; lime provides concentrated emphasis. Muted ink carries metadata. Rule separates lists; the footer surface closes the page softly.

**The Equal Paths Rule.** Resources and research receive equal structural space even when their action colours differ.

## Typography
DM Sans is self-hosted under SIL OFL. The display and heading tokens describe desktop defaults. The homepage display uses the display token; interior page headings use clamp(44px, 5.6vw, 78px). Body measure is capped at 70ch.

At widths up to 600px, body text becomes 17px, homepage display uses clamp(39px, 9.6vw, 57px), and interior page headings use 43px. Resource headings, publication titles and metadata have smaller contextual scales in the stylesheet.

## Layout
Most content is capped at 1280px, with the header and photo band capped at 1400px. Sections use the documented gutters and vertical spacing. At 900px gutters narrow to 28px; at 600px the main content grids become a single column and use mobile spacing.

The homepage gives the two audiences equal actions and paired editorial panels. Resources use subject filters above a lesson list; native disclosures expose file downloads. Research uses a publication list and contextual prose. Workshop and people pages retain the legacy paths.

## Elevation & Depth
No shadows. Depth comes from contrast between paper, periwinkle, lime and the footer surface, with thin rules separating content. Images remain rectangular.

## Shapes
Pills belong to actions and filters. Content remains in flat rectangular sections. The homepage headline receives an elliptical periwinkle annotation; the research headline uses an underline. The small RT mark has a circular outline.

## Components
### Buttons
Primary actions use ink and paper; secondary actions use blue and ink. Both use the pill token, a 2px matching border and a minimum 58px height. Hover changes the background; keyboard focus receives an ink outline. On mobile, hero actions stack, padding becomes 13px 20px and minimum height becomes 54px.

### Filters
Subject chips use native buttons with aria-pressed. Selected and hovered filters use ink with paper text. The filter bar appears only after JavaScript enhancement; lesson materials remain accessible without JavaScript.

### Navigation
Text links wrap naturally on mobile. Current and hovered links receive an underline. The header retains all four navigation choices rather than hiding them behind a menu.

### Downloads and disclosures
File links pair a descriptive title with format and size. Native details/summary elements expose files with a keyboard-operable disclosure. On narrow screens, lesson download metadata stacks beneath the title.

### Partner identities
User-supplied partner artwork is retained. The Southampton SVG viewBox is normalised around the artwork with padding, improving legibility without changing its paths or colours. Photographs are resized and converted to WebP.

### Accessible states
A skip link, visible keyboard focus, labelled filter group and live result count support navigation. Reduced-motion preference removes smooth scrolling and transitions. Hover is never required to access content.

## Do's and Don'ts
### Do:
- Do give teaching resources and research equal structural prominence.
- Do use real project images and maintain partner artwork proportions.
- Do keep resource downloads available without JavaScript.
### Don't:
- Don't use tragedy as decorative spectacle.
- Don't invent research claims, publication metadata or testimonials.
- Don't extend the lesson licence automatically to photographs and logos.
