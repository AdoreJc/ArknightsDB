# Act20sideCartShowStateBean

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `String actId`

- `Boolean isRetro`

- `Cart currentCart`

- `Boolean spStageUnlocked`

- `Int32 spStageUnlockCount`


## Methods

- `Void InitData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCartShowStateBean : IStateBean, IHotfixable
{
	public String actId; // 0x10
	public Boolean isRetro; // 0x18
	public Dictionary`2 compsOnCar; // 0x20
	public Dictionary`2 cartCompList; // 0x28
	public Cart currentCart; // 0x30
	public Boolean spStageUnlocked; // 0x38
	public Int32 spStageUnlockCount; // 0x3c
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x32f16f8 VA: 0x75959096f8
	public Void InitData() { }
	// RVA: 0x32f1d8c VA: 0x7595909d8c
	public Void .ctor() { }
}
```