---
layout: post
title: GSoC 25' Summary
subtitle: Thoughts and experience
gh-repo: Rdatatable/data.table
gh-badge: [star, fork, follow]
tags: [pr, contribution, gsoc2025]
comments: true
---

## Basic Info
- **Name**: Mukul Kumar
- **Email**: mukulrao6480@gmail.com
- **Github Username**: Mukulyadav2004
- **Mentors**: Toby Dylan Hocking, Anirban chetia, Joshua Wu
- **Project Title**: Enhancing data.table: Enhancing Functionality, and Ensuring
Quality
- **Project Link**: [data.table](https://github.com/Rdatatable/data.table)

### Work Summary

My contributions during this period centered on resolving key bugs, documentation and extending the functionality of the data.table package. Below is a summary of the work done:

| Issues | Pull Requests |
| :------ | :--- |
| [move from warning to breaking change in melt/dcast #6629](https://github.com/Rdatatable/data.table/issues/6629) | [#7266](https://github.com/Rdatatable/data.table/pull/7266) |
| [fcoalesce will not replace NaN with NA_real_ #4567](https://github.com/Rdatatable/data.table/issues/4567) | [#7189](https://github.com/Rdatatable/data.table/pull/7189) |
| [mistake in help text of ?data.table for with? #4955](https://github.com/Rdatatable/data.table/issues/4955) | [#7155](https://github.com/Rdatatable/data.table/pull/7155) |
| [Error on non scalar aggregates regardless of fill #7260](https://github.com/Rdatatable/data.table/pull/7260)| [#7263](https://github.com/Rdatatable/data.table/pull/7263) |
| [fwrite to gain select and drop column(s) arguments without creating a temporary object #4177](https://github.com/Rdatatable/data.table/issues/4177) | [#7236](https://github.com/Rdatatable/data.table/pull/7236) |
| [Error messages from merge() somewhat confusingly “swap” ‘x’ and ‘i’ prefixes #6641](https://github.com/Rdatatable/data.table/issues/6641) | [#7048](https://github.com/Rdatatable/data.table/pull/7048) |
| [move from warning to breaking change in melt/dcast #6629](https://github.com/Rdatatable/data.table/issues/6629)| [#7260](https://github.com/Rdatatable/data.table/pull/7260) |
| [groupingsets() wrong scoping logic #5560](https://github.com/Rdatatable/data.table/issues/5560) | [#6879](https://github.com/Rdatatable/data.table/pull/6879) |
| [Use classed conditions as often as possible #5913](https://github.com/Rdatatable/data.table/issues/5913) | [#7139](https://github.com/Rdatatable/data.table/pull/7139) |
| [data.table(keep.rownames = TRUE) should preserve names from vectors #1916](https://github.com/Rdatatable/data.table/issues/1916) | [#7136](https://github.com/Rdatatable/data.table/pull/7136) |
| [fread should raise an error instead of a warning when reading a gzipped file that does not fit in temporary storage #5415](https://github.com/Rdatatable/data.table/issues/5415) | [#7097](https://github.com/Rdatatable/data.table/pull/7097) |
| [List Of data.table Options #6720](https://github.com/Rdatatable/data.table/issues/6720) | [#7075](https://github.com/Rdatatable/data.table/pull/7075) |
| [first(named_vector) removes names #2487](https://github.com/Rdatatable/data.table/issues/2487) | [#7056](https://github.com/Rdatatable/data.table/pull/7056) |
| [first(x) not always the same as x[1] #2002](https://github.com/Rdatatable/data.table/issues/2002) | [#7056](https://github.com/Rdatatable/data.table/pull/7056) |
| [Add functionality to print column classes at bottom #6902](https://github.com/Rdatatable/data.table/issues/6902) | [#6905](https://github.com/Rdatatable/data.table/pull/6905) |
| [Error message for unspecified join gives incorrect advice on how to do a natural join #5455](https://github.com/Rdatatable/data.table/issues/5455) | [#6876](https://github.com/Rdatatable/data.table/pull/6876) |
| [Typo in vignette on reshaping #6855](https://github.com/Rdatatable/data.table/issues/6855) | [#6870](https://github.com/Rdatatable/data.table/pull/6870) |
| [Clarify behavior of first() and last() #7056](https://github.com/Rdatatable/data.table/pull/7056),| [#7061](https://github.com/Rdatatable/data.table/pull/7061) |
| [key(as.data.table(x, key = <key>)) is inconsistent, varies based on x #6859](https://github.com/Rdatatable/data.table/issues/6859) | [#6865](https://github.com/Rdatatable/data.table/pull/6865) |
| [print.data.table warns when options(datatable.show.indices=TRUE) and an index exists #6806](https://github.com/Rdatatable/data.table/issues/6806) | [#6816](https://github.com/Rdatatable/data.table/pull/6816) |


## **Overview**

Taking part in Google Summer of Code this year has been a truly increadible experience. I’m grateful to my mentor for trusting me with this project and for providing steady guidance throughout the journey. The program strengthened my technical skills and at the same time gave me the confidence to tackle complex problems and explore new areas of open-source development.

Balancing academics with GSoC was challenging at times, yet it turned into one of the most rewarding aspects of the experience. Dedicating evenings and weekends to the project taught me discipline, focus, and effective time management. The encouragement and flexibility I received from my mentor made it easier to stay consistent and motivated throughout the summer.

For me, GSoC has been much more than writing code—it has been a journey of growth, learning, and collaboration. I’ll continue to contribute in improving data.table project and to carry these lessons forward into future work.

## **Acknowledgments**

I would like to sincerely thank my mentors, Toby Dylan Hocking, Anirban Chetia and Joshua Wu for their guidance and support. Their patience, quick feedback, and insightful suggestions pushed me to think critically and improve the quality of my work. Many of the principles I learned from them have changed how I approach coding and problem-solving.

I’m also thankful to the data.table community for their generosity in sharing knowledge and offering constructive feedback. Their guidance helped me refine my contributions and gain a deeper understanding of the project.

Lastly, I want to appreciate my fellow GSoC contributor, working alongside such talented peers made this journey even more meaningful and enjoyable.
