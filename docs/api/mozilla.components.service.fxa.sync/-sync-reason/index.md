[android-components](../../index.md) / [mozilla.components.service.fxa.sync](../index.md) / [SyncReason](./index.md)

# SyncReason

`sealed class SyncReason` [(source)](https://github.com/mozilla-mobile/android-components/blob/master/components/service/firefox-accounts/src/main/java/mozilla/components/service/fxa/sync/SyncManager.kt#L22)

A collection of objects describing a reason for running a sync.

### Types

| Name | Summary |
|---|---|
| [EngineChange](-engine-change.md) | `object EngineChange : `[`SyncReason`](./index.md)<br>User changed enabled/disabled state of one or more [SyncEngine](../../mozilla.components.service.fxa/-sync-engine/index.md)s. |
| [Startup](-startup.md) | `object Startup : `[`SyncReason`](./index.md)<br>Application is starting up, and wants to sync data. |
| [User](-user.md) | `object User : `[`SyncReason`](./index.md)<br>User is requesting a sync (e.g. pressed a "sync now" button). |

### Extension Functions

| Name | Summary |
|---|---|
| [loadResourceAsString](../../mozilla.components.support.test.file/kotlin.-any/load-resource-as-string.md) | `fun `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`.loadResourceAsString(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Loads a file from the resources folder and returns its content as a string object. |

### Inheritors

| Name | Summary |
|---|---|
| [EngineChange](-engine-change.md) | `object EngineChange : `[`SyncReason`](./index.md)<br>User changed enabled/disabled state of one or more [SyncEngine](../../mozilla.components.service.fxa/-sync-engine/index.md)s. |
| [Startup](-startup.md) | `object Startup : `[`SyncReason`](./index.md)<br>Application is starting up, and wants to sync data. |
| [User](-user.md) | `object User : `[`SyncReason`](./index.md)<br>User is requesting a sync (e.g. pressed a "sync now" button). |
