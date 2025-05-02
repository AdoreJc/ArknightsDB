# RangeTileViewHolder

**Namespace:** ` `


## Fields

- `ViewRangeFogManager m_manager`


## Methods

- `Void MarkNotInView(String)`

- `Void MarkInView(String, Int32, Int32, Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RangeTileViewHolder : IHotfixable
{
	private ListDict`2 _leftButtomTile; // 0x10
	private ListDict`2 _rightUpTile; // 0x18
	private ViewRangeFogManager m_manager; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_MarkNotInView; // 0x8
	private static DelegateBridge __Hotfix0_MarkInView; // 0x10


	// RVA: 0x406ddf0 VA: 0x7596685df0
	public Void .ctor(ViewRangeFogManager manager) { }
	// RVA: 0x406df00 VA: 0x7596685f00
	public Void MarkNotInView(String id) { }
	// RVA: 0x406e188 VA: 0x7596686188
	public Void MarkInView(String id, Int32 leftButtomX, Int32 leftButtomY, Int32 rightUpX, Int32 rightUpY) { }
}
```