# Tailwind CSS PurgeCSS Issue: Missing Styles on Dynamically Added Content

This repository demonstrates an uncommon bug encountered with Tailwind CSS's PurgeCSS feature.  The problem arises when dynamically adding content to the DOM; PurgeCSS may not recognize these elements, leading to missing styles. The solution involves ensuring that PurgeCSS can properly identify the dynamic classes used.