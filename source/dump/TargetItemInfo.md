# TargetItemInfo

**Namespace:** ` `


## Fields

- `String itemId`

- `Int32 targetAmount`

- `Boolean <needShowTargetAmountInfo>k__BackingField`


## Properties

- `Boolean needShowTargetAmountInfo`


## Methods

- `Boolean get_needShowTargetAmountInfo()`

- `Void set_needShowTargetAmountInfo(Boolean)`

- `Void FindIfNeedShowTargetAmountInfo(BuildingWorkShopFormulaTree)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TargetItemInfo : IHotfixable
{
	public String itemId; // 0x10
	public Int32 targetAmount; // 0x18
	private Boolean <needShowTargetAmountInfo>k__BackingField; // 0x1c
	private static DelegateBridge __Hotfix0_get_needShowTargetAmountInfo; // 0x0
	private static DelegateBridge __Hotfix0_set_needShowTargetAmountInfo; // 0x8
	private static DelegateBridge __Hotfix0_FindIfNeedShowTargetAmountInfo; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean needShowTargetAmountInfo { get; set; }

	// RVA: 0x3d649bc VA: 0x759637c9bc
	public Boolean get_needShowTargetAmountInfo() { }
	// RVA: 0x3d66600 VA: 0x759637e600
	private Void set_needShowTargetAmountInfo(Boolean value) { }
	// RVA: 0x3d600fc VA: 0x75963780fc
	public Void FindIfNeedShowTargetAmountInfo(BuildingWorkShopFormulaTree formulaTree) { }
	// RVA: 0x3d66680 VA: 0x759637e680
	public Void .ctor() { }
}
```