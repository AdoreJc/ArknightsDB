# EnemyDuelJudgeDialog

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Text _desc`

- `Action m_confirmCallback`

- `Action m_cancelCallback`


## Methods

- `Void OnCancelClicked()`

- `Void OnConfirmClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelJudgeDialog : UICustomDialog`1
{
	private Text _desc; // 0x50
	private Action m_confirmCallback; // 0x58
	private Action m_cancelCallback; // 0x60
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0_OnCancelClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnConfirmClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2942a0c VA: 0x7594f5aa0c
	protected override Void OnRender(Options options) { }
	// RVA: 0x2942b70 VA: 0x7594f5ab70
	public Void OnCancelClicked() { }
	// RVA: 0x2942bf4 VA: 0x7594f5abf4
	public Void OnConfirmClicked() { }
	// RVA: 0x2942c78 VA: 0x7594f5ac78
	public Void .ctor() { }
}
```