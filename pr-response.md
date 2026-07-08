# PR Response Doc — CineLog Watchlist Feature

## AI Usage
<!-- Fill in at the end — how you used AI tools during this project -->

## Comment 1 — Rename
**What I did:** Change the named of the function to add_to_watchlist to be consistent with the existing naming convention
**How I verified:** I used the VScode find and replace feature. I then ran the test suite to make sure everything passes.

## Comment 2 — Deduplication
**What I did:** I added a small block of code mirroring the collection service that checks for an existing id. If found, it raises an exception. 
**How I verified:** I used Postman to send duplicate video submissions and test the api.

## Comment 3 — Missing test
**What I did:** I created a new file and copied over the template code from test_collection.py. I think updated the function names to test the new watchlist functions. 
**How I verified:** I ran the test suite to see that everything is passing correctly.

## Comment 4 — Default visibility
**My position:**
**Reasoning:**
**Tradeoff acknowledged:**

## Comment 5 — Sort order
**My position:**
**Reasoning:**
**Engagement with reviewer's point:**

## Comment 6 — Rebase
**What conflicted:**
**How I resolved it:**
**How I verified no conflict remains:**

## PR Description
<!-- Written at the end — feature overview, design decisions, manual testing steps -->