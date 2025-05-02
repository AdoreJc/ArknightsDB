# ArchiveDynamicPicController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchivePicListDataBinder _picListBinder`

- `ArchivePicContentDataBinder _picContentBinder`

- `ArchiveDynamicPicFullscreenDataBinder _picFullscreenDataBinder`

- `Action onSetHomeKV`

- `Handler m_handler`


## Methods

- `Void set_onFullscreenToggled(Action`1)`

- `Void OnPicClicked()`

- `Void OnSetHomeKV()`

- `Void <>xLuaBaseProxy_OnItemClick(String)`

- `Void <>xLuaBaseProxy_Init(ActArchiveProxy)`

- `IEnumerator <>xLuaBaseProxy_Show(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveDynamicPicController : ActArchiveController
{
	private ArchivePicListDataBinder _picListBinder; // 0x38
	private ArchivePicContentDataBinder _picContentBinder; // 0x40
	private ArchiveDynamicPicFullscreenDataBinder _picFullscreenDataBinder; // 0x48
	public Action onSetHomeKV; // 0x50
	public Action`2 onPicItemClicked; // 0x58
	private Action`1 m_onFullscreenToggled; // 0x60
	private Handler m_handler; // 0x68
	private static DelegateBridge __Hotfix0_get_onFullscreenToggled; // 0x0
	private static DelegateBridge __Hotfix0_set_onFullscreenToggled; // 0x8
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x10
	private static DelegateBridge __Hotfix0_OnPicClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnSetHomeKV; // 0x20
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinders; // 0x28
	private static DelegateBridge __Hotfix0_Init; // 0x30
	private static DelegateBridge __Hotfix0_Show; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Action`1 onFullscreenToggled { get; set; }

	// RVA: 0x30678cc VA: 0x759567f8cc
	public Action`1 get_onFullscreenToggled() { }
	// RVA: 0x3067934 VA: 0x759567f934
	public Void set_onFullscreenToggled(Action`1 value) { }
	// RVA: 0x3067a70 VA: 0x759567fa70
	public override Void OnItemClick(String funcId) { }
	// RVA: 0x3067b00 VA: 0x759567fb00
	public Void OnPicClicked() { }
	// RVA: 0x3067ba0 VA: 0x759567fba0
	public Void OnSetHomeKV() { }
	// RVA: 0x3067c24 VA: 0x759567fc24
	public List`1 InitAndAchieveDataBinders() { }
	// RVA: 0x3068104 VA: 0x7595680104
	public override Void Init(ActArchiveProxy proxy) { }
	// RVA: 0x3068258 VA: 0x7595680258
	public override IEnumerator Show(Boolean fastMode) { }
	// RVA: 0x3068348 VA: 0x7595680348
	public Void .ctor() { }
	// RVA: 0x30683b8 VA: 0x75956803b8
	private Void <>xLuaBaseProxy_OnItemClick(String P0) { }
	// RVA: 0x30683c0 VA: 0x75956803c0
	private Void <>xLuaBaseProxy_Init(ActArchiveProxy P0) { }
	// RVA: 0x30683c8 VA: 0x75956803c8
	private IEnumerator <>xLuaBaseProxy_Show(Boolean P0) { }
}
```