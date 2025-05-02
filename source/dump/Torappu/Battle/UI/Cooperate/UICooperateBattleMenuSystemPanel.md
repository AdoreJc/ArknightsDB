# UICooperateBattleMenuSystemPanel

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `GameObject _systemPanelAbnormal`

- `Text _systemPanelAbnormalText`

- `Text _systemPanelAbnormalInfoText`

- `Text _systemPanelAbnormalInfoWaringText`

- `GameObject _exitInfoUnpunish`

- `GameObject _exitInfoPunish`

- `GameObject _exitInfoInTraining`

- `CooperateGameMode m_gameMode`

- `CooperateUIPlugin m_plugin`

- `Int32 m_gameAbnormalParam`

- `Boolean m_isAbnormalExit`

- `Boolean m_isShowNetWorkMask`

- `ResultInfoBasic m_result`

- `GameSettleInfo m_cachedSettle`


## Methods

- `Void OnGameInit(CooperateUIPlugin, CooperateGameMode)`

- `Void OnGameReady()`

- `Void InitLayout()`

- `Void Show()`

- `Void SetPunishInfo(Boolean)`

- `Boolean HookOnBattleFinishServiceStateEnter()`

- `Void AddResultNormalTarget(TargetInfo)`

- `Void _HandleBattleEnd(Object)`

- `Void _OnBattleFinishSend(GameSettleInfo)`

- `Void OnAbnormalExitClicked()`

- `Void OnGiveUpClicked()`

- `Void OnCancelGiveUpClicked()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateBattleMenuSystemPanel : MonoBehaviour, IHotfixable
{
	private GameObject _systemPanelAbnormal; // 0x18
	private Text _systemPanelAbnormalText; // 0x20
	private Text _systemPanelAbnormalInfoText; // 0x28
	private Text _systemPanelAbnormalInfoWaringText; // 0x30
	private GameObject _exitInfoUnpunish; // 0x38
	private GameObject _exitInfoPunish; // 0x40
	private GameObject _exitInfoInTraining; // 0x48
	private CooperateGameMode m_gameMode; // 0x50
	private CooperateUIPlugin m_plugin; // 0x58
	private Int32 m_gameAbnormalParam; // 0x60
	private Boolean m_isAbnormalExit; // 0x64
	private Boolean m_isShowNetWorkMask; // 0x65
	private ResultInfoBasic m_result; // 0x68
	private GameSettleInfo m_cachedSettle; // 0x70
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x0
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x8
	private static DelegateBridge __Hotfix0_InitLayout; // 0x10
	private static DelegateBridge __Hotfix0_Show; // 0x18
	private static DelegateBridge __Hotfix0_SetPunishInfo; // 0x20
	private static DelegateBridge __Hotfix0_HookOnBattleFinishServiceStateEnter; // 0x28
	private static DelegateBridge __Hotfix0_AddResultNormalTarget; // 0x30
	private static DelegateBridge __Hotfix0__HandleBattleEnd; // 0x38
	private static DelegateBridge __Hotfix0__OnBattleFinishSend; // 0x40
	private static DelegateBridge __Hotfix0_OnAbnormalExitClicked; // 0x48
	private static DelegateBridge __Hotfix0_OnGiveUpClicked; // 0x50
	private static DelegateBridge __Hotfix0_OnCancelGiveUpClicked; // 0x58
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x20e295c VA: 0x75946fa95c
	public Void OnGameInit(CooperateUIPlugin plugin, CooperateGameMode gameMode) { }
	// RVA: 0x20e2df8 VA: 0x75946fadf8
	public Void OnGameReady() { }
	// RVA: 0x20e3038 VA: 0x75946fb038
	public Void InitLayout() { }
	// RVA: 0x20e310c VA: 0x75946fb10c
	public Void Show() { }
	// RVA: 0x20e318c VA: 0x75946fb18c
	public Void SetPunishInfo(Boolean punish) { }
	// RVA: 0x20e3260 VA: 0x75946fb260
	public Boolean HookOnBattleFinishServiceStateEnter() { }
	// RVA: 0x20e3850 VA: 0x75946fb850
	public Void AddResultNormalTarget(TargetInfo target) { }
	// RVA: 0x20e2bdc VA: 0x75946fabdc
	private Void _HandleBattleEnd(Object arg) { }
	// RVA: 0x20e39ec VA: 0x75946fb9ec
	private Void _OnBattleFinishSend(GameSettleInfo settleInfo) { }
	// RVA: 0x20e3c4c VA: 0x75946fbc4c
	public Void OnAbnormalExitClicked() { }
	// RVA: 0x20e3d28 VA: 0x75946fbd28
	public Void OnGiveUpClicked() { }
	// RVA: 0x20e3ecc VA: 0x75946fbecc
	public Void OnCancelGiveUpClicked() { }
	// RVA: 0x20e3f40 VA: 0x75946fbf40
	public Void OnDestroy() { }
	// RVA: 0x20e4048 VA: 0x75946fc048
	public Void .ctor() { }
}
```