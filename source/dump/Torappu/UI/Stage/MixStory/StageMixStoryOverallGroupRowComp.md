# StageMixStoryOverallGroupRowComp

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `Single _height`

- `HorizontalLayoutGroup _layoutGroup`

- `SimpleLayoutContent _layoutContent`

- `StageMixStoryOverallGroupItemView _itemView`

- `Boolean m_hasInited`

- `Adapter m_adapter`


## Properties

- `RectOffset layoutPadding`

- `Single layoutSpacing`


## Methods

- `RectOffset get_layoutPadding()`

- `Single get_layoutSpacing()`

- `Single WidthOfStorySetItem(StorylineStorySetType)`

- `Void _Render(ViewModel, StageMixStoryOverallItemStateHandler)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryOverallGroupRowComp : MonoBehaviour, IHotfixable
{
	private Single _height; // 0x18
	private HorizontalLayoutGroup _layoutGroup; // 0x20
	private SimpleLayoutContent _layoutContent; // 0x28
	private StageMixStoryOverallGroupItemView _itemView; // 0x30
	private Boolean m_hasInited; // 0x38
	private Adapter m_adapter; // 0x40
	private static DelegateBridge __Hotfix0_get_layoutPadding; // 0x0
	private static DelegateBridge __Hotfix0_get_layoutSpacing; // 0x8
	private static DelegateBridge __Hotfix0_WidthOfStorySetItem; // 0x10
	private static DelegateBridge __Hotfix0__Render; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public RectOffset layoutPadding { get; }
	public Single layoutSpacing { get; }

	// RVA: 0x2ffab58 VA: 0x7595612b58
	public RectOffset get_layoutPadding() { }
	// RVA: 0x2ffabcc VA: 0x7595612bcc
	public Single get_layoutSpacing() { }
	// RVA: 0x2ffac40 VA: 0x7595612c40
	public Single WidthOfStorySetItem(StorylineStorySetType type) { }
	// RVA: 0x2ffacc8 VA: 0x7595612cc8
	private Void _Render(ViewModel model, StageMixStoryOverallItemStateHandler itemStateHandler) { }
	// RVA: 0x2ffad98 VA: 0x7595612d98
	private Void _InitIfNot() { }
	// RVA: 0x2ffafdc VA: 0x7595612fdc
	public Void .ctor() { }
}
```