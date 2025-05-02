# AsyncDataViewHandler

**Namespace:** `Torappu.UI`


## Fields

- `ViewType <view>k__BackingField`

- `DataType <data>k__BackingField`


## Properties

- `ViewType view`

- `DataType data`


## Methods

- `ViewType get_view()`

- `Void set_view(ViewType)`

- `DataType get_data()`

- `Void set_data(DataType)`

- `Void UpdateData(DataType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class AsyncDataViewHandler`2 : Handler
{
	private ViewType <view>k__BackingField; // 0x0
	private DataType <data>k__BackingField; // 0x0
	private static DelegateBridge __Hotfix0_get_view; // 0x0
	private static DelegateBridge __Hotfix0_set_view; // 0x0
	private static DelegateBridge __Hotfix0_get_data; // 0x0
	private static DelegateBridge __Hotfix0_set_data; // 0x0
	private static DelegateBridge __Hotfix0_OnGameObjectLoaded; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0

	protected ViewType view { get; set; }
	protected DataType data { get; set; }

	// RVA: 0x VA: 0x0
	protected ViewType get_view() { }
	// RVA: 0x VA: 0x0
	private Void set_view(ViewType value) { }
	// RVA: 0x VA: 0x0
	protected DataType get_data() { }
	// RVA: 0x VA: 0x0
	private Void set_data(DataType value) { }
	// RVA: 0x VA: 0x0
	protected sealed override Void OnGameObjectLoaded(GameObject obj) { }
	// RVA: 0x VA: 0x0
	public Void UpdateData(DataType data) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```