---
title: Frequently Asked Questions
date: 2025-06-10
layout: single
faqs:
  - question: Why propose a new platform?
    answer: To better reflect the values and priorities of Utah County Republicans in 2025.
  - question: How can I provide feedback?
    answer: Comment on plank pages or contact the party directly via our official channels.
---
# FAQ

{{ range .Params.faqs }}
### {{ .question }}
{{ .answer }}
{{ end }}