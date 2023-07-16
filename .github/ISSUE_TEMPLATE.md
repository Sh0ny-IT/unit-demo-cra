---
title: {{ env.GITHUB_REF_NAME }}
assignees: {{ env.GITHUB_ACTOR }}
labels: release
---

## Version
{{ env.GITHUB_REF_NAME }}

## time of changes
{{ env.TIME_OF_CHANGES }}

## test report
{{ env.TEST_REPORT }}

## author
{{ env.GITHUB_ACTOR }}
