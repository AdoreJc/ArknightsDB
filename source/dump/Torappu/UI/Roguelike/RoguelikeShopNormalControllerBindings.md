# RoguelikeShopNormalControllerBindings

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Action m_onLeaveShop`

- `Action m_onDealerClick`

- `Action m_onSwitchClick`


## Methods

- `Void OnLeaveShopClicked()`

- `Void OnDealerClick()`

- `Void OnSwitchClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeShopNormalControllerBindings : IHotfixable
{
	private Action m_onLeaveShop; // 0x10
	private Action m_onDealerClick; // 0x18
	private Action m_onSwitchClick; // 0x20
	private static DelegateBridge __Hotfix0_OnLeaveShopClicked; // 0x0
	private static DelegateBridge __Hotfix0_OnDealerClick; // 0x8
	private static DelegateBridge __Hotfix0_OnSwitchClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2aeb930 VA: 0x7595103930
	public Void OnLeaveShopClicked() { }
	// RVA: 0x2aeba2c VA: 0x7595103a2c
	public Void OnDealerClick() { }
	// RVA: 0x2aeb70c VA: 0x759510370c
	public Void OnSwitchClick() { }
	// RVA: 0x2aec27c VA: 0x759510427c
	public Void .ctor() { }
}
```