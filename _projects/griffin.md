---
layout: page
title: "Griffin"
description: "A tiny chess solver via computational decision optimisation (via page description)"
github: "https://github.com/mrvlabs/griffin"
categories: chess thinking optimisation
---

For a given standard board, with any given combination of pieces, and any given positions, calculate:
- The squares controlled exclusively by the black pieces;
- The squares controlled exclusively by the white pieces;
- The squares that are disputed;
- The squares that are controlled by neither;
- The material score for each of the black and white pieces;
- The "territory" score for each of the black and white pieces (1 point for a controlled and undisputed square, 0.5 points for a disputed square)
  - A square occupied by a piece counts as controlled and undisputed if the piece is not under threat; and as disputed if occupied with the piece under threat)
  - Do we need a special case for check? (idea here is a check effectively limits the exercise of the "estate")

<a href="{{ page.github }}">View Github Repository</a>
