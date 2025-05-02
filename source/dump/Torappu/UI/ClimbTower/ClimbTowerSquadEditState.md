# ClimbTowerSquadEditState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerSquadEditView _view`

- `ClimbTowerMenuButton _menuButtonPrefab`

- `GameObject _multiEditBtnGo`

- `GameObject _disableEditGo`

- `RectTransform _backBtnRt`

- `Boolean m_hasInited`

- `ClimbTowerSquadEditStateBean m_stateBean`

- `Int32 m_cacheCardId`

- `MenuAdapter m_menuAdapter`

- `Coroutine m_tutorialCoroutine`

- `Boolean m_isForcedOpen`


## Methods

- `Void _NavToSingleEditState(IStateBean)`

- `Void _NavToMultiEditState(IStateBean)`

- `Void _OnProfessionClicked(ProfessionCategory)`

- `Void _OnStartBtnClicked()`

- `Void OnBtnMultiEdit()`

- `Void OnBtnBack()`

- `Void _TriggerTutorialCoroutine()`

- `Void _StopTutorialCoroutine()`

- `IEnumerator _WaitAndRaiseAVGSignal()`

- `Void _InitIfNot()`

- `Void _OnCharEdit(Int32)`

- `Void _DoStartBattle()`

- `Boolean _CheckIfStartBattleValid()`

- `Param _CreateParamToStartBattle()`

- `Void _InvokedStartBattle(Param)`

- `Void _OnStartBattleSuccess()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPause()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadEditState : PopupFadeState
{
	private ClimbTowerSquadEditView _view; // 0x70
	private ClimbTowerMenuButton _menuButtonPrefab; // 0x78
	private GameObject _multiEditBtnGo; // 0x80
	private GameObject _disableEditGo; // 0x88
	private RectTransform _backBtnRt; // 0x90
	private Boolean m_hasInited; // 0x98
	private ClimbTowerSquadEditStateBean m_stateBean; // 0xa0
	private Int32 m_cacheCardId; // 0xa8
	private MenuAdapter m_menuAdapter; // 0xb0
	private Coroutine m_tutorialCoroutine; // 0xb8
	private Boolean m_isForcedOpen; // 0xc0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnPause; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__NavToSingleEditState; // 0x20
	private static DelegateBridge __Hotfix0__NavToMultiEditState; // 0x28
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x30
	private static DelegateBridge __Hotfix0__OnProfessionClicked; // 0x38
	private static DelegateBridge __Hotfix0__OnStartBtnClicked; // 0x40
	private static DelegateBridge __Hotfix0_OnBtnMultiEdit; // 0x48
	private static DelegateBridge __Hotfix0_OnBtnBack; // 0x50
	private static DelegateBridge __Hotfix0__TriggerTutorialCoroutine; // 0x58
	private static DelegateBridge __Hotfix0__StopTutorialCoroutine; // 0x60
	private static DelegateBridge __Hotfix0__WaitAndRaiseAVGSignal; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x70
	private static DelegateBridge __Hotfix0__OnCharEdit; // 0x78
	private static DelegateBridge __Hotfix0__DoStartBattle; // 0x80
	private static DelegateBridge __Hotfix0__CheckIfStartBattleValid; // 0x88
	private static DelegateBridge __Hotfix0__CreateParamToStartBattle; // 0x90
	private static DelegateBridge __Hotfix0__PickRandomCharacter; // 0x98
	private static DelegateBridge __Hotfix0__InvokedStartBattle; // 0xa0
	private static DelegateBridge __Hotfix0__OnStartBattleSuccess; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0


	// RVA: 0x2cba4e4 VA: 0x75952d24e4
	protected override Void OnEnter() { }
	// RVA: 0x2cbb3c8 VA: 0x75952d33c8
	protected override Void OnPause() { }
	// RVA: 0x2cbb4f4 VA: 0x75952d34f4
	protected override Void OnResume() { }
	// RVA: 0x2cbb838 VA: 0x75952d3838
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2cbba2c VA: 0x75952d3a2c
	private Void _NavToSingleEditState(IStateBean stateBean) { }
	// RVA: 0x2cbbb0c VA: 0x75952d3b0c
	private Void _NavToMultiEditState(IStateBean stateBean) { }
	// RVA: 0x2cbbff8 VA: 0x75952d3ff8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2cbc060 VA: 0x75952d4060
	private Void _OnProfessionClicked(ProfessionCategory profession) { }
	// RVA: 0x2cbc1a4 VA: 0x75952d41a4
	private Void _OnStartBtnClicked() { }
	// RVA: 0x2cbc2c0 VA: 0x75952d42c0
	public Void OnBtnMultiEdit() { }
	// RVA: 0x2cbc3c8 VA: 0x75952d43c8
	public Void OnBtnBack() { }
	// RVA: 0x2cbb790 VA: 0x75952d3790
	private Void _TriggerTutorialCoroutine() { }
	// RVA: 0x2cbb44c VA: 0x75952d344c
	private Void _StopTutorialCoroutine() { }
	// RVA: 0x2cbc56c VA: 0x75952d456c
	private IEnumerator _WaitAndRaiseAVGSignal() { }
	// RVA: 0x2cba7dc VA: 0x75952d27dc
	private Void _InitIfNot() { }
	// RVA: 0x2cbc6c4 VA: 0x75952d46c4
	private Void _OnCharEdit(Int32 cardId) { }
	// RVA: 0x2cbc20c VA: 0x75952d420c
	private Void _DoStartBattle() { }
	// RVA: 0x2cbc9d4 VA: 0x75952d49d4
	private Boolean _CheckIfStartBattleValid() { }
	// RVA: 0x2cbca6c VA: 0x75952d4a6c
	private Param _CreateParamToStartBattle() { }
	// RVA: 0x2cbe8a4 VA: 0x75952d68a4
	private static CharacterCardViewModel _PickRandomCharacter(SquadItemStruct[] squad) { }
	// RVA: 0x2cbd158 VA: 0x75952d5158
	private Void _InvokedStartBattle(Param param) { }
	// RVA: 0x2cbea70 VA: 0x75952d6a70
	private Void _OnStartBattleSuccess() { }
	// RVA: 0x2cbead4 VA: 0x75952d6ad4
	public Void .ctor() { }
	// RVA: 0x2cbebf0 VA: 0x75952d6bf0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2cbebf8 VA: 0x75952d6bf8
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x2cbec00 VA: 0x75952d6c00
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2cbec08 VA: 0x75952d6c08
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```