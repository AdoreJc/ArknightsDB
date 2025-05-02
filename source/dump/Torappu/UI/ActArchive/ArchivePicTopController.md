# ArchivePicTopController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchivePicContentDataBinder _picContentBinder`

- `Image _imgBkg`

- `CanvasGroup _bgPanelCanvas`

- `CanvasGroup _itemCanvas`

- `RectTransform _backBtn`

- `Sequence m_sequence`


## Methods

- `Void OnPicClicked()`

- `Void ShowAnim()`

- `Void HideAnim()`

- `Void <ShowAnim>b__10_0()`

- `Void <HideAnim>b__11_0()`

- `Void <>xLuaBaseProxy_Init(ActArchiveProxy)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchivePicTopController : ActArchiveTopController
{
	private ArchivePicContentDataBinder _picContentBinder; // 0x30
	private Image _imgBkg; // 0x38
	private CanvasGroup _bgPanelCanvas; // 0x40
	private CanvasGroup _itemCanvas; // 0x48
	private RectTransform _backBtn; // 0x50
	public Action`1 onFullscreenToggled; // 0x58
	public Sequence m_sequence; // 0x60
	private static DelegateBridge __Hotfix0_OnPicClicked; // 0x0
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinders; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_ShowAnim; // 0x18
	private static DelegateBridge __Hotfix0_HideAnim; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x306d8b8 VA: 0x75956858b8
	public Void OnPicClicked() { }
	// RVA: 0x3069df0 VA: 0x7595681df0
	public List`1 InitAndAchieveDataBinders() { }
	// RVA: 0x306d940 VA: 0x7595685940
	public override Void Init(ActArchiveProxy proxy) { }
	// RVA: 0x306a724 VA: 0x7595682724
	public Void ShowAnim() { }
	// RVA: 0x306a918 VA: 0x7595682918
	public Void HideAnim() { }
	// RVA: 0x306db7c VA: 0x7595685b7c
	public Void .ctor() { }
	// RVA: 0x306dbec VA: 0x7595685bec
	private Void <ShowAnim>b__10_0() { }
	// RVA: 0x306dc14 VA: 0x7595685c14
	private Void <HideAnim>b__11_0() { }
	// RVA: 0x306dc3c VA: 0x7595685c3c
	private Void <>xLuaBaseProxy_Init(ActArchiveProxy P0) { }
}
```