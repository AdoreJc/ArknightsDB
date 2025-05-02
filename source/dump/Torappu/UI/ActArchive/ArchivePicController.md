# ArchivePicController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchivePicListDataBinder _picListBinder`

- `ArchivePicContentDataBinder _picContentBinder`

- `ArchivePicFullscreenDataBinder _picFullscreenDataBinder`

- `Image _imgBkg`

- `Image _imgTitle`

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
public class ArchivePicController : ActArchiveController
{
	private ArchivePicListDataBinder _picListBinder; // 0x38
	private ArchivePicContentDataBinder _picContentBinder; // 0x40
	private ArchivePicFullscreenDataBinder _picFullscreenDataBinder; // 0x48
	private Image _imgBkg; // 0x50
	private Image _imgTitle; // 0x58
	public Action onSetHomeKV; // 0x60
	public Action`2 onPicItemClicked; // 0x68
	private Action`1 m_onFullscreenToggled; // 0x70
	private Handler m_handler; // 0x78
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

	// RVA: 0x3069760 VA: 0x7595681760
	public Action`1 get_onFullscreenToggled() { }
	// RVA: 0x30697c8 VA: 0x75956817c8
	public Void set_onFullscreenToggled(Action`1 value) { }
	// RVA: 0x3069904 VA: 0x7595681904
	public override Void OnItemClick(String funcId) { }
	// RVA: 0x3069994 VA: 0x7595681994
	public Void OnPicClicked() { }
	// RVA: 0x3069a34 VA: 0x7595681a34
	public Void OnSetHomeKV() { }
	// RVA: 0x3069ab8 VA: 0x7595681ab8
	public List`1 InitAndAchieveDataBinders() { }
	// RVA: 0x3069f0c VA: 0x7595681f0c
	public override Void Init(ActArchiveProxy proxy) { }
	// RVA: 0x306a274 VA: 0x7595682274
	public override IEnumerator Show(Boolean fastMode) { }
	// RVA: 0x306a364 VA: 0x7595682364
	public Void .ctor() { }
	// RVA: 0x306a3d4 VA: 0x75956823d4
	private Void <>xLuaBaseProxy_OnItemClick(String P0) { }
	// RVA: 0x306a3dc VA: 0x75956823dc
	private Void <>xLuaBaseProxy_Init(ActArchiveProxy P0) { }
	// RVA: 0x306a3e4 VA: 0x75956823e4
	private IEnumerator <>xLuaBaseProxy_Show(Boolean P0) { }
}
```