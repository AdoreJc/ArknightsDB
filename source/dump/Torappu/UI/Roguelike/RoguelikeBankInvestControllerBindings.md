# RoguelikeBankInvestControllerBindings

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Action m_onCancel`

- `Action m_onInvest`

- `Action m_onOpenBankReward`


## Methods

- `Void OnInvest()`

- `Void OnCancel()`

- `Void OnOpenBankReward()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeBankInvestControllerBindings : IHotfixable
{
	private Action m_onCancel; // 0x10
	private Action m_onInvest; // 0x18
	private Action m_onOpenBankReward; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnInvest; // 0x8
	private static DelegateBridge __Hotfix0_OnCancel; // 0x10
	private static DelegateBridge __Hotfix0_OnOpenBankReward; // 0x18


	// RVA: 0x2adecd8 VA: 0x75950f6cd8
	private Void .ctor() { }
	// RVA: 0x2ade9e0 VA: 0x75950f69e0
	public Void OnInvest() { }
	// RVA: 0x2adeadc VA: 0x75950f6adc
	public Void OnCancel() { }
	// RVA: 0x2adebd8 VA: 0x75950f6bd8
	public Void OnOpenBankReward() { }
}
```