---
name: Rebilly
x-slug: rebilly
description: ""
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Alter
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/alter/master/_listings/rebilly/apis.md
specificationVersion: "0.14"
apis:
- name: Rebilly
  x-api-slug: rebilly
  description: -introductionthe-rebilly-api-is-built-on-http---our-api-is-restful---it-has-predictableresource-urls---it-returns-http-response-codes-to-indicate-errors---it-alsoaccepts-and-returns-json-in-the-http-body---you-can-use-your-favoritehttprest-library-for-your-programming-language-to-use-rebillys-api-oryou-can-use-one-of-our-sdks-currently-available-in-phphttpsgithub-comrebillyrebillyphpand-chttpsgithub-comrebillyrebillydotnetclient--authenticationwhen-you-sign-up-for-an-account-you-are-given-your-first-api-key-you-can-generate-additional-api-keys-and-delete-api-keys-as-you-mayneed-to-rotate-your-keys-in-the-future--you-authenticate-to-therebilly-api-by-providing-your-secret-key-in-the-request-header-rebilly-offers-three-forms-of-authentication--private-key-json-web-tokens-andpublic-key--private-key-authenticates-each-request-by-searching-for-the-presenceof-an-http-header-rebapikey--jwt-authenticates-each-request-by-the-http-header-authorization--public-key-authenticates-by-the-http-header-rebauth-read-more-on-this-below-rebilly-also-offers-json-web-tokens-jwt-authentication-where-you-can-controlthe-specific-granular-permissions-and-expiration-for-that-jwt---we-call-our-resourcefor-generating-jwt-sessionstagsessions-rebilly-also-has-a-clientside-authentication-scheme-that-uses-anapiuser-and-hmacsha1-signature-only-for-the-tokens-resource-sothat-you-may-safely-create-tokens-from-the-clientside-without-compromisingyour-secret-keys-never-share-your-secret-keys--keep-them-guarded-and-secure-the-clientside-authentication-scheme-uses-one-http-header-named-rebauth--redocinject-securitydefinitions--php-sdkfor-all-php-sdk-examples-provided-in-this-spec-you-will-need-to-configure-client-you-may-do-it-like-thisphpclient--new-rebillyclient----apikey--yourapikeyhere----baseurl--httpsapi-rebilly-com
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
  humanURL: https://www.rebilly.com
  baseURL: https://api.rebilly.com//v2.1
  tags: Billing, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/alter/master/_listings/rebilly/customfieldsresourcename-put-openapi.md
- name: Rebilly
  x-api-slug: rebilly
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
  humanURL: https://www.rebilly.com
  baseURL: https://api.rebilly.com//v2.1
  tags: Alter
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/alter/master/_listings/rebilly/openapi.md
x-common:
- type: x-website
  url: https://www.rebilly.com
- type: x-api-gallery
  url: http://rat.genome.database.api.gallery.streamdata.io
- type: x-api-stack
  url: http://rebilly.stack.network
- type: x-documentation
  url: https://rebilly.github.io/RebillyAPI/#
- type: x-github
  url: https://github.com/Rebilly
- type: x-license-agreement
  url: https://www.rebilly.com/api-license/
- type: x-openapi
  url: https://rebilly.github.io/RebillyAPI/swagger.json
- type: x-pricing
  url: https://www.rebilly.com/pricing/
- type: x-privacy-policy
  url: https://www.rebilly.com/privacy-policy/
- type: x-support
  url: https://help.rebilly.com/
- type: x-terms-of-service
  url: https://www.rebilly.com/terms-of-use/
- type: x-twitter
  url: https://twitter.com/RebillyInc
- type: x-website
  url: http://rebilly.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---