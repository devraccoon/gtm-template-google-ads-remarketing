# gtm-template-google-ads-remarketing
Raccoon Google Ads Remarketing custom tag template


The official template for "Google Ads Remarketing" tag has a bug.

The official template was recently updated to support the new dynamic remkarketing events (reference1: https://support.google.com/google-ads/answer/3103357?hl=en, reference2: https://support.google.com/google-ads/answer/7305793), but this implementation has a bug: the "value" event parameter never get sent by the template.

This custom template mimics what the gtag snippet send to the network. We hope Google fix the problem on the official template in the next few months.