# RoguelikeBankWithdrawControllerBindings

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Action m_callWithDrawl`

- `Action m_callOnCancel`

- `Action m_onOpenBankReward`


## Methods

- `Void OnWithDraw()`

- `Void OnCancel()`

- `Void OnOpenBankReward()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeBankWithdrawControllerBindings : IHotfixable
{
	private Action m_callWithDrawl; // 0x10
	private Action m_callOnCancel; // 0x18
	private Action m_onOpenBankReward; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnWithDraw; // 0x8
	private static DelegateBridge __Hotfix0_OnCancel; // 0x10
	private static DelegateBridge __Hotfix0_OnOpenBankReward; // 0x18


	// RVA: 0x2adfa1c VA: 0x75950f7a1c
	private Void .ctor() { }
	// RVA: 0x2adf6fc VA: 0x75950f76fc
	public Void OnWithDraw() { }
	// RVA: 0x2adf7f8 VA: 0x75950f77f8
	public Void OnCancel() { }
	// RVA: 0x2adf8f4 VA: 0x75950f78f4
	public Void OnOpenBankReward() { }
}
```