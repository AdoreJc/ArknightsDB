# UIEffect

**Namespace:** `Torappu.UI`


## Fields

- `Boolean _overrideSortingLayer`

- `SortingLayerWrapper _sortingLayerId`

- `Int32 _sortingOrderDelta`

- `Boolean _overrideGoLayerToUI`


## Properties

- `Boolean overrideSortingLayer`


## Methods

- `Boolean get_overrideSortingLayer()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIEffect : BasicEffect
{
	private Boolean _overrideSortingLayer; // 0x18
	private SortingLayerWrapper _sortingLayerId; // 0x1c
	private Int32 _sortingOrderDelta; // 0x20
	private Boolean _overrideGoLayerToUI; // 0x24

	protected Boolean overrideSortingLayer { get; }

	// RVA: 0x226c258 VA: 0x7594884258
	protected Boolean get_overrideSortingLayer() { }
	// RVA: 0x226c260 VA: 0x7594884260
	public Void .ctor() { }
}
```