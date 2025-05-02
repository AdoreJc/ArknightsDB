# RoguelikeShopLineupControllerBindings

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Action m_onBankClicked`

- `Action m_onRefresh`


## Methods

- `Void OnGoodsClicked(RoguelikeGoodsViewModel)`

- `Void OnBankClicked()`

- `Void OnLockSlotClicked(RoguelikeGoodsViewModel)`

- `Void OnRefresh()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeShopLineupControllerBindings : IHotfixable
{
	private Action`1 m_onGoodsClicked; // 0x10
	private Action m_onBankClicked; // 0x18
	private Action`1 m_onLockSlotClicked; // 0x20
	private List`1 m_goodPlugins; // 0x28
	private List`1 m_addonPlugins; // 0x30
	private Action m_onRefresh; // 0x38
	private static DelegateBridge __Hotfix0_get_goodPlugins; // 0x0
	private static DelegateBridge __Hotfix0_get_addonPlugins; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_OnGoodsClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnBankClicked; // 0x20
	private static DelegateBridge __Hotfix0_OnLockSlotClicked; // 0x28
	private static DelegateBridge __Hotfix0_OnRefresh; // 0x30

	public List`1 goodPlugins { get; }
	public List`1 addonPlugins { get; }

	// RVA: 0x2ae9570 VA: 0x7595101570
	public List`1 get_goodPlugins() { }
	// RVA: 0x2aea850 VA: 0x7595102850
	public List`1 get_addonPlugins() { }
	// RVA: 0x2aeb318 VA: 0x7595103318
	private Void .ctor() { }
	// RVA: 0x2aeb388 VA: 0x7595103388
	public Void OnGoodsClicked(RoguelikeGoodsViewModel model) { }
	// RVA: 0x2aeb428 VA: 0x7595103428
	public Void OnBankClicked() { }
	// RVA: 0x2aeb4ac VA: 0x75951034ac
	public Void OnLockSlotClicked(RoguelikeGoodsViewModel model) { }
	// RVA: 0x2aeab30 VA: 0x7595102b30
	public Void OnRefresh() { }
}
```