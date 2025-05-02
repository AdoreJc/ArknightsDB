# EnemyDuelOperationModeViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Int32 totalMoney`

- `Int32 betMoney`

- `Int32 expectationMoney`

- `Boolean isExBet`

- `Int32 playerRank`


## Properties

- `Boolean isMoneyEnough`

- `Boolean useExBet`


## Methods

- `Boolean get_isMoneyEnough()`

- `Boolean get_useExBet()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelOperationModeViewModel : IHotfixable
{
	public Int32 totalMoney; // 0x10
	public Int32 betMoney; // 0x14
	public Int32 expectationMoney; // 0x18
	public Boolean isExBet; // 0x1c
	public Int32 playerRank; // 0x20
	private static DelegateBridge __Hotfix0_get_isMoneyEnough; // 0x0
	private static DelegateBridge __Hotfix0_get_useExBet; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isMoneyEnough { get; }
	public Boolean useExBet { get; }

	// RVA: 0x297c42c VA: 0x7594f9442c
	public Boolean get_isMoneyEnough() { }
	// RVA: 0x297c49c VA: 0x7594f9449c
	public Boolean get_useExBet() { }
	// RVA: 0x2982988 VA: 0x7594f9a988
	public Void .ctor() { }
}
```