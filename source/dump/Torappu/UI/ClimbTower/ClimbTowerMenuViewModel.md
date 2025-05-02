# ClimbTowerMenuViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerInnerBuffListModel buffList`

- `Int32 squadCount`

- `Int32 trapCount`

- `Boolean isHardMode`

- `String curGodCardId`


## Methods

- `Void LoadData(Boolean, List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerMenuViewModel : IHotfixable
{
	public ClimbTowerInnerBuffListModel buffList; // 0x10
	public Int32 squadCount; // 0x18
	public Int32 trapCount; // 0x1c
	public Boolean isHardMode; // 0x20
	public String curGodCardId; // 0x28
	public Dictionary`2 squadProfessionCount; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2cda628 VA: 0x75952f2628
	public Void LoadData(Boolean isTutorial, List`1 predefinedCharList) { }
	// RVA: 0x2cdabe4 VA: 0x75952f2be4
	public Void .ctor() { }
}
```