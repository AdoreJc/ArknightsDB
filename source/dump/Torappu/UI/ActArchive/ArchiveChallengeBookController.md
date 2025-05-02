# ArchiveChallengeBookController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveChallengeBookListDataBinder _chaosDataBinder`


## Properties

- `ArchiveChallengeBookListDataBinder dataBinder`


## Methods

- `Void set_onItemClicked(Action`2)`

- `ArchiveChallengeBookListDataBinder get_dataBinder()`

- `Void <>xLuaBaseProxy_OnItemClick(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveChallengeBookController : ActArchiveController
{
	private ArchiveChallengeBookListDataBinder _chaosDataBinder; // 0x38
	private Action`2 <onItemClicked>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_dataBinder; // 0x10
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`2 onItemClicked { get; set; }
	public ArchiveChallengeBookListDataBinder dataBinder { get; }

	// RVA: 0x303d32c VA: 0x759565532c
	private Action`2 get_onItemClicked() { }
	// RVA: 0x303d394 VA: 0x7595655394
	public Void set_onItemClicked(Action`2 value) { }
	// RVA: 0x303d418 VA: 0x7595655418
	public ArchiveChallengeBookListDataBinder get_dataBinder() { }
	// RVA: 0x303d480 VA: 0x7595655480
	public override Void OnItemClick(String storyId) { }
	// RVA: 0x303d53c VA: 0x759565553c
	public Void .ctor() { }
	// RVA: 0x303d5ac VA: 0x75956555ac
	private Void <>xLuaBaseProxy_OnItemClick(String P0) { }
}
```