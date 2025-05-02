# ArchiveDynamicStoryController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveDynamicStoryListDataBinder _storyListBinder`


## Methods

- `Void <>xLuaBaseProxy_OnItemClick(String)`

- `IEnumerator <>xLuaBaseProxy_Show(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveDynamicStoryController : ActArchiveController
{
	private ArchiveDynamicStoryListDataBinder _storyListBinder; // 0x38
	public Action`2 onStoryItemClicked; // 0x40
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x0
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinders; // 0x8
	private static DelegateBridge __Hotfix0_Show; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x307e1f8 VA: 0x75956961f8
	public override Void OnItemClick(String funcId) { }
	// RVA: 0x307e29c VA: 0x759569629c
	public List`1 InitAndAchieveDataBinders() { }
	// RVA: 0x307e454 VA: 0x7595696454
	public override IEnumerator Show(Boolean fastMode) { }
	// RVA: 0x307e544 VA: 0x7595696544
	public Void .ctor() { }
	// RVA: 0x307e5b4 VA: 0x75956965b4
	private Void <>xLuaBaseProxy_OnItemClick(String P0) { }
	// RVA: 0x307e5bc VA: 0x75956965bc
	private IEnumerator <>xLuaBaseProxy_Show(Boolean P0) { }
}
```