# NotifyRecord

**Namespace:** ` `


## Fields

- `Int32 viewId`

- `Int64 endTicks`

- `NotifyViewPriority priority`

- `String signature`

- `NotifyViewLayouter layouter`

- `GameObject prefab`

- `Boolean isDynLoaded`


## Methods

- `Int32 CompareTo(NotifyRecord)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
protected class NotifyRecord : IComparable`1
{
	public Int32 viewId; // 0x10
	public Int64 endTicks; // 0x18
	public NotifyViewPriority priority; // 0x20
	public String signature; // 0x28
	public NotifyViewLayouter layouter; // 0x30
	public GameObject prefab; // 0x38
	public Boolean isDynLoaded; // 0x40


	// RVA: 0x67ab30c VA: 0x7598dc330c
	public Int32 CompareTo(NotifyRecord other) { }
	// RVA: 0x67ab888 VA: 0x7598dc3888
	public Void .ctor() { }
}
```