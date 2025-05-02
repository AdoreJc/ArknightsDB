# RhineArcTimelineItem

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `GameObject _unAvailPart`

- `GameObject _availPart`

- `GameObject _unAvailDot`

- `GameObject _unAvailFirstDot`

- `GameObject _availDot`

- `GameObject _newTrack`

- `GameObject _newTrackDot`

- `Text _id`

- `Text _name`

- `Image _itemIcon`

- `Image _itemSmallIcon`

- `UIAtlasImage _textBack`

- `UIAtlasImage _itemMask`

- `Single _lockTextBackAlpha`

- `Color _newMaskColor`

- `Color _unlockMaskColor`

- `Color _lockMaskColor`

- `Button _itemBtn`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `Item m_cachedItem`

- `Boolean isBehindAvailItem`


## Methods

- `Void Render(Item)`

- `Void OnClickItemBtn()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class RhineArcTimelineItem : MonoBehaviour, IHotfixable
{
	private GameObject _unAvailPart; // 0x18
	private GameObject _availPart; // 0x20
	private GameObject _unAvailDot; // 0x28
	private GameObject _unAvailFirstDot; // 0x30
	private GameObject _availDot; // 0x38
	private GameObject _newTrack; // 0x40
	private GameObject _newTrackDot; // 0x48
	private Text _id; // 0x50
	private Text _name; // 0x58
	private Image _itemIcon; // 0x60
	private Image _itemSmallIcon; // 0x68
	private UIAtlasImage _textBack; // 0x70
	private UIAtlasImage _itemMask; // 0x78
	private Single _lockTextBackAlpha; // 0x80
	private Color _newMaskColor; // 0x84
	private Color _unlockMaskColor; // 0x94
	private Color _lockMaskColor; // 0xa4
	private List`1 _smallIconList; // 0xb8
	private Button _itemBtn; // 0xc0
	private UIPageFinder m_pageFinder; // 0xc8
	private UIStateFinder m_stateFinder; // 0xd8
	private Item m_cachedItem; // 0xe8
	public Boolean isBehindAvailItem; // 0xf0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClickItemBtn; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3276758 VA: 0x759588e758
	public Void Render(Item item) { }
	// RVA: 0x3276b4c VA: 0x759588eb4c
	public Void OnClickItemBtn() { }
	// RVA: 0x3276d3c VA: 0x759588ed3c
	public Void .ctor() { }
}
```