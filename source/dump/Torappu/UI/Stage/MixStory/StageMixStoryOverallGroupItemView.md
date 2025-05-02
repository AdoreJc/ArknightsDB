# StageMixStoryOverallGroupItemView

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `UIAnimationLocation _validDarkenAnimation`

- `UIAnimationLocation _invalidDarkAnimation`

- `Single _mainlineWidth`

- `Single _ssWidth`

- `Single _collectWidth`

- `Boolean m_hasInited`

- `UIStateFinder m_stateFinder`

- `ILoadAsset m_iLoadAsset`

- `StageStorylineStorySetViewModel m_cachedModel`

- `Tween m_darkenTween`


## Methods

- `Void OnItemClickEvent()`

- `Void Render(StageStorylineStorySetViewModel, StageMixStoryOverallItemStateHandler)`

- `Single GetWidthOfType(StorylineStorySetType)`

- `Void _InitIfNeed()`

- `Void _FitSizeWithType()`

- `Void _SetTypePanelStatus()`

- `Void _RenderIconViews()`

- `Void _RenderFeaturePanels(StageMixStoryOverallItemStateHandler)`

- `Void _RenderPluginContainers(StageMixStoryOverallItemStateHandler)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryOverallGroupItemView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _validDarkenAnimation; // 0x18
	private UIAnimationLocation _invalidDarkAnimation; // 0x28
	private List`1 _typePanels; // 0x38
	private List`1 _iconViews; // 0x40
	private List`1 _featurePanels; // 0x48
	private List`1 _pluginContainers; // 0x50
	private Single _mainlineWidth; // 0x58
	private Single _ssWidth; // 0x5c
	private Single _collectWidth; // 0x60
	private Boolean m_hasInited; // 0x64
	private UIStateFinder m_stateFinder; // 0x68
	private ILoadAsset m_iLoadAsset; // 0x78
	private StageStorylineStorySetViewModel m_cachedModel; // 0x80
	private Tween m_darkenTween; // 0x88
	private static DelegateBridge __Hotfix0_OnItemClickEvent; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_GetWidthOfType; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNeed; // 0x18
	private static DelegateBridge __Hotfix0__FitSizeWithType; // 0x20
	private static DelegateBridge __Hotfix0__SetTypePanelStatus; // 0x28
	private static DelegateBridge __Hotfix0__RenderIconViews; // 0x30
	private static DelegateBridge __Hotfix0__RenderFeaturePanels; // 0x38
	private static DelegateBridge __Hotfix0__RenderPluginContainers; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2ff97a8 VA: 0x75956117a8
	public Void OnItemClickEvent() { }
	// RVA: 0x2ff9a44 VA: 0x7595611a44
	public Void Render(StageStorylineStorySetViewModel model, StageMixStoryOverallItemStateHandler itemStateHandler) { }
	// RVA: 0x2ffa4b0 VA: 0x75956124b0
	public Single GetWidthOfType(StorylineStorySetType type) { }
	// RVA: 0x2ff9bc8 VA: 0x7595611bc8
	private Void _InitIfNeed() { }
	// RVA: 0x2ff9c84 VA: 0x7595611c84
	private Void _FitSizeWithType() { }
	// RVA: 0x2ff9d94 VA: 0x7595611d94
	private Void _SetTypePanelStatus() { }
	// RVA: 0x2ff9f6c VA: 0x7595611f6c
	private Void _RenderIconViews() { }
	// RVA: 0x2ffa0b8 VA: 0x75956120b8
	private Void _RenderFeaturePanels(StageMixStoryOverallItemStateHandler itemStateHandler) { }
	// RVA: 0x2ffa1a4 VA: 0x75956121a4
	private Void _RenderPluginContainers(StageMixStoryOverallItemStateHandler itemStateHandler) { }
	// RVA: 0x2ffa8b4 VA: 0x75956128b4
	public Void .ctor() { }
}
```