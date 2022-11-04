# DRF_Code_Snippet_Website
Django Application that allows users to CRUD code snippets/strings to a website.  Implements API authentication so that:
* Code snippets are always associated with a creator.
* Only authenticated users may create snippets.
* Only the creator of a snippet may update or delete it.
* Unauthenticated requests should have full read-only access.
