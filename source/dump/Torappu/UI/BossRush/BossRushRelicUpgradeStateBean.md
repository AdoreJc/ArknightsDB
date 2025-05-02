# BossRushRelicUpgradeStateBean

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `String actId`

- `BossRushRelicUpgradeViewProperty viewProperty`

- `BossRushRelicNodeModel relicData`

- `String tokenName`

- `Int32 tokenCount`


## Methods

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushRelicUpgradeStateBean : IStateBean, IHotfixable
{
	public String actId; // 0x10
	public BossRushRelicUpgradeViewProperty viewProperty; // 0x18
	public BossRushRelicNodeModel relicData; // 0x20
	public String tokenName; // 0x28
	public Int32 tokenCount; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2e5ebb4 VA: 0x7595476bb4
	public Void LoadData() { }
	// RVA: 0x2e5f1b8 VA: 0x75954771b8
	public Void .ctor() { }
}
```