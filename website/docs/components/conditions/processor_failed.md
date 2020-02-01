---
title: processor_failed
type: condition
---

<!--
     THIS FILE IS AUTOGENERATED!

     To make changes please edit the contents of:
     lib/condition/processor_failed.go
-->


```yaml
processor_failed:
  part: 0
```

Returns true if a processing stage of a message has failed. This condition is
useful for dropping failed messages or creating dead letter queues, you can read
more about these patterns [here](/docs/configuration/error_handling).

