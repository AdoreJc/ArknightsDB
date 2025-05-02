# StageMixStoryActOtherLineView

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `GameObject _inPanel`

- `GameObject _outPanel`

- `GameObject _classifiedPanel`

- `GameObject _normalPanel`

- `Image _storylineAbbrImage`

- `Text _storylineNameText`

- `UIDynImage _storySetTitleImage`

- `Single _width`

- `Single _followingSpacing`

- `UIStateFinder m_finder`

- `StageStorylineStorySetLocationViewModel m_cachedModel`

- `String m_cachedAbbrImageId`

- `String m_cachedTitleImageId`


## Methods

- `Void OnClickEvent()`

- `Void _Render(StageStorylineStorySetLocationViewModel)`

- `Void _SetEffectStatus(StageStorylineStorySetLocationViewModel)`

- `Void _RenderTitleOrClassified(StageStorylineStorySetLocationViewModel, StageStorylineStorySetViewModel)`

- `Void _RenderStorylineNameAndAbbr(StageStorylineViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryActOtherLineView : StageMixStoryLocationItem`1
{
	private GameObject _inPanel; // 0x20
	private GameObject _outPanel; // 0x28
	private GameObject _classifiedPanel; // 0x30
	private GameObject _normalPanel; // 0x38
	private Image _storylineAbbrImage; // 0x40
	private Text _storylineNameText; // 0x48
	private UIDynImage _storySetTitleImage; // 0x50
	private Single _width; // 0x58
	private Single _followingSpacing; // 0x5c
	private UIStateFinder m_finder; // 0x60
	private StageStorylineStorySetLocationViewModel m_cachedModel; // 0x70
	private String m_cachedAbbrImageId; // 0x78
	private String m_cachedTitleImageId; // 0x80
	private static DelegateBridge __Hotfix0_OnClickEvent; // 0x0
	private static DelegateBridge __Hotfix0_OnSetInfo; // 0x8
	private static DelegateBridge __Hotfix0__Render; // 0x10
	private static DelegateBridge __Hotfix0__SetEffectStatus; // 0x18
	private static DelegateBridge __Hotfix0__RenderTitleOrClassified; // 0x20
	private static DelegateBridge __Hotfix0__RenderStorylineNameAndAbbr; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2fe4714 VA: 0x75955fc714
	public Void OnClickEvent() { }
	// RVA: 0x2fe48c4 VA: 0x75955fc8c4
	public override Void OnSetInfo(StageStorylineStorySetLocationViewModel storySetLocation) { }
	// RVA: 0x2fe4968 VA: 0x75955fc968
	private Void _Render(StageStorylineStorySetLocationViewModel storySetLocation) { }
	// RVA: 0x2fe4a48 VA: 0x75955fca48
	private Void _SetEffectStatus(StageStorylineStorySetLocationViewModel storySetLocation) { }
	// RVA: 0x2fe4b00 VA: 0x75955fcb00
	private Void _RenderTitleOrClassified(StageStorylineStorySetLocationViewModel storySetLocation, StageStorylineStorySetViewModel storySet) { }
	// RVA: 0x2fe4c3c VA: 0x75955fcc3c
	private Void _RenderStorylineNameAndAbbr(StageStorylineViewModel storyline) { }
	// RVA: 0x2fe4d58 VA: 0x75955fcd58
	public Void .ctor() { }
}
```