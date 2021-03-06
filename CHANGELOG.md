1.4.0
=====
* Update to support use with Rails 5.0.0 RCs
* Improved data included in the DeliveryException
* Support for Recipient-Specific data

1.3.0
=====
* Convert to raising a StandardError rather than Exception
* Support for inline_css functionality (thanks to @daniilsunyaev)
* Support for html-only emails when using inline-content.

1.2.0
=====

* Transactional flag support
* IP Pool support
* Skip Suppression support
* Start Time (scheduled / delayed generation) support
* Support for setting the Description of a transmission
* Support for setting additional header info
* Bug fix on name vs. URL for inline images

1.1.0
=====

* Sandbox mode support
* CC support
* BCC support
* File Attachments
* Inline Images
* Transmission-specific handling of open_tracking, click_tracking, return_path, campaign_id, sandbox mode
* Support for substitution data
* Support for templates
* Support for recipient lists


1.0.1
=====

* Initial release of gem
* Full test suite + Travis CI integration for repo
* To, From, Reply-To support. 
* Subject, single, and multi-part (text & html) content support
