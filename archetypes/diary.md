---
title: "{{ replace .Name "-" " " | title }}" # Generates title from filename
date: {{ .Date }} # Sets the date of creation - CRUCIAL for timeline
draft: true # Start as draft
summary: "A brief summary of this diary entry..." # Optional but useful for list views
tags: ["Personal", "Development"] # Example tags
# Add any other custom front matter you might want, e.g.:
# mood: "Reflective"
# featured_image: "/images/diary/entry-image.jpg"
---

Start writing your diary entry here... Use Markdown!

You can include headings, lists, **bold text**, images, and even shortcodes like the YouTube or button ones.

<!-- Optional: Use Hugo's summary divider -->
<!--more-->

More detailed content goes here if you use the summary divider.