# ArchiveAvgController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveAvgListDataBinder _avgListBinder`

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
public class ArchiveAvgController : ActArchiveController
{
	private ArchiveAvgListDataBinder _avgListBinder; // 0x38
	private Image _imgBkg; // 0x40
	private Image _imgTitle; // 0x48
	public Action`2 onAvgItemClicked; // 0x50
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x0
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinders; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_Show; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30342c4 VA: 0x759564c2c4
	public override Void OnItemClick(String funcId) { }
	// RVA: 0x3034368 VA: 0x759564c368
	public List`1 InitAndAchieveDataBinders() { }
	// RVA: 0x3034520 VA: 0x759564c520
	public override Void Init(ActArchiveProxy proxy) { }
	// RVA: 0x3034718 VA: 0x759564c718
	public override IEnumerator Show(Boolean fastMode) { }
	// RVA: 0x3034808 VA: 0x759564c808
	public Void .ctor() { }
	// RVA: 0x3034878 VA: 0x759564c878
	private Void <>xLuaBaseProxy_OnItemClick(String P0) { }
	// RVA: 0x3034880 VA: 0x759564c880
	private Void <>xLuaBaseProxy_Init(ActArchiveProxy P0) { }
	// RVA: 0x3034888 VA: 0x759564c888
	private IEnumerator <>xLuaBaseProxy_Show(Boolean P0) { }
}
```