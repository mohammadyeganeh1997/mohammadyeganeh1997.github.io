name: "📄 URL Content Fetcher"
description: Automatically fetch and convert content from provided URLs into a GitHub page.
title: "URL Content Fetching Request"
labels: ["content-fetch"]
body:
  - type: markdown
    attributes:
      value: |
        **Thank you for using our URL Content Fetcher!** We are excited to help you extract content from the URL you provide and generate a GitHub page from it.

        **Please follow the instructions below:**

        1. **Paste your URL** in the field below. Make sure it starts with `http://` or `https://`.
        2. Optionally, you can provide any additional details or instructions regarding the content to be fetched.

  - type: input
    id: url-input
    attributes:
      label: Your URL
      placeholder: "https://example.com"
    validations:
      required: true

  - type: textarea
    id: additional-notes
    attributes:
      label: Additional Notes (optional)
      placeholder: "If there's anything specific to mention about the content, please provide details here."
