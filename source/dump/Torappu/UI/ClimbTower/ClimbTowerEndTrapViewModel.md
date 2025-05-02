# ClimbTowerEndTrapViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Type type`

- `Sprite imgTrap`


## Methods

- `Void LoadTrap(Type, String)`

- `Int32 CompareTo(ClimbTowerEndTrapViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEndTrapViewModel : IHotfixable
{
	public Type type; // 0x10
	public Sprite imgTrap; // 0x18
	private static DelegateBridge __Hotfix0_LoadTrap; // 0x0
	private static DelegateBridge __Hotfix0_CompareTo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2c9e75c VA: 0x75952b675c
	public Void LoadTrap(Type trapType, String trapId) { }
	// RVA: 0x2c9e81c VA: 0x75952b681c
	public Int32 CompareTo(ClimbTowerEndTrapViewModel r) { }
	// RVA: 0x2c9e908 VA: 0x75952b6908
	public Void .ctor() { }
}
```