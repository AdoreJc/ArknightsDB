# EnemyDuelPrepareModeDetailView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `TwoStateToggle _roomIconToggle`

- `Text _modeNameText`

- `Text _playerCntText`

- `Text _modeTargetText`

- `Text _modeDetailText`

- `Text _modePrefixText`

- `TwoStateToggle _multiPlayerToggle`


## Methods

- `Void Render(ActivityEnemyDuelModeData, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPrepareModeDetailView : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _roomIconToggle; // 0x18
	private Text _modeNameText; // 0x20
	private Text _playerCntText; // 0x28
	private Text _modeTargetText; // 0x30
	private Text _modeDetailText; // 0x38
	private Text _modePrefixText; // 0x40
	private TwoStateToggle _multiPlayerToggle; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2999ff8 VA: 0x7594fb1ff8
	public Void Render(ActivityEnemyDuelModeData modeData, Boolean isInRoom) { }
	// RVA: 0x299bfe0 VA: 0x7594fb3fe0
	public Void .ctor() { }
}
```