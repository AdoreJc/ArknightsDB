# SandboxBattleFailedMask

**Namespace:** `Torappu.Battle.UI`


## Fields

- `GameObject _basementStatusView`

- `GameObject _mobileBasementStatusView`

- `SandboxV2NodeType m_currentNodeType`

- `Boolean m_hooked`

- `GameObject m_statusView`

- `AnimationWrapper m_statusViewAnimation`

- `SandboxGameMode m_gameMode`


## Properties

- `SandboxGameMode sandboxGameMode`


## Methods

- `SandboxGameMode get_sandboxGameMode()`

- `Void OnPanelClick()`

- `Boolean BattleFailedPanelHide()`

- `RectTransform BattleFailedPanelInit()`

- `Boolean BattleFailedPanelShow()`

- `Boolean _NeedShowBattleFail()`

- `Void PlayAnim(String, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class SandboxBattleFailedMask : MonoBehaviour, IHotfixable
{
	private GameObject _basementStatusView; // 0x18
	private GameObject _mobileBasementStatusView; // 0x20
	private SandboxV2NodeType m_currentNodeType; // 0x28
	private Boolean m_hooked; // 0x2c
	private GameObject m_statusView; // 0x30
	private AnimationWrapper m_statusViewAnimation; // 0x38
	private SandboxGameMode m_gameMode; // 0x40
	private const String ENTRY; // 0x0
	private static DelegateBridge __Hotfix0_get_sandboxGameMode; // 0x0
	private static DelegateBridge __Hotfix0_OnPanelClick; // 0x8
	private static DelegateBridge __Hotfix0_BattleFailedPanelHide; // 0x10
	private static DelegateBridge __Hotfix0_BattleFailedPanelInit; // 0x18
	private static DelegateBridge __Hotfix0_BattleFailedPanelShow; // 0x20
	private static DelegateBridge __Hotfix0__NeedShowBattleFail; // 0x28
	private static DelegateBridge __Hotfix0_PlayAnim; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private SandboxGameMode sandboxGameMode { get; }

	// RVA: 0x20187a8 VA: 0x75946307a8
	private SandboxGameMode get_sandboxGameMode() { }
	// RVA: 0x2018858 VA: 0x7594630858
	public Void OnPanelClick() { }
	// RVA: 0x2018940 VA: 0x7594630940
	public Boolean BattleFailedPanelHide() { }
	// RVA: 0x20189c8 VA: 0x75946309c8
	public RectTransform BattleFailedPanelInit() { }
	// RVA: 0x2018a3c VA: 0x7594630a3c
	public Boolean BattleFailedPanelShow() { }
	// RVA: 0x2018c84 VA: 0x7594630c84
	private Boolean _NeedShowBattleFail() { }
	// RVA: 0x2018d90 VA: 0x7594630d90
	public Void PlayAnim(String stateName, Action`1 onAnimEnd) { }
	// RVA: 0x2018eac VA: 0x7594630eac
	public Void .ctor() { }
}
```