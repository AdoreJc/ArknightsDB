# RL04FragmentDetailWeightViewModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `FragmentBagStatus status`

- `Int32 totalWeight`

- `Int32 limitWeight`

- `Int32 overWeight`

- `Single weightProgress`

- `Int32 weightWithoutFragment`

- `Single weightProgressWithoutFragment`

- `Single limitWeightScale`

- `Single overWeightScale`


## Methods

- `Void RefreshStatus(RL04FragmentItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentDetailWeightViewModel : IHotfixable
{
	public FragmentBagStatus status; // 0x10
	public Int32 totalWeight; // 0x14
	public Int32 limitWeight; // 0x18
	public Int32 overWeight; // 0x1c
	public Single weightProgress; // 0x20
	public Int32 weightWithoutFragment; // 0x24
	public Single weightProgressWithoutFragment; // 0x28
	public Single limitWeightScale; // 0x2c
	public Single overWeightScale; // 0x30
	private static DelegateBridge __Hotfix0_RefreshStatus; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2b226f4 VA: 0x759513a6f4
	public Void RefreshStatus(RL04FragmentItemViewModel selectItem) { }
	// RVA: 0x2b227e4 VA: 0x759513a7e4
	public Void .ctor() { }
}
```