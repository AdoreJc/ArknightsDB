# RoguelikeBankFaultyControllerBindings

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Action m_onCancel`

- `Action m_onOpenBankReward`


## Methods

- `Void OnCancel()`

- `Void OnOpenBankReward()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeBankFaultyControllerBindings : IHotfixable
{
	private Action m_onCancel; // 0x10
	private Action m_onOpenBankReward; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnCancel; // 0x8
	private static DelegateBridge __Hotfix0_OnOpenBankReward; // 0x10


	// RVA: 0x2ade6e0 VA: 0x75950f66e0
	private Void .ctor() { }
	// RVA: 0x2ade4f0 VA: 0x75950f64f0
	public Void OnCancel() { }
	// RVA: 0x2ade5ec VA: 0x75950f65ec
	public Void OnOpenBankReward() { }
}
```