# UniEquipShowStateBean

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `UniEquipData uniEquipData`

- `String subProfessionId`

- `Boolean isUnlockShow`


## Methods

- `Void LoadData(UniEquipData, String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipShowStateBean : IStateBean, IHotfixable
{
	public UniEquipData uniEquipData; // 0x10
	public String subProfessionId; // 0x18
	public Boolean isUnlockShow; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x230c6d8 VA: 0x75949246d8
	public Void LoadData(UniEquipData uniEquipData, String subProfessionId, Boolean isUnlockShow) { }
	// RVA: 0x230c794 VA: 0x7594924794
	public Void .ctor() { }
}
```