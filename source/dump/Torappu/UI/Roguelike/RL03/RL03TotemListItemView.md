# RL03TotemListItemView

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `GameObject _panelEmpty`

- `GameObject _panelItem`

- `Text _txtTotemName`

- `Image _imgTotemIcon`

- `Image _imgTotemBg`

- `GameObject _panelTotemOutline`

- `GameObject _panelSubBuff`

- `UIAtlasImage _imgSubBuff`

- `GameObject _panelDivinationBkg`

- `GameObject _panelDivination`

- `Text _txtTotemDesc`

- `GameObject _panelUnselectable`

- `Button _btnItem`

- `UIAtlasObject _uiAtlasObject`

- `UIAnimationLocation _selectAnim`

- `Single _preferSize`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `AnimationSwitchTween m_selectSwitchTween`

- `RL03TotemListItemViewModel m_itemViewModel`

- `Int32 m_cacheIndex`


## Methods

- `Void Render(RL03TotemListItemVirtualViewStruct)`

- `Void UpdateSelectStatus(RL03TotemListItemViewModel, List`1, Int32)`

- `Void EventOnItemClick()`

- `Void _InitIfNot()`

- `Void _RenderBaseInfo(RL03TotemListItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TotemListItemView : MonoBehaviour, IHotfixable
{
	private GameObject _panelEmpty; // 0x18
	private GameObject _panelItem; // 0x20
	private Text _txtTotemName; // 0x28
	private Image _imgTotemIcon; // 0x30
	private Image _imgTotemBg; // 0x38
	private GameObject _panelTotemOutline; // 0x40
	private Graphic[] _graphicsWithColor; // 0x48
	private GameObject _panelSubBuff; // 0x50
	private UIAtlasImage _imgSubBuff; // 0x58
	private GameObject _panelDivinationBkg; // 0x60
	private GameObject _panelDivination; // 0x68
	private Text _txtTotemDesc; // 0x70
	private GameObject _panelUnselectable; // 0x78
	private Button _btnItem; // 0x80
	private UIAtlasObject _uiAtlasObject; // 0x88
	private UIAnimationLocation _selectAnim; // 0x90
	private Single _preferSize; // 0xa0
	private Boolean m_isInited; // 0xa4
	private UIPageFinder m_pageFinder; // 0xa8
	private AnimationSwitchTween m_selectSwitchTween; // 0xb8
	private Action`2 m_onclick; // 0xc0
	private List`1 m_groupSelectStatusList; // 0xc8
	private RL03TotemListItemViewModel m_itemViewModel; // 0xd0
	private Int32 m_cacheIndex; // 0xd8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_UpdateSelectStatus; // 0x8
	private static DelegateBridge __Hotfix0_EventOnItemClick; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__RenderBaseInfo; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2bae778 VA: 0x75951c6778
	public Void Render(RL03TotemListItemVirtualViewStruct viewStruct) { }
	// RVA: 0x2baef34 VA: 0x75951c6f34
	public Void UpdateSelectStatus(RL03TotemListItemViewModel viewModel, List`1 groupSelectStatusList, Int32 viewIndex) { }
	// RVA: 0x2baf0d0 VA: 0x75951c70d0
	public Void EventOnItemClick() { }
	// RVA: 0x2bae8c8 VA: 0x75951c68c8
	private Void _InitIfNot() { }
	// RVA: 0x2baead0 VA: 0x75951c6ad0
	private Void _RenderBaseInfo(RL03TotemListItemViewModel itemViewModel) { }
	// RVA: 0x2baf4a8 VA: 0x75951c74a8
	public Void .ctor() { }
}
```