# RoguelikeGameShopStatusViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeGameShopStatusEnum m_shopStatus`

- `RoguelikeGameShopStatusEnum m_lastNormalStatus`


## Properties

- `RoguelikeGameShopStatusEnum shopStatus`

- `RoguelikeGameShopStatusEnum lastNormalStatus`


## Methods

- `RoguelikeGameShopStatusEnum get_shopStatus()`

- `Void set_shopStatus(RoguelikeGameShopStatusEnum)`

- `RoguelikeGameShopStatusEnum get_lastNormalStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeGameShopStatusViewModel : IHotfixable
{
	private RoguelikeGameShopStatusEnum m_shopStatus; // 0x10
	private RoguelikeGameShopStatusEnum m_lastNormalStatus; // 0x14
	private static DelegateBridge __Hotfix0_get_shopStatus; // 0x0
	private static DelegateBridge __Hotfix0_set_shopStatus; // 0x8
	private static DelegateBridge __Hotfix0_get_lastNormalStatus; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public RoguelikeGameShopStatusEnum shopStatus { get; set; }
	public RoguelikeGameShopStatusEnum lastNormalStatus { get; }

	// RVA: 0x2ad6c50 VA: 0x75950eec50
	public RoguelikeGameShopStatusEnum get_shopStatus() { }
	// RVA: 0x2ad6e34 VA: 0x75950eee34
	public Void set_shopStatus(RoguelikeGameShopStatusEnum value) { }
	// RVA: 0x2adadf8 VA: 0x75950f2df8
	public RoguelikeGameShopStatusEnum get_lastNormalStatus() { }
	// RVA: 0x2ae39d4 VA: 0x75950fb9d4
	public Void .ctor() { }
}
```