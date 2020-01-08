# Public Email Suffix List

An extension to the public suffix list to include email specific suffixes.

# Background

## The Public Suffix List (PSL)

A "public suffix" is one under which Internet users can (or historically could) directly register names. Some examples of public suffixes are .com, .co.uk and pvt.k12.ma.us. The Public Suffix List is a list of all known public suffixes.

See https://publicsuffix.org/ for more information.

## Problem

The public suffix list is an extensive list of visitable domain suffixes, but we deal with emails, not neccessarily visitable domains.

Some email service providers allow users to send emails from subdomains of their domain, for example .substack.com, .mailchimp.com & .convertkit.com. These don't represent actual websites, just email domains, so the PSL has no need for them.

However, we need to know these suffixes in order to associate their Subscription Scores with the correct domain.
