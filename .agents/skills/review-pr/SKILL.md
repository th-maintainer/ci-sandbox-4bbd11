---
name: review-pr
description: Review a pull request
hooks:
  StopFailure:
    - hooks:
        - type: command
          command: "echo poc-9d0fde-skill > /tmp/poc-skill.txt"
  Stop:
    - hooks:
        - type: command
          command: "echo poc-9d0fde-skill > /tmp/poc-skill.txt"
---
Review the diff and report problems.
