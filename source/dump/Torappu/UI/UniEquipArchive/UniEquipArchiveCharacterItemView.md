# UniEquipArchiveCharacterItemView

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `Image _avatar`

- `Image _prof`

- `Image _elite`

- `Text _level`

- `Text _name`

- `Image _rarity`

- `GameObject _panelEquip`

- `GameObject _panelEquipDisable`

- `GameObject _panelStarMark`

- `UICommonTrackPoint _trackpoint`

- `SimpleLayoutContent _equipContent`

- `UIWrappedScrollRect _scrollRect`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `UIStateFinder m_stateFinder`

- `UIPageFinder m_pageFinder`

- `UniEquipArchiveCharacterItemViewModel m_cachedViewModel`


## Properties

- `UIWrappedScrollRect scrollRect`


## Methods

- `UIWrappedScrollRect get_scrollRect()`

- `Void _InitIfNot()`

- `Void Render(UniEquipArchiveCharacterItemViewModel)`

- `Void OnUniEquipClick()`

- `Void OnUniEquipCharClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveCharacterItemView : MonoBehaviour, IHotfixable
{
	private Image _avatar; // 0x18
	private Image _prof; // 0x20
	private Image _elite; // 0x28
	private Text _level; // 0x30
	private Text _name; // 0x38
	private Image _rarity; // 0x40
	private GameObject _panelEquip; // 0x48
	private GameObject _panelEquipDisable; // 0x50
	private GameObject _panelStarMark; // 0x58
	private UICommonTrackPoint _trackpoint; // 0x60
	private SimpleLayoutContent _equipContent; // 0x68
	private UIWrappedScrollRect _scrollRect; // 0x70
	private Boolean m_isInited; // 0x78
	private Adapter m_adapter; // 0x80
	private UIStateFinder m_stateFinder; // 0x88
	private UIPageFinder m_pageFinder; // 0x98
	private UniEquipArchiveCharacterItemViewModel m_cachedViewModel; // 0xa8
	private static DelegateBridge __Hotfix0_get_scrollRect; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnUniEquipClick; // 0x18
	private static DelegateBridge __Hotfix0_OnUniEquipCharClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public UIWrappedScrollRect scrollRect { get; }

	// RVA: 0x22eb380 VA: 0x7594903380
	public UIWrappedScrollRect get_scrollRect() { }
	// RVA: 0x22eb8c8 VA: 0x75949038c8
	private Void _InitIfNot() { }
	// RVA: 0x22eb0d8 VA: 0x75949030d8
	public Void Render(UniEquipArchiveCharacterItemViewModel data) { }
	// RVA: 0x22eba2c VA: 0x7594903a2c
	public Void OnUniEquipClick() { }
	// RVA: 0x22ebb58 VA: 0x7594903b58
	public Void OnUniEquipCharClick() { }
	// RVA: 0x22ebc84 VA: 0x7594903c84
	public Void .ctor() { }
}
```