==================================================================
  AI-GENERATED LANDING PAGE  -  STUDENT INSTRUCTIONS
==================================================================

WHAT YOU ARE BUILDING
---------------------
A responsive, one-page marketing website for a productivity app,
built with semantic HTML5 and modern CSS layout (Flexbox and/or
Grid). You are encouraged to use AI to help PLAN the design and
write the marketing COPY - but you must write the final CODE
yourself.

The page needs these sections, in order:
    HERO      - big headline, short subtext, a main button.
    FEATURES  - a few feature cards/items describing the app.
    CTA        - a "call to action" section inviting the visitor
                 to sign up / get started.
    FOOTER    - closing info (links, copyright, etc.).

It must look good on BOTH desktop and mobile (responsive).

NOTE: This is a plain HTML/CSS project - no build tools, no npm.
You will create two files and open the page in a browser.

QUICK VOCABULARY:
    Semantic HTML - using tags that describe MEANING (header, nav,
                    section, footer) instead of plain <div> for
                    everything.
    Flexbox       - a CSS system for arranging items in a row or
                    column with flexible spacing.
    Grid          - a CSS system for arranging items in rows AND
                    columns (great for feature cards).
    Responsive    - the layout adapts to screen size, so it looks
                    good on a phone and a laptop.
    Media query   - the CSS rule (@media) that applies different
                    styles at different screen widths.


------------------------------------------------------------------
STEP 0  -  FIND OUT WHERE YOU ARE (do this first!)
------------------------------------------------------------------
Open the terminal in VS Code:
  Top menu  ->  Terminal  ->  New Terminal

Type this and press Enter:

    whoami && pwd

  - "whoami" tells you your username.
  - "pwd" tells you which folder you are currently in.

Remember the folder it prints - this is where your project should
live.


------------------------------------------------------------------
STEP 1  -  CREATE THE PROJECT FOLDER AND FILES
------------------------------------------------------------------
You will create the folder and files by CLICKING inside VS Code.

  1. Look at the EXPLORER panel on the left (the file tree).
  2. Hover over the folder name at the top. Small icons appear.
  3. Click the "New Folder" icon. Type:   ai-generated-landing-page
     Press Enter.
  4. Click your new folder once to select it.
  5. Click the "New File" icon. Type:   index.html   Press Enter.
  6. Repeat to create:   style.css
  7. You should now see both files inside the folder.
  8. Click each file to open it, write your code (see STEP 3), and
     SAVE with Ctrl+S (Cmd+S on Mac).

  NOTE: If you cannot create the folder ("Permission denied"), go
  back to STEP 0, run "pwd", and create the project inside the
  folder that "pwd" showed you.


------------------------------------------------------------------
STEP 2  -  USE AI TO PLAN (ideas and copy, not final code)
------------------------------------------------------------------
Before writing code, use an AI assistant to PLAN. The goal is to
get ideas and wording quickly - you will still write the HTML/CSS
yourself.

  THINGS AI IS GREAT FOR HERE:
    - Inventing a fake app name and a one-line value proposition.
    - Drafting hero headline + subtext options.
    - Listing 3-4 feature ideas with short descriptions.
    - Suggesting a colour palette and font pairing.
    - Suggesting a layout (for example "hero centered, features in
      a 3-column grid that stacks on mobile").

  EXAMPLE PROMPTS YOU COULD ADAPT (write your own):
    - "Suggest a name and one-sentence pitch for a productivity
       app that helps remote teams plan their week."
    - "Give me 3 feature cards (title + one sentence each) for
       that app."
    - "Suggest a clean, modern colour palette (hex codes) and a
       Google Fonts pairing for a productivity landing page."

  IMPORTANT - WRITE THE CODE YOURSELF:
    Use the AI output as a PLAN and as text content. Do NOT paste
    AI-generated HTML/CSS as your final code - the assignment is
    about you building the layout. In your README later, jot a
    quick note on what the AI helped with (ideas, copy, palette).


------------------------------------------------------------------
STEP 3  -  WHAT TO BUILD (your code)
------------------------------------------------------------------
This is YOUR code to write. The points below describe what each
file needs. Try it yourself first - that is how you learn.

  ----------------------------------------------------------------
  index.html  (the structure - use SEMANTIC tags)
  ----------------------------------------------------------------
    - A normal HTML5 document, linking your style.css in the head.
    - Build the sections using MEANINGFUL, identifiable tags and
      names so they are clearly recognisable:
        * A HERO section (for example <section> with a hero class
          or id) containing a headline (h1), a short paragraph,
          and a button/link.
        * A FEATURES section containing several feature items
          (each with a small heading and a short description).
          Cards laid out side by side work well here.
        * A CTA section (call to action) with a short persuasive
          line and a button/link.
        * A <footer> with closing content.
    - Prefer semantic tags (header, nav, section, footer, etc.)
      over wrapping everything in plain <div>s.
    - TIP: give the hero, features, and cta sections clear class
      or id names (like "hero", "features", "cta") - it keeps your
      CSS organised and makes the sections easy to identify.

  ----------------------------------------------------------------
  style.css  (the look - use FLEXBOX and/or GRID)
  ----------------------------------------------------------------
    - Style the page so typography and spacing are readable and
      consistent (sensible font sizes, line spacing, padding).
    - Use FLEXBOX and/or GRID for layout. Common choices:
        * Grid for the row of feature cards.
        * Flexbox for the hero or a nav bar (aligning items in a
          row, centering content).
    - Make it RESPONSIVE: add at least one media query (@media) so
      the layout adapts on small screens - for example, feature
      cards that sit in a row on desktop should STACK into a
      single column on mobile.
    - Make sure nothing overflows or gets cut off on a narrow
      screen.

  THINK ABOUT:
    - Which sections are naturally a ROW of items (good for flex/
      grid) and which are stacked?
    - What should change on a small screen - usually multi-column
      layouts collapse to a single column. That is what your media
      query handles.
    - Are your headings, body text, and buttons visually distinct
      and easy to read?


------------------------------------------------------------------
STEP 4  -  PREVIEW ON DESKTOP AND MOBILE
------------------------------------------------------------------
Open your page and check BOTH screen sizes:

  - Open "index.html": right-click it in the Explorer and choose
    "Open with Live Server" (if available), or open the file in a
    browser.
  - Check DESKTOP: the sections should be laid out cleanly with
    good spacing.
  - Check MOBILE: open the browser's device toolbar (press F12,
    then click the phone/tablet icon) OR just drag the window
    narrow. Confirm the layout adapts - multi-column areas should
    stack and text should stay readable, with no sideways
    scrolling.


------------------------------------------------------------------
STEP 5  -  CHECK YOUR WORK (run this before submitting!)
------------------------------------------------------------------
In the terminal, make sure you are inside your project folder:

    cd ai-generated-landing-page

Then copy and paste this whole block and press Enter:

----------------- COPY FROM HERE -----------------
echo "Checking your project..."
test -f index.html && echo "PASS: index.html exists" || echo "FAIL: index.html missing"
test -f style.css && echo "PASS: style.css exists" || echo "FAIL: style.css missing"
grep -q 'style.css' index.html && echo "PASS: style.css is linked in index.html" || echo "FAIL: style.css not linked in index.html"
grep -Eiq 'hero' index.html && echo "PASS: a hero section is present" || echo "FAIL: no 'hero' found in index.html"
grep -Eiq 'feature' index.html && echo "PASS: a features section is present" || echo "FAIL: no 'features' found in index.html"
grep -Eiq 'cta|call-to-action|call to action' index.html && echo "PASS: a CTA section is present" || echo "FAIL: no CTA section found in index.html"
grep -Eiq '<footer' index.html && echo "PASS: a footer is present" || echo "FAIL: no <footer> found in index.html"
grep -Eiq '<section|<header|<nav|<main|<article' index.html && echo "PASS: semantic HTML5 tags used" || echo "FAIL: no semantic tags (section/header/nav/main) found"
grep -Eiq 'display:[[:space:]]*flex|display:[[:space:]]*grid' style.css && echo "PASS: Flexbox and/or Grid used" || echo "FAIL: no flex/grid layout found in style.css"
grep -Eiq '@media' style.css && echo "PASS: a media query (responsive) is present" || echo "FAIL: no @media query found in style.css"
echo "Check complete."
------------------ TO HERE ------------------


------------------------------------------------------------------
HOW TO KNOW YOU PASSED
------------------------------------------------------------------
After running the check block, read the output carefully.

  - If EVERY line starts with "PASS:", your page has all the
    required pieces. You should see 10 PASS lines and no FAILs.

  - If ANY line starts with "FAIL:", that line tells you what is
    missing. For example:
        "FAIL: no CTA section found in index.html"
            -> add a call-to-action section (give it a class or id
               like "cta").
        "FAIL: no flex/grid layout found in style.css"
            -> use display: flex or display: grid for at least one
               part of your layout.
        "FAIL: no @media query found in style.css"
            -> add an @media rule so the layout adapts on small
               screens.

  IMPORTANT: These checks only confirm the required PIECES are
  present. They do NOT prove the page actually LOOKS good or is
  truly responsive. You MUST preview it (STEP 4) on both desktop
  and a narrow/mobile width and confirm it adapts cleanly.

  Fix whatever failed, save (Ctrl+S), and run the block again.
  Repeat until all 10 lines say PASS.


------------------------------------------------------------------
STEP 6  -  SUBMIT
------------------------------------------------------------------
  1. Make sure both files are SAVED (no white dots on tabs).
  2. Confirm the check block shows all PASS.
  3. Confirm the page looks good on desktop AND mobile (STEP 4).
  4. Write a README.md. If you used AI, include a short note on
     what it helped with (for example "AI suggested the app name,
     hero copy, and colour palette; I wrote all the HTML/CSS").
  5. Push to GitHub with MEANINGFUL commits (commit as you finish
     each section, with clear messages), and submit your repo link.

  TIP ON COMMITS: instead of one giant "done" commit, commit in
  steps - for example "add hero section", "add features grid",
  "add responsive media query". Clear history is part of the
  grade.


------------------------------------------------------------------
STRETCH GOALS (optional, once the basics pass)
------------------------------------------------------------------
  - Add a sticky navigation bar (look up "position: sticky").
  - Add subtle hover animations on cards/buttons (look up CSS
    "transition" and ":hover").
  - Improve accessibility: good colour contrast, alt text on
    images, and ARIA labels where they help.


------------------------------------------------------------------
COMMON PROBLEMS
------------------------------------------------------------------
  "Permission denied" creating the folder
      -> Run "pwd" and build inside the folder it shows.

  The CSS does not seem to apply
      -> Check the <link> to style.css in your HTML head, and make
         sure both files are in the SAME folder and SAVED.

  The page does not change on mobile
      -> Make sure you added a <meta name="viewport"> tag in the
         HTML head, and that your @media query uses a sensible
         width (for example max-width: 600px).

  Content scrolls sideways on a phone
      -> Something is wider than the screen. Avoid fixed pixel
         widths on big elements; use percentages or max-width, and
         let flex/grid wrap.

  Live Server is not available
      -> You can still just open index.html directly in a browser.
         Live Server only adds auto-reload, which is convenient but
         not required.

==================================================================
  END OF INSTRUCTIONS
==================================================================
