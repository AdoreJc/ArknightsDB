# ArchiveDynamicPicTopController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchivePicContentDataBinder _picContentBinder`

- `CanvasGroup _bgPanelCanvas`

- `CanvasGroup _itemCanvas`

- `RectTransform _backBtn`

- `Sequence m_sequence`


## Methods

- `Void OnPicClicked()`

- `Void ShowAnim()`

- `Void HideAnim()`

- `Void <ShowAnim>b__9_0()`

- `Void <HideAnim>b__10_0()`

- `Void <>xLuaBaseProxy_Init(ActArchiveProxy)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveDynamicPicTopController : ActArchiveTopController
{
	private ArchivePicContentDataBinder _picContentBinder; // 0x30
	private CanvasGroup _bgPanelCanvas; // 0x38
	private CanvasGroup _itemCanvas; // 0x40
	private RectTransform _backBtn; // 0x48
	public Action`1 onFullscreenToggled; // 0x50
	public Sequence m_sequence; // 0x58
	private static DelegateBridge __Hotfix0_OnPicClicked; // 0x0
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinders; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_ShowAnim; // 0x18
	private static DelegateBridge __Hotfix0_HideAnim; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3068c98 VA: 0x7595680c98
	public Void OnPicClicked() { }
	// RVA: 0x3067fe8 VA: 0x759567ffe8
	public List`1 InitAndAchieveDataBinders() { }
	// RVA: 0x3068d20 VA: 0x7595680d20
	public override Void Init(ActArchiveProxy proxy) { }
	// RVA: 0x3068858 VA: 0x7595680858
	public Void ShowAnim() { }
	// RVA: 0x3068a4c VA: 0x7595680a4c
	public Void HideAnim() { }
	// RVA: 0x3068e3c VA: 0x7595680e3c
	public Void .ctor() { }
	// RVA: 0x3068eac VA: 0x7595680eac
	private Void <ShowAnim>b__9_0() { }
	// RVA: 0x3068ed4 VA: 0x7595680ed4
	private Void <HideAnim>b__10_0() { }
	// RVA: 0x3068efc VA: 0x7595680efc
	private Void <>xLuaBaseProxy_Init(ActArchiveProxy P0) { }
}
```