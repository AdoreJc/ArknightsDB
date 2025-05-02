# ArchiveQuestTopController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveQuestCgContentDataBinder _cgContentBinder`

- `CanvasGroup _bgPanelCanvas`

- `CanvasGroup _itemCanvas`

- `RectTransform _backBtn`

- `Sequence m_sequence`


## Methods

- `Void OnCgClicked()`

- `Void ShowAnim()`

- `Void HideAnim()`

- `Void <ShowAnim>b__10_0()`

- `Void <HideAnim>b__11_0()`

- `Void <>xLuaBaseProxy_Init(ActArchiveProxy)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveQuestTopController : ActArchiveTopController
{
	private ArchiveQuestCgContentDataBinder _cgContentBinder; // 0x30
	private CanvasGroup _bgPanelCanvas; // 0x38
	private CanvasGroup _itemCanvas; // 0x40
	private RectTransform _backBtn; // 0x48
	public Action`1 onFullscreenToggled; // 0x50
	public Sequence m_sequence; // 0x58
	private static DelegateBridge __Hotfix0_OnCgClicked; // 0x0
	private static DelegateBridge __Hotfix0_get_dataBinder; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_ShowAnim; // 0x18
	private static DelegateBridge __Hotfix0_HideAnim; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public DataBinder`1 dataBinder { get; }

	// RVA: 0x30776c0 VA: 0x759568f6c0
	public Void OnCgClicked() { }
	// RVA: 0x307081c VA: 0x759568881c
	public DataBinder`1 get_dataBinder() { }
	// RVA: 0x3077748 VA: 0x759568f748
	public override Void Init(ActArchiveProxy proxy) { }
	// RVA: 0x3073ad4 VA: 0x759568bad4
	public Void ShowAnim() { }
	// RVA: 0x3073cc8 VA: 0x759568bcc8
	public Void HideAnim() { }
	// RVA: 0x3077864 VA: 0x759568f864
	public Void .ctor() { }
	// RVA: 0x30778d4 VA: 0x759568f8d4
	private Void <ShowAnim>b__10_0() { }
	// RVA: 0x30778fc VA: 0x759568f8fc
	private Void <HideAnim>b__11_0() { }
	// RVA: 0x3077924 VA: 0x759568f924
	private Void <>xLuaBaseProxy_Init(ActArchiveProxy P0) { }
}
```