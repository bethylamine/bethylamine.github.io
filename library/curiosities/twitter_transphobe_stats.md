---
layout: default
title: Twitter transphobe stats
parent: Curiosities
permalink: /library/whatisawomanbot/twitter_transphobe_stats
---

# Twitter Transphobe Stats

The following data comes from a data set of 52,401 Twitter accounts marked in one way or another as transphobic. The data set can be downloaded here:

* [soupcan.csv](https://github.com/bethylamine/bethylamine.github.io/files/11606395/soupcan.csv)

Important note: the join date is not accurate, because it only shows the month and year on twitter. So do not use the day value, it is arbitrary (set to the day the script was run.)

## TLDR

* This dataset tracks about **34K** relatively active transphobe accounts.
* 1 in 3 accounts with a valid location in their bio were from the UK, and 2 in 5 were from the USA.
* Proportional to the userbase size by location, that means UK accounts were 3.8x more likely to be transphobic than their USA counterparts.
* Most (72%) transphobes have less followers than the number of people they are following.
* One third (34%) of transphobes have fewer than 200 followers.
* 60% of tweets from these users came from accounts with < 1K followers.
* `man` showed up in 880 screen names, `tra` in 627, `fem` in 521, `girl` in 146, `terf` in 145, `radfem` in 119, `truth` in 104, `gender` in 100, `feminist` in 92, `witch` in 79
  * Note that these are not always by themselves, e.g. `tra` could show up in `@contrapoints`.

## All the nitty-gritty details

355 (0.7%) accounts are suspended and 1,016 (1.9%) accounts are non-existent (e.g. renamed, or account deleted.) The rest of the analysis
will be only on the 50,815 active accounts with follower/following counts available.

Activity refers to the date of the second tweet that shows up in their "replies tab" (skips over pinned tweets) whether it came from them
or was a retweet.

* 67.3% (2 in 3) had activity in the last week (7 days)
* 85.9% (6 in 7) had activity in the last year (since this day last year.)
* Median Following is 725 (half transphobes follow less, half follow more)
* The transphobe with the most following is [@PAMsLOvE](https://twitter.com/PAMsLOvE) at 534K following.
* Median Followers is 435 (half transphobes have less followers, half have more)
* The transphobe with the most followers is [@elonmusk](https://twitter.com/elonmusk) with ~141M followers
* 34% of transphobes (1 in 3) have fewer than 200 followers.
* ~72% of transphobes have less followers than they're following.
* ~14% of transphobes follow 5x more people than they have following them.
* 20 accounts had transgender slurs in them.
* The number of tweets combined for all these accounts is 307,418,809
* 60.5% of those tweets came from accounts with under 1,000 followers
* 12.9% of those tweets came from accounts with under 200 followers
* Half of the accounts tweeted at least twice per day
* The most common n-grams:
  * ...of length 14: `adulthumanfem1` with 5 and `gendercritical` with 5
  * ...of length 13: `superstraight` with 37 occurrences
  * ...of length 11 but not mentioned above: `conservativ` with 17 occurrences
  * ...of length 10 but not mentioned above: `adulthuman` with 21 occurrences
  * ..of length 8 but not mentioned above: `feminist` with 92 occurrences
  * ..of length 5 but not mentioned above: `woman` (141), `women` (128), `trans` (100)
  * ..of length 6 but not mentioned above: `patrio` (125), `radfem` (119)
  * ..of length 4 but not mentioned above: `ther` (376), `real` (364), `ight` (335) and `john` (324)
  * ..of length 3: `the` (1924), `and` (1360), `mar` (1165), `ter` (1129) and `ell` (1058)
* Of the 26,657 profiles with location information in the bio,
  * Locations were validated with <https://wiki.openstreetmap.org/wiki/Nominatim>.
  * 22,159 (83.1%) locations were matched to a geographical location. Of these locations,
    * 8466 were in the US (38.2%)
    * 7830 were in the UK (35.3%)
  * Using [statistics about the number of Twitter users by country](https://www.oberlo.com/statistics/number-of-twitter-users-by-country),
    we can see that people with a UK location are 3.8x more likely to be reported as a transphobe than people with a US location.
  * Users in the UK made up 56,421,466 tweets (18.4%)
  * Users in the US made up 69,195,140 tweets (22.5%)
  * Meaning the UK users in this data set on average tweeted 1.54x more than the US users in this data set
