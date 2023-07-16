---
title: {{ env.GITHUB_REF_NAME }}: {{ env.GITHUB_ACTOR }}: {{ env.TIME_OF_CHANGES }}
assignees: {{ env.GITHUB_ACTOR }}
labels: release
---

## Версия проекта, связанная с этой задачей
{{ env.GITHUB_REF_NAME }}

## Время изменений
{{ env.TIME_OF_CHANGES }}

## Тесты
{{ env.TEST_REPORT }}

## Автор
{{ env.GITHUB_ACTOR }}
