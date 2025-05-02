# SiracusaMapStageStoryPreviewView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `Text _txtStageName`

- `Text _txtStageCode`

- `Text _txtAvgType`

- `Text _txtAvgDesc`

- `ScrollRect _scrollBriefAvgDesc`

- `CanvasGroup _storyPreviewCanvasGroup`

- `Boolean m_isInited`

- `String m_cachedStoryId`

- `SiracusaMapStageDetailInfoViewModel m_cachedViewModel`

- `SiracusaMapStageDetailInfoViewModel m_sharedDetailInst`

- `UISwitchTween m_previewFadeTween`


## Properties

- `UISwitchTween previewFadeTween`


## Methods

- `UISwitchTween get_previewFadeTween()`

- `Void set_eventPlayStory(Action`1)`

- `Void _InitIfNot()`

- `Void _Render(SiracusaMapStageDetailInfoViewModel)`

- `Void OnStartPlayStory()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapStageStoryPreviewView : DataBinder`1
{
	private Text _txtStageName; // 0x20
	private Text _txtStageCode; // 0x28
	private Text _txtAvgType; // 0x30
	private Text _txtAvgDesc; // 0x38
	private ScrollRect _scrollBriefAvgDesc; // 0x40
	private CanvasGroup _storyPreviewCanvasGroup; // 0x48
	private Boolean m_isInited; // 0x50
	private String m_cachedStoryId; // 0x58
	private SiracusaMapStageDetailInfoViewModel m_cachedViewModel; // 0x60
	private SiracusaMapStageDetailInfoViewModel m_sharedDetailInst; // 0x68
	private UISwitchTween m_previewFadeTween; // 0x70
	private Action`1 <eventPlayStory>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_previewFadeTween; // 0x0
	private static DelegateBridge __Hotfix0_get_eventPlayStory; // 0x8
	private static DelegateBridge __Hotfix0_set_eventPlayStory; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__Render; // 0x20
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x28
	private static DelegateBridge __Hotfix0_OnStartPlayStory; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private UISwitchTween previewFadeTween { get; }
	public Action`1 eventPlayStory { get; set; }

	// RVA: 0x23e3aec VA: 0x75949fbaec
	private UISwitchTween get_previewFadeTween() { }
	// RVA: 0x23e3bc8 VA: 0x75949fbbc8
	public Action`1 get_eventPlayStory() { }
	// RVA: 0x23e3c30 VA: 0x75949fbc30
	public Void set_eventPlayStory(Action`1 value) { }
	// RVA: 0x23e3cb4 VA: 0x75949fbcb4
	private Void _InitIfNot() { }
	// RVA: 0x23e3d28 VA: 0x75949fbd28
	private Void _Render(SiracusaMapStageDetailInfoViewModel stageModel) { }
	// RVA: 0x23e3f08 VA: 0x75949fbf08
	public override Void OnValueChanged(SiracusaMapPanelMapProperty property) { }
	// RVA: 0x23e4048 VA: 0x75949fc048
	public Void OnStartPlayStory() { }
	// RVA: 0x23e40f0 VA: 0x75949fc0f0
	public Void .ctor() { }
}
```