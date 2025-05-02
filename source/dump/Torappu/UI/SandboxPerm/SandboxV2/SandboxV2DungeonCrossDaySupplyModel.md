# SandboxV2DungeonCrossDaySupplyModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Int32 charCount`

- `Int32 periodCount`

- `Int32 buffCount`

- `Boolean showBuffEnough`

- `Int32 drinkHasCount`

- `Boolean showDrinkNotEnoughTips`


## Methods

- `Void LoadData(SandboxV2Data, PlayerSandboxV2)`

- `Int32 _GetBuffCountByChars(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonCrossDaySupplyModel : IHotfixable
{
	public Int32 charCount; // 0x10
	public Int32 periodCount; // 0x14
	public Int32 buffCount; // 0x18
	public Boolean showBuffEnough; // 0x1c
	public Int32 drinkHasCount; // 0x20
	public Boolean showDrinkNotEnoughTips; // 0x24
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__GetBuffCountByChars; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2524bb0 VA: 0x7594b3cbb0
	public Void LoadData(SandboxV2Data gameData, PlayerSandboxV2 playerSandbox) { }
	// RVA: 0x2524fe4 VA: 0x7594b3cfe4
	private Int32 _GetBuffCountByChars(List`1 supplyChars) { }
	// RVA: 0x2524b40 VA: 0x7594b3cb40
	public Void .ctor() { }
}
```