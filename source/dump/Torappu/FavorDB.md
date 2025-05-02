# FavorDB

**Namespace:** `Torappu`


## Methods

- `FavorData GetFavorData(Int32)`

- `Int32 GetFavorBattlePhase(Int32)`

- `Int32 CalculateFavorPointByBattlePhaseRoughly(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class FavorDB : ConstTable`2
{
	private static DelegateBridge __Hotfix0_GetFavorData; // 0x0
	private static DelegateBridge __Hotfix0_GetFavorBattlePhase; // 0x8
	private static DelegateBridge __Hotfix0_CalculateFavorPointByBattlePhaseRoughly; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31f0bd8 VA: 0x7595808bd8
	public FavorData GetFavorData(Int32 favorPoint) { }
	// RVA: 0x31f0ca4 VA: 0x7595808ca4
	public Int32 GetFavorBattlePhase(Int32 favorPoint) { }
	// RVA: 0x31f0d30 VA: 0x7595808d30
	public Int32 CalculateFavorPointByBattlePhaseRoughly(Int32 favorBattlePhase) { }
	// RVA: 0x31f1018 VA: 0x7595809018
	public Void .ctor() { }
}
```