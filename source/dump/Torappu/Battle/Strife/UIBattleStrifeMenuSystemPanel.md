# UIBattleStrifeMenuSystemPanel

**Namespace:** `Torappu.Battle.Strife`


## Fields

- `Text _curWave`

- `Text _maxWave`

- `UIBattleStrifeSystemMenuState m_state`


## Methods

- `Void Show(UIBattleStrifeSystemMenuState, Int32, Int32)`

- `Void Hide()`

- `Void CloseSystemMenuPanel()`

- `Void FinishGameDirectly()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Strife
public class UIBattleStrifeMenuSystemPanel : MonoBehaviour, IHotfixable
{
	private Text _curWave; // 0x18
	private Text _maxWave; // 0x20
	private UIBattleStrifeSystemMenuState m_state; // 0x28
	private static DelegateBridge __Hotfix0_Show; // 0x0
	private static DelegateBridge __Hotfix0_Hide; // 0x8
	private static DelegateBridge __Hotfix0_CloseSystemMenuPanel; // 0x10
	private static DelegateBridge __Hotfix0_FinishGameDirectly; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1c58bc8 VA: 0x7594270bc8
	public Void Show(UIBattleStrifeSystemMenuState state, Int32 finishWave, Int32 totalWave) { }
	// RVA: 0x1c58d44 VA: 0x7594270d44
	public Void Hide() { }
	// RVA: 0x1c58dbc VA: 0x7594270dbc
	public Void CloseSystemMenuPanel() { }
	// RVA: 0x1c58e9c VA: 0x7594270e9c
	public Void FinishGameDirectly() { }
	// RVA: 0x1c58f7c VA: 0x7594270f7c
	public Void .ctor() { }
}
```