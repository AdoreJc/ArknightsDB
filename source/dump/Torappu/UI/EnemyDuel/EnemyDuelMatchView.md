# EnemyDuelMatchView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Text _timerText`

- `Text _maxPlayerText`

- `Text _curPlayerText`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelMatchView : DataBinder`1, IHotfixable
{
	private const String TIMER_FORMAT; // 0x0
	private Text _timerText; // 0x20
	private Text _maxPlayerText; // 0x28
	private Text _curPlayerText; // 0x30
	private TwoStateToggle[] _isMatchedToggles; // 0x38
	private Boolean m_isInited; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x299821c VA: 0x7594fb021c
	private Void _InitIfNot() { }
	// RVA: 0x2998290 VA: 0x7594fb0290
	public override Void OnValueChanged(EnemyDuelMatchProperty property) { }
	// RVA: 0x2998478 VA: 0x7594fb0478
	public Void .ctor() { }
}
```