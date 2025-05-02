# Act1LockAutoBattleView

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `GameObject _autoBattleLocked`

- `TwoStateToggle _tglAutoBattle`

- `TwoStateToggle _tglPractice`

- `Boolean m_isInited`

- `Boolean m_isAutoBattleUnlocked`


## Methods

- `Void OnAutoBattleLocked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockAutoBattleView : DataBinder`1
{
	private GameObject _autoBattleLocked; // 0x20
	private TwoStateToggle _tglAutoBattle; // 0x28
	private TwoStateToggle _tglPractice; // 0x30
	private Boolean m_isInited; // 0x38
	private Boolean m_isAutoBattleUnlocked; // 0x39
	private static DelegateBridge __Hotfix0_OnAutoBattleLocked; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x33a8dd8 VA: 0x75959c0dd8
	public Void OnAutoBattleLocked() { }
	// RVA: 0x33a8e70 VA: 0x75959c0e70
	public override Void OnValueChanged(Act1LockDetailAutoBattleProperty property) { }
	// RVA: 0x33a8ff4 VA: 0x75959c0ff4
	private Void _InitIfNot() { }
	// RVA: 0x33a907c VA: 0x75959c107c
	public Void .ctor() { }
}
```