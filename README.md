# oneclick
RFC for non-interactive email unsubscription via http

> This document describes a simplified method for signaling "One-Click"
> functionality for HTTPS URIs as they appear in email headers.  The
> need for this arises out of the fact, that third-party entities
> involved in the processing of emails sometimes unintendedly trigger
> actions that are subject to the user and shall not be triggered
> automatically without an user's intent.

## Build requirements

Install [xml2rfc](http://xml2rfc.ietf.org).

Run

    xml2rfc draft-herkula-oneclick.xml
    
