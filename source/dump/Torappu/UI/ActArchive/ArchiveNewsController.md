# ArchiveNewsController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveNewsListDataBinder _newsListBinder`

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
public class ArchiveNewsController : ActArchiveController
{
	private ArchiveNewsListDataBinder _newsListBinder; // 0x38
	private Image _imgBkg; // 0x40
	private Image _imgTitle; // 0x48
	public Action`2 onNewsItemClicked; // 0x50
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x0
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinders; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_Show; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30635ec VA: 0x759567b5ec
	public override Void OnItemClick(String funcId) { }
	// RVA: 0x3063690 VA: 0x759567b690
	public List`1 InitAndAchieveDataBinders() { }
	// RVA: 0x3063848 VA: 0x759567b848
	public override Void Init(ActArchiveProxy proxy) { }
	// RVA: 0x3063a40 VA: 0x759567ba40
	public override IEnumerator Show(Boolean fastMode) { }
	// RVA: 0x3063b30 VA: 0x759567bb30
	public Void .ctor() { }
	// RVA: 0x3063ba0 VA: 0x759567bba0
	private Void <>xLuaBaseProxy_OnItemClick(String P0) { }
	// RVA: 0x3063ba8 VA: 0x759567bba8
	private Void <>xLuaBaseProxy_Init(ActArchiveProxy P0) { }
	// RVA: 0x3063bb0 VA: 0x759567bbb0
	private IEnumerator <>xLuaBaseProxy_Show(Boolean P0) { }
}
```