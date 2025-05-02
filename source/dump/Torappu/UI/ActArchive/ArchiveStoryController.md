# ArchiveStoryController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveStoryListDataBinder _storyListBinder`

- `Image _imgBkg`

- `Image _imgTitle`


## Methods

- `Void <>xLuaBaseProxy_OnItemClick(String)`

- `Void <>xLuaBaseProxy_Init(ActArchiveProxy)`

- `IEnumerator <>xLuaBaseProxy_Show(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveStoryController : ActArchiveController
{
	private ArchiveStoryListDataBinder _storyListBinder; // 0x38
	private Image _imgBkg; // 0x40
	private Image _imgTitle; // 0x48
	public Action`2 onStoryItemClicked; // 0x50
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x0
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinders; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_Show; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x307f8c8 VA: 0x75956978c8
	public override Void OnItemClick(String funcId) { }
	// RVA: 0x307f96c VA: 0x759569796c
	public List`1 InitAndAchieveDataBinders() { }
	// RVA: 0x307fb24 VA: 0x7595697b24
	public override Void Init(ActArchiveProxy proxy) { }
	// RVA: 0x307fcb8 VA: 0x7595697cb8
	public override IEnumerator Show(Boolean fastMode) { }
	// RVA: 0x307fda8 VA: 0x7595697da8
	public Void .ctor() { }
	// RVA: 0x307fe18 VA: 0x7595697e18
	private Void <>xLuaBaseProxy_OnItemClick(String P0) { }
	// RVA: 0x307fe20 VA: 0x7595697e20
	private Void <>xLuaBaseProxy_Init(ActArchiveProxy P0) { }
	// RVA: 0x307fe28 VA: 0x7595697e28
	private IEnumerator <>xLuaBaseProxy_Show(Boolean P0) { }
}
```