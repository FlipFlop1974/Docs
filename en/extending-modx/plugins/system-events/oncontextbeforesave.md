---
title: "OnContextBeforeSave"
_old_id: "414"
_old_uri: "2.x/developing-in-modx/basic-development/plugins/system-events/oncontextbeforesave"
---

## Event: OnContextBeforeSave

Happens right before a context is saved.

- Service: 2 - Manager Access Events

## Event Parameters

| Name    | Description                                                                                                                            |
| ------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| context | A reference to the modContext object.                                                                                                  |
| mode    | Either 'new' (modSystemEvent::MODE\_NEW) or 'upd' (modSystemEvent::MODE\_UPD) depending on whether is a new object or an existing one. |

## See Also

- [System Events](extending-modx/plugins/system-events "System Events")
- [Plugins](extending-modx/plugins "Plugins")
