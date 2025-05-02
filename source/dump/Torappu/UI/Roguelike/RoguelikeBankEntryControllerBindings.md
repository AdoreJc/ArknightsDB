# RoguelikeBankEntryControllerBindings

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Action m_onCancel`

- `Action m_onOpenWithdraw`

- `Action m_onOpenInvest`

- `Action m_onOpenBankReward`


## Methods

- `Void OnOpenWithdraw()`

- `Void OnOpenInvest()`

- `Void OnCancel()`

- `Void OnOpenBankReward()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeBankEntryControllerBindings : IHotfixable
{
	private Action m_onCancel; // 0x10
	private Action m_onOpenWithdraw; // 0x18
	private Action m_onOpenInvest; // 0x20
	private Action m_onOpenBankReward; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnOpenWithdraw; // 0x8
	private static DelegateBridge __Hotfix0_OnOpenInvest; // 0x10
	private static DelegateBridge __Hotfix0_OnCancel; // 0x18
	private static DelegateBridge __Hotfix0_OnOpenBankReward; // 0x20


	// RVA: 0x2ade2ec VA: 0x75950f62ec
	private Void .ctor() { }
	// RVA: 0x2adde94 VA: 0x75950f5e94
	public Void OnOpenWithdraw() { }
	// RVA: 0x2addf90 VA: 0x75950f5f90
	public Void OnOpenInvest() { }
	// RVA: 0x2ade08c VA: 0x75950f608c
	public Void OnCancel() { }
	// RVA: 0x2ade188 VA: 0x75950f6188
	public Void OnOpenBankReward() { }
}
```