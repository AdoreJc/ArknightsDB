# StageMixStoryActView

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `GameObject _normalPanel`

- `GameObject _classifiedPanel`

- `Image _ssKvImage`

- `Color _ssKvInvalidColor`

- `Single _mainlineWidth`

- `Single _ssWidth`

- `Single _collectWidth`

- `UIAnimationLocation _validBlockAnimation`

- `UIAnimationLocation _invalidBlockAnimation`

- `UIStateFinder m_finder`

- `StageStorylineStorySetLocationViewModel m_cachedModel`


## Methods

- `Void OnClickEvent()`

- `Void _ToastLockedMsg(StageStorylineStorySetLocationViewModel)`

- `Void _OnMainlineClick(StageStorylineMainlineViewModel)`

- `Void _OnSsOrCollectClick(StageStorylineStorySetViewModel)`

- `Void OnSetInfo(StageStorylineStorySetLocationViewModel, Boolean)`

- `Void _Render(StageStorylineStorySetLocationViewModel, Boolean)`

- `Void _SetTypePanelStatus()`

- `Void _ClearIconViews()`

- `Void _RenderIconViews()`

- `Void _RenderPlugins()`

- `Void _RenderBlockStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryActView : StageMixStoryLocationItem`1
{
	private GameObject _normalPanel; // 0x20
	private GameObject _classifiedPanel; // 0x28
	private List`1 _typePanels; // 0x30
	private List`1 _pluginContainers; // 0x38
	private List`1 _iconViews; // 0x40
	private Image _ssKvImage; // 0x48
	private Color _ssKvInvalidColor; // 0x50
	private Single _mainlineWidth; // 0x60
	private Single _ssWidth; // 0x64
	private Single _collectWidth; // 0x68
	private UIAnimationLocation _validBlockAnimation; // 0x70
	private UIAnimationLocation _invalidBlockAnimation; // 0x80
	private UIStateFinder m_finder; // 0x90
	private StageStorylineStorySetLocationViewModel m_cachedModel; // 0xa0
	private static DelegateBridge __Hotfix0_OnClickEvent; // 0x0
	private static DelegateBridge __Hotfix0__ToastLockedMsg; // 0x8
	private static DelegateBridge __Hotfix0__OnMainlineClick; // 0x10
	private static DelegateBridge __Hotfix0__OnSsOrCollectClick; // 0x18
	private static DelegateBridge __Hotfix0_OnSetInfo; // 0x20
	private static DelegateBridge __Hotfix0__Render; // 0x28
	private static DelegateBridge __Hotfix0__SetTypePanelStatus; // 0x30
	private static DelegateBridge __Hotfix0__ClearIconViews; // 0x38
	private static DelegateBridge __Hotfix0__RenderIconViews; // 0x40
	private static DelegateBridge __Hotfix0__RenderPlugins; // 0x48
	private static DelegateBridge __Hotfix0__RenderBlockStatus; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2fe5058 VA: 0x75955fd058
	public Void OnClickEvent() { }
	// RVA: 0x2fe51dc VA: 0x75955fd1dc
	private Void _ToastLockedMsg(StageStorylineStorySetLocationViewModel location) { }
	// RVA: 0x2fe52cc VA: 0x75955fd2cc
	private Void _OnMainlineClick(StageStorylineMainlineViewModel mainline) { }
	// RVA: 0x2fe5480 VA: 0x75955fd480
	private Void _OnSsOrCollectClick(StageStorylineStorySetViewModel storySet) { }
	// RVA: 0x2fe55a4 VA: 0x75955fd5a4
	public Void OnSetInfo(StageStorylineStorySetLocationViewModel storySetLocation, Boolean isClassified) { }
	// RVA: 0x2fe5654 VA: 0x75955fd654
	private Void _Render(StageStorylineStorySetLocationViewModel storySetLocation, Boolean isClassified) { }
	// RVA: 0x2fe5874 VA: 0x75955fd874
	private Void _SetTypePanelStatus() { }
	// RVA: 0x2fe5740 VA: 0x75955fd740
	private Void _ClearIconViews() { }
	// RVA: 0x2fe5a58 VA: 0x75955fda58
	private Void _RenderIconViews() { }
	// RVA: 0x2fe5c7c VA: 0x75955fdc7c
	private Void _RenderPlugins() { }
	// RVA: 0x2fe5d78 VA: 0x75955fdd78
	private Void _RenderBlockStatus() { }
	// RVA: 0x2fe6038 VA: 0x75955fe038
	public Void .ctor() { }
}
```