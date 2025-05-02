# BarrageManager

**Namespace:** ` `


## Fields

- `EnemyDuelEmoticonPageComponent m_closure`


## Methods

- `Void AddBarrage(EmoticonBarrageItemParam)`

- `BarrageLane _ChooseBarrageLane()`

- `EnemyDuelEmoticonBarrageItem _AllocateBarrageItem()`

- `Void _RecycleBarrageItem(EnemyDuelEmoticonBarrageItem)`

- `Single _GetLaneSamplePos(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class BarrageManager : IHotfixable
{
	private EnemyDuelEmoticonPageComponent m_closure; // 0x10
	private BarrageLane[] m_barrageLanes; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_AddBarrage; // 0x8
	private static DelegateBridge __Hotfix0__ChooseBarrageLane; // 0x10
	private static DelegateBridge __Hotfix0__AllocateBarrageItem; // 0x18
	private static DelegateBridge __Hotfix0__RecycleBarrageItem; // 0x20
	private static DelegateBridge __Hotfix0__GetLaneSamplePos; // 0x28


	// RVA: 0x2984f20 VA: 0x7594f9cf20
	public Void .ctor(EnemyDuelEmoticonPageComponent closure) { }
	// RVA: 0x29854c4 VA: 0x7594f9d4c4
	public Void AddBarrage(EmoticonBarrageItemParam param) { }
	// RVA: 0x298583c VA: 0x7594f9d83c
	private BarrageLane _ChooseBarrageLane() { }
	// RVA: 0x2985ad4 VA: 0x7594f9dad4
	private EnemyDuelEmoticonBarrageItem _AllocateBarrageItem() { }
	// RVA: 0x2985c88 VA: 0x7594f9dc88
	private Void _RecycleBarrageItem(EnemyDuelEmoticonBarrageItem item) { }
	// RVA: 0x29857a0 VA: 0x7594f9d7a0
	private Single _GetLaneSamplePos(Int32 index, Int32 count) { }
}
```