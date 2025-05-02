# UIBattleSandboxTopBarStatus

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `UITextSlider _remainTimeSlider`

- `Text _remainTimeText`

- `Image _remainTimeSliderBg`

- `Color _normalTimeColor`

- `Int32 _emergencyTimeThreshold`

- `Animation _emergencyAnim`

- `UITextSlider _coreHpSlider`

- `Text _monsterInfoText`

- `SandboxBattleStyle m_battleStyle`

- `Int32 m_cachedFinishedEnemiesCnt`

- `SandboxGameMode m_gameMode`

- `Int32 m_remainTime`


## Methods

- `Void OnInit(SandboxBattleStyle)`

- `Void UpdateData(BattleController, Boolean)`

- `Void _UpdateMonsterInfo(BattleController, Boolean)`

- `Void _SetRemainTimeInfo()`

- `Void _SetCoreHpSlider()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxTopBarStatus : MonoBehaviour, IHotfixable
{
	private UITextSlider _remainTimeSlider; // 0x18
	private Text _remainTimeText; // 0x20
	private Image _remainTimeSliderBg; // 0x28
	private Color _normalTimeColor; // 0x30
	private Int32 _emergencyTimeThreshold; // 0x40
	private Animation _emergencyAnim; // 0x48
	private UITextSlider _coreHpSlider; // 0x50
	private Text _monsterInfoText; // 0x58
	private SandboxBattleStyle m_battleStyle; // 0x60
	private Int32 m_cachedFinishedEnemiesCnt; // 0x64
	private SandboxGameMode m_gameMode; // 0x68
	private Int32 m_remainTime; // 0x70
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge __Hotfix0__UpdateMonsterInfo; // 0x10
	private static DelegateBridge __Hotfix0__SetRemainTimeInfo; // 0x18
	private static DelegateBridge __Hotfix0__SetCoreHpSlider; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x20c3234 VA: 0x75946db234
	public Void OnInit(SandboxBattleStyle battleStyle) { }
	// RVA: 0x20c34d8 VA: 0x75946db4d8
	public Void UpdateData(BattleController controller, Boolean force) { }
	// RVA: 0x20c38f4 VA: 0x75946db8f4
	private Void _UpdateMonsterInfo(BattleController controller, Boolean force) { }
	// RVA: 0x20c35ac VA: 0x75946db5ac
	private Void _SetRemainTimeInfo() { }
	// RVA: 0x20c37f4 VA: 0x75946db7f4
	private Void _SetCoreHpSlider() { }
	// RVA: 0x20c3a44 VA: 0x75946dba44
	public Void .ctor() { }
}
```