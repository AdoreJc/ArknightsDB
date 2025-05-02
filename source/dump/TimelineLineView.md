# TimelineLineView

**Namespace:** ` `


## Fields

- `Int32 m_cachedIndex`


## Methods

- `Int32 _determineLineIndex(TimelineItemModel)`

- `Void ApplyData(TimelineItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TimelineLineView : IHotfixable
{
	private List`1 _lines; // 0x10
	private Int32 m_cachedIndex; // 0x18
	private static DelegateBridge __Hotfix0__determineLineIndex; // 0x0
	private static DelegateBridge __Hotfix0_ApplyData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3086674 VA: 0x759569e674
	private Int32 _determineLineIndex(TimelineItemModel timelineItemModel) { }
	// RVA: 0x3085c88 VA: 0x759569dc88
	public Void ApplyData(TimelineItemModel timelineItemModel) { }
	// RVA: 0x3086744 VA: 0x759569e744
	public Void .ctor() { }
}
```