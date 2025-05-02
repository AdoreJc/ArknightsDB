# EnemyDuelOKDialog

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Text _desc`

- `Text _btnText`

- `Action m_comfirmCallback`


## Methods

- `Void OnCancelClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelOKDialog : UICustomDialog`1
{
	private Text _desc; // 0x50
	private Text _btnText; // 0x58
	private Action m_comfirmCallback; // 0x60
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0_OnCancelClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2942d08 VA: 0x7594f5ad08
	protected override Void OnRender(Options options) { }
	// RVA: 0x2942ec8 VA: 0x7594f5aec8
	public Void OnCancelClicked() { }
	// RVA: 0x2942f4c VA: 0x7594f5af4c
	public Void .ctor() { }
}
```