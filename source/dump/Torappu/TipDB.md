# TipDB

**Namespace:** `Torappu`


## Methods

- `TipData PickTip()`

- `TipData PickTip(Category)`

- `WorldViewTip PickWorldViewTip(WorldViewTip)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class TipDB : ConstTable`2
{
	private const Int32 INITIAL_CAPACITY; // 0x0
	private List`1 m_list; // 0x60
	private static DelegateBridge __Hotfix0_PickTip; // 0x0
	private static DelegateBridge __Hotfix1_PickTip; // 0x8
	private static DelegateBridge __Hotfix0_PickTips; // 0x10
	private static DelegateBridge __Hotfix1_PickTips; // 0x18
	private static DelegateBridge __Hotfix0_PickWorldViewTip; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x32c5714 VA: 0x75958dd714
	public TipData PickTip() { }
	// RVA: 0x32c5780 VA: 0x75958dd780
	public TipData PickTip(Category category) { }
	// RVA: 0x32c599c VA: 0x75958dd99c
	public TipData[] PickTips(Int32 count) { }
	// RVA: 0x32c5a24 VA: 0x75958dda24
	public TipData[] PickTips(Int32 count, Category category, IList`1 candidates) { }
	// RVA: 0x32c5f54 VA: 0x75958ddf54
	public WorldViewTip PickWorldViewTip(WorldViewTip lastTip) { }
	// RVA: 0x32c6080 VA: 0x75958de080
	public Void .ctor() { }
}
```