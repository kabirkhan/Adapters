# Possible data sources / adapters

## Twitter

**feasibility**: [manual download](https://twitter.com/settings/account) possible

**data format**: `JSON` (one file per month)

**content**: personal tweets/retweets, no responses, like-count, retweet-counts

## Facebook

**feasibility**: manual download possible

**data format**: `HTML` (easily parsable structure)

**content**: https://www.facebook.com/help/405183566203254

## LinkedIn

**feasibility**: [manual download](https://www.linkedin.com/psettings/member-data) possible

**data format**: `CSV` multiple files for each content type in .zip

**content**: profile info, skills, connections, education, positions, projects, messages, recommendations

## Google Fit

**feasibility**: [manual download](https://takeout.google.com/settings/takeout) possible

**data format**: individual tracks as `txc` (`xml`) and daily aggregates as `csv`, one file per track/day

**content**: GPS tracks, timestamps

> Start time,End time,Calories (kcal),Distance (m),Low latitude (deg),Low longitude (deg),High latitude (deg),High longitude (deg),Average speed (m/s),Max speed (m/s),Min speed (m/s),Step count,Average weight (kg),Max weight (kg),Min weight (kg),Inactive duration (ms),Walking duration (ms)

## Google Search

**feasibility**: [manual download](https://takeout.google.com/settings/takeout) possible

**data format**: `JSON` every 3 months

**content**: timestamp, search query

## Google Location History

**feasibility**: [manual download](https://takeout.google.com/settings/takeout) possible

**data format**: one giant `JSON`

I got `2033770` data points for ~6.5 years of data

**content**: timestamps, GPS positions+accuracy, activity (in vehicle, walking..)

## Runtastic

**feasibility**: ?

**data format**: ?

**content**: ?
