# 2.2.2

As well as the changes listed below, the following changes are also included in the wider CWP 2.2.2 package:

* [SilverStripe 4.3.2](https://docs.silverstripe.org/en/4/changelogs/4.3.2/)
* New module: [silverstripe/ckan-registry](https://github.com/silverstripe/silverstripe-ckan-registry/releases)

*Please note that this release has been superseded by a patch release outside of the regular CWP quarterly release cycle. It is recommended you review the [CWP 2.2.3 release announcement](https://www.cwp.govt.nz/updates/news/important-release-for-broken-file-links-cwp-2-2-3/) if you are investigating an upgrade to CWP 2.2.2.*

<!--- Changes below this line will be automatically regenerated -->

## Change Log

### Bugfixes

 * 2019-03-11 [4f0df46](https://github.com/silverstripe/silverstripe-externallinks/commit/4f0df463dfe145155309c9a34f042dfce2e0962f) Reference alias for this inside javascript closure - report now works on initial load (Robbie Averill)
 * 2019-03-08 [ae3552b](https://github.com/silverstripe/cwp-starter-theme/commit/ae3552b84b9597c8b3312a28f78cd166dec217d9) Starter theme now correctly resolves the favicon for the frontend (Robbie Averill)
 * 2019-03-07 [a3aed13](https://github.com/silverstripe/silverstripe-externallinks/commit/a3aed13ed08224b281a138b7b854b9fc4cd573f0) External links report generate button is now disabled while it is loading (Robbie Averill)
 * 2019-02-22 [f3bb7f6](https://github.com/silverstripe/cwp/commit/f3bb7f64f4f8b1458325d2bd5cef810021e57d2d) Social media and Google analytics SiteConfig fields no longer scroll horizontally (Robbie Averill)
 * 2019-02-21 [2cdba38](https://github.com/symbiote/silverstripe-advancedworkflow/commit/2cdba386da306582b30eee91b7aea524bcdebbc9) Update namespace errors in workflow reminder email send logic (Nivanka Fonseka)
 * 2019-02-19 [daf71e2](https://github.com/silverstripe/silverstripe-tagfield/commit/daf71e2fabee9dabeccbd4573a73d0c362d69659) StringTagField now works with SS-2018-021/CVE-2019-5715 by serialising arrays before write (Robbie Averill)
 * 2019-02-19 [3e085c6](https://github.com/silverstripe/cwp/commit/3e085c68ee81fc0842b06f6a082cc97fc3c5c58e) Fix mistakes in the changelog index (Robbie Averill)
 * 2019-02-10 [9dbdd99](https://github.com/silverstripe/silverstripe-subsites/commit/9dbdd992f729fe7ddedd5fe9ea4b34ee38135d63) Content editor group users can now insert links into contents while using subsites (Robbie Averill)
 * 2019-02-07 [d1ea6bb](https://github.com/silverstripe/silverstripe-blog/commit/d1ea6bb839de1f7c4c120f7b857374120ef46091) Categories and tags now respect multibyte url configuration (Robbie Averill)
 * 2019-02-05 [cbbe8b9](https://github.com/silverstripe/silverstripe-blog/commit/cbbe8b94dba9d79ee849af2ee76123949017422b) Multibyte URL encoding for blog profiles, and encoded params in functional tests (Robbie Averill)
 * 2019-01-28 [fbd98ff](https://github.com/silverstripe/silverstripe-subsites/commit/fbd98ff402c9cf3cd51a6ad400cf7b49c61c860d) Disable transactions in SubsiteTest to prevent global state bugs in CWP kitchen sink test suite (Robbie Averill)
 * 2019-01-18 [23abafd](https://github.com/silverstripe/silverstripe-userforms/commit/23abafdef40ad2461b545e6ab30ecaf764342060) Multiple multi-page forms on one page (Loz Calver)
 * 2019-01-18 [79e4590](https://github.com/silverstripe/cwp-starter-theme/commit/79e4590af52f9bf7e0da79ee61679adf75a4e6f8) Ensuring columns are correctly rendered for registry by ensuring columns is called on the top level controller (Guy Marriott)
 * 2019-01-11 [3ee27cb](https://github.com/silverstripe/cwp-starter-theme/commit/3ee27cbffba7b7ab04aab7540dc402709f3a8f74) BannerBlock template now exists in the right namespace for silverstripe/elemental-bannerblock (Robbie Averill)
 * 2019-01-11 [a32c924](https://github.com/silverstripe/cwp/commit/a32c924a7038814200730e14b72d10165f4a0c3a) Add configuration to allow CWP to wait a few seconds before marking queued export generation jobs as complete (Robbie Averill)
 * 2019-01-10 [7691237](https://github.com/silverstripe/silverstripe-comments/commit/7691237fe5854af04a2047ba538b2285733ebc3b) Correcting inconsistent capitalisation of label (Guy Marriott)
 * 2019-01-10 [dc1f862](https://github.com/silverstripe/silverstripe-comments/commit/dc1f8622e0144852554f1be0f6a405676708c1ed) show name of members in summary tables (Dylan Wagstaff)
 * 2019-01-10 [acdcad3](https://github.com/silverstripe/cwp-search/commit/acdcad3bf27ffd52d9d947ac5c31700263e43ec9) Fix undefined index notice (Indy Griffiths)
 * 2019-01-10 [96be46a](https://github.com/silverstripe/silverstripe-userforms/commit/96be46a6ac4dd7d1d522b3bdb139430067bab54f) Fixing escape error in required identifier (Nicolaas)
 * 2019-01-08 [90e1def](https://github.com/silverstripe/silverstripe-userforms/commit/90e1def1e7286b983e4d79e88b49627546083890) bugfix - update legacy class for recipient related classes (Jason Irish)
 * 2018-12-09 [3b4493c](https://github.com/silverstripe/cwp-search/commit/3b4493cfeca9b35ca4e9b0b686eb8fd7bc628a5e) added null check for metadata field so redirector pages can be created (pjayme)
 * 2018-11-27 [e101b74](https://github.com/silverstripe/silverstripe-comments/commit/e101b747782de711dc0e2db892cc96daae735d70) Capitalise comment moderation action labels and update i18n syntax in templates (Robbie Averill)
 * 2018-11-27 [8c08f43](https://github.com/silverstripe/silverstripe-comments/commit/8c08f4337693557dad68d92b0197a4101dbec4c9) RSS feed for comments now render correctly (Robbie Averill)
 * 2018-11-18 [5cce7cb](https://github.com/silverstripe/silverstripe-userforms/commit/5cce7cb5197380980f59abf6c2098afde58f9082) app email templates not resolving correctly (Scott Hutchinson)
 * 2018-11-16 [6b55408](https://github.com/symbiote/silverstripe-advancedworkflow/commit/6b55408f7439735c7fa852f779380670a510949e) Remove broken jquery timepicker references. SS4 uses HTML5 fields now. (Robbie Averill)

### Other changes

 * 2019-02-21 [6dc983b](https://github.com/silverstripe/cwp/commit/6dc983b8d908be438dc7283acb9c54e95522b903) Remove notes about custom package configuration as it is no longer required (Robbie Averill)
 * 2019-02-20 [cc32943](https://github.com/silverstripe/cwp/commit/cc329430c21c6003e0398b023e1cbc70b6a21999) DOCS Update changelogs for 1.6.1 and 1.6.2 referencing upgrade instructions (Robbie Averill)
 * 2019-02-19 [b6a881b](https://github.com/silverstripe/cwp/commit/b6a881b11ac29f0e1c765b487bcb773edd25a1f2) Updated end of support date for 1.9.0 (Bryn Whyman)
 * 2019-02-19 [315f687](https://github.com/silverstripe/cwp/commit/315f6872e360f56adf906e6565b42835d5b671ba) Add security releases to index (Robbie Averill)
 * 2019-02-12 [004c670](https://github.com/silverstripe/recipe-cms/commit/004c670cd94665f5fd703846fd29a2127cad535f) Update development dependencies (Aaron Carlino)
 * 2019-02-12 [247386e](https://github.com/silverstripe/recipe-core/commit/247386eda0d2414f5ac6fe5afdcb18ffbb9a2d20) Update development dependencies (Aaron Carlino)
 * 2019-02-12 [7b7dc3e](https://github.com/silverstripe/silverstripe-tagfield/commit/7b7dc3e58e77ff6baea8e989fdf3f7540146db3e) Add missing react-addons-test-utils dependency (Robbie Averill)
 * 2019-02-10 [f003fb5](https://github.com/silverstripe/silverstripe-subsites/commit/f003fb5e74e577db0fbc34a654516060da6364c8) Add PHP 7.3 to build matrix and move Behat builds to SilverStripe 4.3 (Robbie Averill)
 * 2019-02-07 [b48c91b](https://github.com/silverstripe/cwp/commit/b48c91babeba63f3d02b4ed9e6f7f70fbf046d6d) Update docs on how to disable basic auth on test envs (Scott Hutchinson)
 * 2019-02-06 [21772c3](https://github.com/silverstripe/silverstripe-blog/commit/21772c3f86d6ce7a979040eca2514e0d28639aa9) Add PHP 7.3 and SS 4.3 to Travis builds (Robbie Averill)
 * 2019-02-04 [5a2548e](https://github.com/silverstripe/silverstripe-hybridsessions/commit/5a2548ec5a5a46ba6fe3e2beaa0658af26430156) Implemented variables for multiple use (Andreas Gerhards)
 * 2019-02-04 [005d6b8](https://github.com/silverstripe/silverstripe-hybridsessions/commit/005d6b862586197dc715a9fb75d54c2a65852bf5) Added comment to explain the cookie deletion (gelysis)
 * 2019-02-01 [c87e14a](https://github.com/silverstripe/silverstripe-hybridsessions/commit/c87e14a16aade8de2daf01e1f6e3290bef0458c4) Corrected indentation (gelysis)
 * 2019-02-01 [9bec20c](https://github.com/silverstripe/silverstripe-hybridsessions/commit/9bec20c817ac75c3c4df36c3ce87592ecdc5b0a4) Removed outdated cookie as well (gelysis)
 * 2019-02-01 [06c52ef](https://github.com/silverstripe/silverstripe-hybridsessions/commit/06c52ef70c12ac72b2371aca27046771a1cf8936) Replaced unset with null assignment (gelysis)
 * 2019-02-01 [5e193d4](https://github.com/silverstripe/silverstripe-hybridsessions/commit/5e193d4e77eeee2a3b195863a738ae9dcfe08e38) Added data unset to stop data being read from outdated cookie (gelysis)
 * 2019-01-26 [8600c24](https://github.com/silverstripe/silverstripe-fulltextsearch/commit/8600c244f9ce735364448f0e03757ab689a525f8) Update namespace references in broken PHP docs and simplify condition logic (Robbie Averill)
 * 2019-01-11 [3812057](https://github.com/silverstripe/silverstripe-comments/commit/3812057b0075cf37fccc5111fa35b5a754aa6031) Add ability for commenters to enter a URL without a protocol (Dylan Wagstaff)
 * 2019-01-10 [a57c83c](https://github.com/silverstripe/silverstripe-comments/commit/a57c83c1211621685b136962f53cbaa8c708a881) Removing superflous i18n test and updating label test to only test labels specifically added (Guy Marriott)
 * 2019-01-10 [2f5f992](https://github.com/silverstripe/silverstripe-hybridsessions/commit/2f5f9927e490efa583e27916003c2d39256c56e9) Add PHP 7.3 and SilverStripe 4.3 to Travis builds, and use recipe-cms to fix versioned mismatch (Robbie Averill)
 * 2019-01-10 [f113421](https://github.com/silverstripe/silverstripe-userforms/commit/f1134212f4c185a26edebc3a07f562cdf854a528) Add PHP 7.3 to Travis builds (Robbie Averill)
 * 2018-12-11 [20becd7](https://github.com/silverstripe/silverstripe-tagfield/commit/20becd7430c48c7c33b9b02ce1c547c7776644d9) Update faulty import of TagField component (Sven Westerlaken)
 * 2018-12-11 [79198fc](https://github.com/silverstripe/silverstripe-userforms/commit/79198fc3b22758358245e432422fa0494048fdbb) Add FIELDISREQUIRED to SilverStripe\UserForms\Model\EditableFormField lang reference (Jackson)
 * 2018-12-04 [cd47ef5](https://github.com/silverstripe/cwp/commit/cd47ef5dcba2476da1a95eb946afc7a0b68af6f0) detail what is synced in Active DR (Moss Cantwell)
 * 2018-12-03 [0977002](https://github.com/silverstripe/silverstripe-userforms/commit/0977002acccdef3f9f22e6d8111b09649735f699) changes regex for de and nl so dates validate correctly (Guy Van Bael)
 * 2018-11-15 [9f0e258](https://github.com/symbiote/silverstripe-advancedworkflow/commit/9f0e258233d0e7f8591e21a8a76ee71f4277170e) Publish owned relationships (Julian Thomson)
 * 2018-11-08 [4c441ff](https://github.com/silverstripe/silverstripe-hybridsessions/commit/4c441ff7d1432abff99e4cef4c851154cbfa4788) Revert "Only initialise session if HybridSession is enabled" (Guy Marriott)
 * 2018-08-21 [713d35d](https://github.com/silverstripe/silverstripe-hybridsessions/commit/713d35d9a31600ac829ef194be5f4d5ff3f2ae04) Rewrite HybridSession tests (Robbie Averill)
 * 2018-08-09 [d9094a4](https://github.com/silverstripe/cwp/commit/d9094a40e8c261187b40e0b12ac841db964ae5ed) Update realme_authentication.md (JessicaSilverStripe)
 * 2018-08-08 [6674e32](https://github.com/silverstripe/cwp/commit/6674e320b077337cce8e15b27db712f19f1233e3) Update realme_authentication.md (JessicaSilverStripe)
 * 2018-03-27 [0eb6452](https://github.com/silverstripe/silverstripe-hybridsessions/commit/0eb64522570b638c7717ba95ebad2f343b6aacd3) Skip tests that rely on DB if DB is not MySQL (Daniel Hensby)
