name: 🐛 Bug Report
description: Create a report to help us fix broken links or issues
title: "[BUG]: "
labels: ["bug"]
body:
  - type: textarea
    id: bug-description
    attributes:
      label: Bug Description
      description: A clear description of what the issue is (e.g., broken link in docs).
      placeholder: "The link to X certification in useful-links/certifications.md is returning a 404 error..."
    validations:
      required: true
