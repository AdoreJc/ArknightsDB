# RoguelikeShopDetailControllerBindings

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Action m_onCancel`

- `Action m_onConfirm`

- `RoguelikeShopDetailExtraInfoPlugin m_extraInfoPlugin`

- `RoguelikeGoodsObjPlugin m_goodIconPlugin`


## Properties

- `RoguelikeShopDetailExtraInfoPlugin extraInfoPlugin`

- `RoguelikeGoodsObjPlugin goodIconPlugin`


## Methods

- `RoguelikeShopDetailExtraInfoPlugin get_extraInfoPlugin()`

- `RoguelikeGoodsObjPlugin get_goodIconPlugin()`

- `Void OnConfirm()`

- `Void OnCancel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeShopDetailControllerBindings : IHotfixable
{
	private Action m_onCancel; // 0x10
	private Action m_onConfirm; // 0x18
	private RoguelikeShopDetailExtraInfoPlugin m_extraInfoPlugin; // 0x20
	private RoguelikeGoodsObjPlugin m_goodIconPlugin; // 0x28
	private static DelegateBridge __Hotfix0_get_extraInfoPlugin; // 0x0
	private static DelegateBridge __Hotfix0_get_goodIconPlugin; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_OnConfirm; // 0x18
	private static DelegateBridge __Hotfix0_OnCancel; // 0x20

	public RoguelikeShopDetailExtraInfoPlugin extraInfoPlugin { get; }
	public RoguelikeGoodsObjPlugin goodIconPlugin { get; }

	// RVA: 0x2ae8b14 VA: 0x7595100b14
	public RoguelikeShopDetailExtraInfoPlugin get_extraInfoPlugin() { }
	// RVA: 0x2ae8c04 VA: 0x7595100c04
	public RoguelikeGoodsObjPlugin get_goodIconPlugin() { }
	// RVA: 0x2ae8eec VA: 0x7595100eec
	private Void .ctor() { }
	// RVA: 0x2ae8ce4 VA: 0x7595100ce4
	public Void OnConfirm() { }
	// RVA: 0x2ae8de0 VA: 0x7595100de0
	public Void OnCancel() { }
}
```