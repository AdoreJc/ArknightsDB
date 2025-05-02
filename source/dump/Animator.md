# Animator

**Namespace:** ` `


## Fields

- `Int32 m_focusIndex`

- `Single m_position`

- `Tween m_tween`


## Methods

- `Void set_dataSource(List`1)`

- `Void Reset(Int32)`

- `Void Update(Int32)`

- `Single _GetPosition()`

- `Void _SetPosition(Single)`

- `StageMixStoryRetroLineItemView _FetchSpareView()`

- `Void _SpareView(StageMixStoryRetroLineItemView)`

- `Void _SpareAllViews()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class Animator
{
	private readonly StageMixStoryRetroLineItemView m_itemPrefab; // 0x10
	private readonly Transform m_itemParent; // 0x18
	private readonly Int32 m_activeDistance; // 0x20
	private readonly Ease m_focusEase; // 0x24
	private readonly Single m_focusDuration; // 0x28
	private readonly ListDict`2 m_activeItems; // 0x30
	private readonly Stack`1 m_inactiveItems; // 0x38
	private readonly HashSet`1 m_toRemove; // 0x40
	private Int32 m_focusIndex; // 0x48
	private Single m_position; // 0x4c
	private Tween m_tween; // 0x50
	private List`1 <dataSource>k__BackingField; // 0x58

	private List`1 dataSource { get; set; }

	// RVA: 0x2fff930 VA: 0x7595617930
	private List`1 get_dataSource() { }
	// RVA: 0x2fff938 VA: 0x7595617938
	public Void set_dataSource(List`1 value) { }
	// RVA: 0x2fff728 VA: 0x7595617728
	public Void .ctor(StageMixStoryRetroLineItemView itemPrefab, Transform itemParent, Int32 activeDistance, Ease focusEase) { }
	// RVA: 0x2fff550 VA: 0x7595617550
	public Void Reset(Int32 focusIndex) { }
	// RVA: 0x2fff59c VA: 0x759561759c
	public Void Update(Int32 focusIndex) { }
	// RVA: 0x30001c4 VA: 0x75956181c4
	private Single _GetPosition() { }
	// RVA: 0x2fffcbc VA: 0x7595617cbc
	private Void _SetPosition(Single position) { }
	// RVA: 0x3000234 VA: 0x7595618234
	private StageMixStoryRetroLineItemView _FetchSpareView() { }
	// RVA: 0x30001cc VA: 0x75956181cc
	private Void _SpareView(StageMixStoryRetroLineItemView view) { }
	// RVA: 0x2fff940 VA: 0x7595617940
	private Void _SpareAllViews() { }
}
```