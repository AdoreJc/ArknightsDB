# ClimbTowerItemRewardModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Int32 lowerItemCurr`

- `Int32 lowerItemTotal`

- `String lowerItemName`

- `Int32 higherItemCurr`

- `Int32 higherItemTotal`

- `String higherItemName`

- `String countDownText`

- `Boolean isHard`


## Methods

- `Void LoadData(Boolean)`

- `Void SwitchMode(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerItemRewardModel : IHotfixable
{
	public Int32 lowerItemCurr; // 0x10
	public Int32 lowerItemTotal; // 0x14
	public String lowerItemName; // 0x18
	public Int32 higherItemCurr; // 0x20
	public Int32 higherItemTotal; // 0x24
	public String higherItemName; // 0x28
	public String countDownText; // 0x30
	public Boolean isHard; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_SwitchMode; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2cd8824 VA: 0x75952f0824
	public Void LoadData(Boolean isHard) { }
	// RVA: 0x2cd8a38 VA: 0x75952f0a38
	public Void SwitchMode(Boolean isHardMode) { }
	// RVA: 0x2cd8ab8 VA: 0x75952f0ab8
	public Void .ctor() { }
}
```