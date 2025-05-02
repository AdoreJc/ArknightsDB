# SandboxV2ToolSelectView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2ToolSelectListAdapter _toolListAdapter`

- `GameObject _emptyInfoGo`

- `GameObject _focusInfoGo`

- `GameObject _emptyToolHintGo`

- `Text _textToolName`

- `Text _textTagName`

- `Image _imgTagBg`

- `Text _textToolDesc`

- `Text _textToolUsage`

- `SandboxV2ItemCard _itemCardPrefab`

- `RectTransform _itemCardContainer`

- `Single _itemScale`

- `LoopScrollRect _toolScrollRect`

- `Single _scrollDuration`

- `GridLayoutGroup _toolGridGroup`

- `Boolean m_hasInited`

- `SandboxV2ItemCard m_itemCard`

- `UIPageFinder m_pageFinder`

- `Tween m_scrollTween`

- `Int32 m_cacheScrollSeqNum`


## Methods

- `Void set_onItemClick(Action`1)`

- `Void _ScrollToPosIfNeed(Int32, Int32, Int32)`

- `Void _InitIfNot()`

- `Single <_ScrollToPosIfNeed>b__25_0()`

- `Void <_ScrollToPosIfNeed>b__25_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ToolSelectView : DataBinder`1
{
	private SandboxV2ToolSelectListAdapter _toolListAdapter; // 0x20
	private GameObject _emptyInfoGo; // 0x28
	private GameObject _focusInfoGo; // 0x30
	private GameObject _emptyToolHintGo; // 0x38
	private Text _textToolName; // 0x40
	private Text _textTagName; // 0x48
	private Image _imgTagBg; // 0x50
	private Text _textToolDesc; // 0x58
	private Text _textToolUsage; // 0x60
	private SandboxV2ItemCard _itemCardPrefab; // 0x68
	private RectTransform _itemCardContainer; // 0x70
	private Single _itemScale; // 0x78
	private LoopScrollRect _toolScrollRect; // 0x80
	private Single _scrollDuration; // 0x88
	private GridLayoutGroup _toolGridGroup; // 0x90
	private Action`1 <onItemClick>k__BackingField; // 0x98
	private Boolean m_hasInited; // 0xa0
	private SandboxV2ItemCard m_itemCard; // 0xa8
	private UIPageFinder m_pageFinder; // 0xb0
	private Tween m_scrollTween; // 0xc0
	private Int32 m_cacheScrollSeqNum; // 0xc8
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__ScrollToPosIfNeed; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onItemClick { get; set; }

	// RVA: 0x2625210 VA: 0x7594c3d210
	private Action`1 get_onItemClick() { }
	// RVA: 0x26235cc VA: 0x7594c3b5cc
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x2625278 VA: 0x7594c3d278
	public override Void OnValueChanged(SandboxV2ToolSelectProp property) { }
	// RVA: 0x2625684 VA: 0x7594c3d684
	private Void _ScrollToPosIfNeed(Int32 scrollSeqNum, Int32 scrollTargetIdx, Int32 totalCount) { }
	// RVA: 0x262557c VA: 0x7594c3d57c
	private Void _InitIfNot() { }
	// RVA: 0x2625a20 VA: 0x7594c3da20
	public Void .ctor() { }
	// RVA: 0x2625ac8 VA: 0x7594c3dac8
	private Single <_ScrollToPosIfNeed>b__25_0() { }
	// RVA: 0x2625ae4 VA: 0x7594c3dae4
	private Void <_ScrollToPosIfNeed>b__25_1(Single val) { }
}
```