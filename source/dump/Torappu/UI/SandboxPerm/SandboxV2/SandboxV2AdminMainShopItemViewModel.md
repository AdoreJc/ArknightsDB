# SandboxV2AdminMainShopItemViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Int32 index`

- `String goodId`

- `String itemId`

- `String itemName`

- `Int32 itemCount`

- `SandboxV2CoinType coinType`

- `Int32 originPrice`

- `Int32 currPrice`

- `Boolean isDiscount`

- `Int32 stock`

- `Boolean isSoldOut`

- `String goldItemId`

- `String dimensionCoinItemId`

- `String topicId`


## Methods

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainShopItemViewModel : IComparable, IHotfixable
{
	public Int32 index; // 0x10
	public String goodId; // 0x18
	public String itemId; // 0x20
	public String itemName; // 0x28
	public Int32 itemCount; // 0x30
	public SandboxV2CoinType coinType; // 0x34
	public Int32 originPrice; // 0x38
	public Int32 currPrice; // 0x3c
	public Boolean isDiscount; // 0x40
	public Int32 stock; // 0x44
	public Boolean isSoldOut; // 0x48
	public String goldItemId; // 0x50
	public String dimensionCoinItemId; // 0x58
	public String topicId; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_CompareTo; // 0x8


	// RVA: 0x24eb888 VA: 0x7594b03888
	public Void .ctor(Int32 index, String topicId, SandboxV2ShopGoodData goodData, SandboxPermItemData itemData, ShopSlotData playerData, SandboxV2BasicConst constData) { }
	// RVA: 0x24eb9f0 VA: 0x7594b039f0
	public Int32 CompareTo(Object obj) { }
}
```