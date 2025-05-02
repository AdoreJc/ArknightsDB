# SkipBriefPanel

**Namespace:** `Torappu.AVG`


## Fields

- `Text _chapterName`

- `Text _title`

- `Text _avgTag`

- `Text _content`

- `GameObject _nonBriefPanel`

- `GameObject _briefPanel`

- `Action _onConfirm`

- `CanvasGroup m_canvasGroup`

- `FadeSwitchTween m_skipBriefTween`


## Properties

- `CanvasGroup canvasGroup`

- `FadeSwitchTween fadeSwitchTween`

- `Boolean isShown`


## Methods

- `Void Reset()`

- `Void RenderBriefSkip(String, String, String, String)`

- `Void RenderNonBriefSkip()`

- `CanvasGroup get_canvasGroup()`

- `FadeSwitchTween get_fadeSwitchTween()`

- `Void _UpdateShown(Boolean, Boolean)`

- `Boolean get_isShown()`

- `Void set_isShown(Boolean)`

- `Void OnCloseBtnClicked()`

- `Void OnConfirmBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class SkipBriefPanel : MonoBehaviour, IHotfixable
{
	private Text _chapterName; // 0x18
	private Text _title; // 0x20
	private Text _avgTag; // 0x28
	private Text _content; // 0x30
	private GameObject _nonBriefPanel; // 0x38
	private GameObject _briefPanel; // 0x40
	public Action _onConfirm; // 0x48
	private CanvasGroup m_canvasGroup; // 0x50
	private FadeSwitchTween m_skipBriefTween; // 0x58
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0_RenderBriefSkip; // 0x8
	private static DelegateBridge __Hotfix0_RenderNonBriefSkip; // 0x10
	private static DelegateBridge __Hotfix0_get_canvasGroup; // 0x18
	private static DelegateBridge __Hotfix0_get_fadeSwitchTween; // 0x20
	private static DelegateBridge __Hotfix0__UpdateShown; // 0x28
	private static DelegateBridge __Hotfix0_get_isShown; // 0x30
	private static DelegateBridge __Hotfix0_set_isShown; // 0x38
	private static DelegateBridge __Hotfix0_OnCloseBtnClicked; // 0x40
	private static DelegateBridge __Hotfix0_OnConfirmBtnClicked; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private CanvasGroup canvasGroup { get; }
	private FadeSwitchTween fadeSwitchTween { get; }
	public Boolean isShown { get; set; }

	// RVA: 0x3e8d4a0 VA: 0x75964a54a0
	public Void Reset() { }
	// RVA: 0x3e8d590 VA: 0x75964a5590
	public Void RenderBriefSkip(String chapterName, String title, String avgTag, String content) { }
	// RVA: 0x3e8d798 VA: 0x75964a5798
	public Void RenderNonBriefSkip() { }
	// RVA: 0x3e8d824 VA: 0x75964a5824
	private CanvasGroup get_canvasGroup() { }
	// RVA: 0x3e8d8fc VA: 0x75964a58fc
	private FadeSwitchTween get_fadeSwitchTween() { }
	// RVA: 0x3e8d9c8 VA: 0x75964a59c8
	private Void _UpdateShown(Boolean value, Boolean force) { }
	// RVA: 0x3e8da98 VA: 0x75964a5a98
	public Boolean get_isShown() { }
	// RVA: 0x3e8d50c VA: 0x75964a550c
	public Void set_isShown(Boolean value) { }
	// RVA: 0x3e8db10 VA: 0x75964a5b10
	public Void OnCloseBtnClicked() { }
	// RVA: 0x3e8dba8 VA: 0x75964a5ba8
	public Void OnConfirmBtnClicked() { }
	// RVA: 0x3e8dc44 VA: 0x75964a5c44
	public Void .ctor() { }
}
```