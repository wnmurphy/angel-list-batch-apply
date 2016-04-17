Angel List Batch Apply
====================

# Overview

This is a script which applies to every single startup in your Angel List search results with a single click.

It leverages jQuery, which is already loaded as a site dependency.

Obviously, it's going to be more effective for your job search to apply directly through the company website, and even more effective to go through a referral or recruiter.

This script is not a substitute for an actual application, and Angel List tends to have a low response rate precisely because it's so easy to 'apply' (express interest).

## Configuring:

To set up this script:

- Replace `customNote` with your own note.
- Comment out lines 69-70, and 74-76.
- Uncomment line 65 to log your custom notes and check syntax and formatting.

## Usage:

To run this script:

- Go to [Angel List's job search](https://angel.co/jobs).
- Enter your filtering criteria and search.
- Open the console.
- Paste this script and run it.
- The page may appear to hang. Let it be.

I believe Angel List has a rate-limiting feature, as well as intermittent 'call-to-action' buttons throughout the search results which interrupt the script, so you may need to run multiple times.