# EnemyDuelEntryRewardView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `SimpleLayoutContent _basicScoreContent`

- `SimpleLayoutContent _operationScoreContent`

- `SimpleLayoutContent _standScoreContent`

- `Text _operationSkipRate`

- `Text _operationBetRate`

- `Text _operationAllinRate`

- `Text _standBetRate`

- `Boolean m_isInited`

- `EnemyDuelEntryRewardViewModel m_cachedModel`

- `BasicScoreAdapter m_basicScoreAdapter`

- `OperationScoreAdapter m_operationScoreAdapter`

- `StandScoreAdapter m_standScoreAdapter`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelEntryRewardView : DataBinder`1, IHotfixable
{
	private SimpleLayoutContent _basicScoreContent; // 0x20
	private SimpleLayoutContent _operationScoreContent; // 0x28
	private SimpleLayoutContent _standScoreContent; // 0x30
	private Text _operationSkipRate; // 0x38
	private Text _operationBetRate; // 0x40
	private Text _operationAllinRate; // 0x48
	private Text _standBetRate; // 0x50
	private Boolean m_isInited; // 0x58
	private EnemyDuelEntryRewardViewModel m_cachedModel; // 0x60
	private BasicScoreAdapter m_basicScoreAdapter; // 0x68
	private OperationScoreAdapter m_operationScoreAdapter; // 0x70
	private StandScoreAdapter m_standScoreAdapter; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x294bb24 VA: 0x7594f63b24
	private Void _InitIfNot() { }
	// RVA: 0x294be4c VA: 0x7594f63e4c
	public override Void OnValueChanged(EnemyDuelEntryRewardProperty property) { }
	// RVA: 0x294c054 VA: 0x7594f64054
	public Void .ctor() { }
}
```