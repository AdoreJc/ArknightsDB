# TemplateShopGroupViewModel

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `String groupId`

- `Int32 slotId`

- `String preGroupId`

- `String unlockString`

- `Boolean preGroupBuyAllFlag`

- `Boolean m_isUnlocked`


## Properties

- `Boolean buyAllFlag`

- `Boolean isUnlocked`


## Methods

- `Boolean get_buyAllFlag()`

- `Boolean get_isUnlocked()`

- `Boolean IsGoodAllSoldout()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopGroupViewModel
{
	public String groupId; // 0x10
	public Int32 slotId; // 0x18
	public String preGroupId; // 0x20
	public String unlockString; // 0x28
	public List`1 goodList; // 0x30
	public Boolean preGroupBuyAllFlag; // 0x38
	private Boolean m_isUnlocked; // 0x39

	public Boolean buyAllFlag { get; }
	public Boolean isUnlocked { get; }

	// RVA: 0x2360bd0 VA: 0x7594978bd0
	public Boolean get_buyAllFlag() { }
	// RVA: 0x235e750 VA: 0x7594976750
	public Boolean get_isUnlocked() { }
	// RVA: 0x2356060 VA: 0x759496e060
	public Boolean IsGoodAllSoldout() { }
	// RVA: 0x2360c70 VA: 0x7594978c70
	public Void .ctor() { }
}
```