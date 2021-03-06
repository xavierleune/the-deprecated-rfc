===== Introduction =====

When a feature is deprecated its date of removal is not defined.
One can argue that it will be dropped as the next major release, another will assume that he has several years to
react (but how much?), in truth no one can say for sure: “it will be dropped in php X.X“. As a result, removal may arrive unexpectly for some people and  RFC’s like this one
https://wiki.php.net/rfc/remove_deprecated_functionality_in_php7 are written. In our opinion, this  RFC should have been an upshot of php 7, not an RFC.


===== Proposal =====

Let’s define  a written in stone deprecation rule like: “a feature marked as deprecated will be remove in next major release”.

===== What we win =====

* Removal of deprecated features are automatically in the roadmap of the next major version
* No time loss in debating whether the deprecated should be removed now or postponed sine die. (A deprecated is flagged for removal for that version of php when it became deprecated, end of question)
* PHP user may anticpate actively and adapt is codebase on time instead of procrastinating.


===== Wild World Examples =====

* From the django project, deprecation policy https://docs.djangoproject.com/en/dev/internals/release-process/#internal-release-deprecation-policy
* From the django project again, deprecation timeline https://docs.djangoproject.com/en/dev/internals/deprecation/
