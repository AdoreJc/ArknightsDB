# BuildingUINotFlagFilterItem

**Namespace:** `Torappu.Building.UI`


## Fields

- `TwoStateToggle _toggle`

- `FilterEnum _filterType`


## Properties

- `FilterEnum filterType`


## Methods

- `FilterEnum get_filterType()`

- `Void EventOnToggleClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingUINotFlagFilterItem`1 : MonoBehaviour
{
	private TwoStateToggle _toggle; // 0x0
	private FilterEnum _filterType; // 0x0
	public Action`1 onFilterClicked; // 0x0

	protected FilterEnum filterType { get; }

	// RVA: 0x VA: 0x0
	protected FilterEnum get_filterType() { }
	// RVA: 0x VA: 0x0
	public virtual Void Render(FilterEnum filterEnum) { }
	// RVA: 0x VA: 0x0
	public Void EventOnToggleClicked() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```