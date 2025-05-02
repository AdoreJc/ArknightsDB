# ItemCardGroupViewModel

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ClassifyFilter m_classifyFilter`


## Properties

- `ClassifyFilter classifyFilter`


## Methods

- `Void set_items(List`1)`

- `UIItemViewModel GetTargetItem(Int32)`

- `ClassifyFilter get_classifyFilter()`

- `Void set_classifyFilter(ClassifyFilter)`

- `Void RefreshClassify()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemCardGroupViewModel
{
	private List`1 m_items; // 0x10
	public List`1 activeItems; // 0x18
	private ClassifyFilter m_classifyFilter; // 0x20

	public List`1 items { get; set; }
	public ClassifyFilter classifyFilter { get; set; }

	// RVA: 0x2d2b4a8 VA: 0x75953434a8
	public List`1 get_items() { }
	// RVA: 0x2d2b4b0 VA: 0x75953434b0
	public Void set_items(List`1 value) { }
	// RVA: 0x2d2b6b0 VA: 0x75953436b0
	public UIItemViewModel GetTargetItem(Int32 position) { }
	// RVA: 0x2d2b70c VA: 0x759534370c
	public ClassifyFilter get_classifyFilter() { }
	// RVA: 0x2d2b714 VA: 0x7595343714
	public Void set_classifyFilter(ClassifyFilter value) { }
	// RVA: 0x2d2b4cc VA: 0x75953434cc
	public Void RefreshClassify() { }
	// RVA: 0x2d2b71c VA: 0x759534371c
	public Void .ctor() { }
}
```