#Changelog

This change log only contains major changes made after October 2016.

Non-major changes are editorial-only changes or minor changes of existing guidelines, e.g. adding new error code. Major changes are changes that come with additional obligations, or even change an existing guideline obligation. The latter changes are additionally labeled with "Rule Change" here.

To see a list of all changes, please have a look at the [commit list in Github](https://github.com/zalando/restful-api-guidelines/commits/master).

## Rule Changes

* `2017-04-24:` Added naming rules for hosts, permissions and events, old rule for event naming was removed
* `2017-03-30:` Added rule that permissions on resources in events must correspond to permissions on API resources
* `2017-03-30:` Added rule that APIs should be modelled around business processes
* `2017-02-28:` Extended information about how to reference sub-resources and the usage of composite identifiers in the [Resources](../resources/Resources.md#-bookmust--identify-resources-and-sub-resources-via-path-segments) part.
* `2017-02-22:` Added guidance for conditional requests with If-Match/If-None-Match
* `2017-02-02:` Added guideline for batch and bulk request
* `2017-02-01:` Discouraged use of [Content-Location](../headers/CommonHeaders.md#could-use-contentlocation-header) header by requiring to use [Location header](../headers/CommonHeaders.md#should-use-location-header-instead-of-contentlocation-header).
* `2017-01-18:` Removed "Avoid Javascript Keywords" rule
* `2017-01-05:` Clarification on the usage of the term "REST/RESTful"
* `2016-12-07:` Introduced "API as a Product" principle
* `2016-12-06:` New guideline: "Should Only Use UUIDs If Necessary"
* `2016-12-04:` Changed OAuth flow example from implicit to password in [Security section](../security/Security.md).
* `2016-10-13:` [Officially deprecated using custom media types instead of application/json](../data-formats/DataFormats.md#should-prefer-standard-media-type-name-applicationjson).
* `2016-10-10:` Introduced the changelog. From now on all rule changes on API guidelines will be recorded here.
