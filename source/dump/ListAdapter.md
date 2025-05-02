# ListAdapter

**Namespace:** ` `


## Fields

- `ArchiveAvgListDataBinder m_closure`

- `String <selectedItemId>k__BackingField`


## Properties

- `String selectedItemId`


## Methods

- `Void set_dataSet(ListDict`2)`

- `String get_selectedItemId()`

- `Void set_selectedItemId(String)`

- `Sprite _TryLoadAvgTitleSprite(AvgItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ListAdapter : SimpleLayoutAdapter
{
	private ArchiveAvgListDataBinder m_closure; // 0x20
	private ListDict`2 <dataSet>k__BackingField; // 0x28
	private String <selectedItemId>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_dataSet; // 0x0
	private static DelegateBridge __Hotfix0_set_dataSet; // 0x8
	private static DelegateBridge __Hotfix0_get_selectedItemId; // 0x10
	private static DelegateBridge __Hotfix0_set_selectedItemId; // 0x18
	private static DelegateBridge __Hotfix0_get_count; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28
	private static DelegateBridge __Hotfix0_RenderView; // 0x30
	private static DelegateBridge __Hotfix0__TryLoadAvgTitleSprite; // 0x38

	public ListDict`2 dataSet { get; set; }
	public String selectedItemId { get; set; }
	public override Int32 count { get; }

	// RVA: 0x3035924 VA: 0x759564d924
	public ListDict`2 get_dataSet() { }
	// RVA: 0x3034f60 VA: 0x759564cf60
	public Void set_dataSet(ListDict`2 value) { }
	// RVA: 0x3036188 VA: 0x759564e188
	public String get_selectedItemId() { }
	// RVA: 0x30361f0 VA: 0x759564e1f0
	public Void set_selectedItemId(String value) { }
	// RVA: 0x3036274 VA: 0x759564e274
	public override Int32 get_count() { }
	// RVA: 0x3034d8c VA: 0x759564cd8c
	public Void .ctor(ArchiveAvgListDataBinder closure) { }
	// RVA: 0x30362f8 VA: 0x759564e2f8
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x3036584 VA: 0x759564e584
	private Sprite _TryLoadAvgTitleSprite(AvgItemModel itemModel) { }
}
```