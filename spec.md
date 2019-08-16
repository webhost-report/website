#Proposed spec for webhost.report
The idea of this is to provide the basics of how the system will function.

## What is webhost.report
A service populated with lists of site domains by website hosting providers to prevent sites using reverse proxy's to make it hard to report content that is illegal or stolen. The service will list a directory and search of domains in the system that each have a virtual page that can be search indexed by services like Google Search. This allows parties to search and find this service when in need of reporting a specific site.

## How will data be collected
A API call that all website hosting providers can push to. Each host on the list will get a key to use. Once a site is in the system it will stay only for 3 months before expiring and needing to be updated. The idea is nightly or any automated jobs that run per site hosted can make the request with no limits.

## What will the public see
A list of sites on the main site, and on a domain/site report page a little info mostly DNS collected on the spot and then a input field to make a report. The hosting provider will NOT be displayed to protect the hosting provider and the

## Other info in the list
We will also list and find sites using DNS info to find and forward reports on to the origin like Godaddy, CF, Squarespace as part of making this a global list. Just by providers putting in sites they don't need to get reports sent to proxy's like CF and then on to the Network provider.
