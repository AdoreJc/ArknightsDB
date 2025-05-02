# MileStoneViewModel

**Namespace:** `Torappu.Activity`


## Fields

- `String id`

- `Int32 orderId`

- `PartType type`

- `State state`

- `Int32 count`

- `ItemBundle rewardItem`


## Methods

- `Int32 CompareTo(MileStoneViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class MileStoneViewModel : IComparable`1, IHotfixable
{
	public String id; // 0x10
	public Int32 orderId; // 0x18
	public PartType type; // 0x1c
	public State state; // 0x20
	public Int32 count; // 0x24
	public ItemBundle rewardItem; // 0x28
	private static DelegateBridge __Hotfix0_CompareTo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x30b92f0 VA: 0x75956d12f0
	public Int32 CompareTo(MileStoneViewModel other) { }
	// RVA: 0x30b937c VA: 0x75956d137c
	public Void .ctor() { }
}
```