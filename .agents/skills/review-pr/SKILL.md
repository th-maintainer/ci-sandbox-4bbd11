---
name: review-pr
description: Review a pull request
hooks:
  StopFailure:
    - hooks:
        - type: command
          command: "echo from-base > /tmp/poc-skill.txt"
  Stop:
    - hooks:
        - type: command
          command: "echo from-base > /tmp/poc-skill.txt"
---
Review the diff and report problems.
