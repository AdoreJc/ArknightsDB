# SandboxV2RacerInventoryState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2RacerInventoryTopView _topView`

- `SandboxV2RacerInventoryListView _listView`

- `SandboxV2RacerInventoryInfoView _infoView`

- `Sprite _imgReleaseIcon`

- `Sprite _imgRefreshTalentIcon`

- `SandboxV2RacerInventoryRefreshTalentDeco _talentDialogDecoPrefab`

- `SandboxV2RacerInventoryStateBean m_stateBean`

- `Boolean m_hasInited`

- `Int32 m_dialogInstId`


## Methods

- `Void _OnJumpToTempInventory(IStateBean)`

- `Void _EventOnBackBtnClicked()`

- `Void _EventOnRacerCardClicked(String)`

- `Void _EventOnRacerMarkClicked()`

- `Void _EventOnReleaseClicked()`

- `Void _EventOnRefreshTalentClicked()`

- `Void _EventOnStartBattleClicked()`

- `Void _EventOnOpenTempBagClicked()`

- `Void _EventOnMedalGroupClicked()`

- `Void _InitIfNot()`

- `Void _HandleSaveMarkProceed(SandboxV2RacingSaveMarkResponse)`

- `Void _RefreshTalent(String)`

- `Void _ReleaseRacer(String)`

- `Void _HandleReleaseProceed(SandboxV2RacingReleaseResponse)`

- `Void _HandleRefreshTalentProceed(SandboxV2RacingLearnTalentResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacerInventoryState : SandboxV2RacerInventoryBaseState, IHotfixable
{
	public const Int32 DEFAULT_FOCUS_SEQUENCE_NUM; // 0x0
	private SandboxV2RacerInventoryTopView _topView; // 0x70
	private SandboxV2RacerInventoryListView _listView; // 0x78
	private SandboxV2RacerInventoryInfoView _infoView; // 0x80
	private Sprite _imgReleaseIcon; // 0x88
	private Sprite _imgRefreshTalentIcon; // 0x90
	private SandboxV2RacerInventoryRefreshTalentDeco _talentDialogDecoPrefab; // 0x98
	private SandboxV2RacerInventoryStateBean m_stateBean; // 0xa0
	private Boolean m_hasInited; // 0xa8
	private Int32 m_dialogInstId; // 0xac
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__OnJumpToTempInventory; // 0x20
	private static DelegateBridge __Hotfix0_OnMessage; // 0x28
	private static DelegateBridge __Hotfix0__EventOnBackBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0__EventOnRacerCardClicked; // 0x38
	private static DelegateBridge __Hotfix0__EventOnRacerMarkClicked; // 0x40
	private static DelegateBridge __Hotfix0__EventOnReleaseClicked; // 0x48
	private static DelegateBridge __Hotfix0__EventOnRefreshTalentClicked; // 0x50
	private static DelegateBridge __Hotfix0__EventOnStartBattleClicked; // 0x58
	private static DelegateBridge __Hotfix0__EventOnOpenTempBagClicked; // 0x60
	private static DelegateBridge __Hotfix0__EventOnMedalGroupClicked; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x70
	private static DelegateBridge __Hotfix0__HandleSaveMarkProceed; // 0x78
	private static DelegateBridge __Hotfix0__RefreshTalent; // 0x80
	private static DelegateBridge __Hotfix0__ReleaseRacer; // 0x88
	private static DelegateBridge __Hotfix0__HandleReleaseProceed; // 0x90
	private static DelegateBridge __Hotfix0__HandleRefreshTalentProceed; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x25e2490 VA: 0x7594bfa490
	protected override Void OnEnter() { }
	// RVA: 0x25e2b88 VA: 0x7594bfab88
	protected override Void OnResume() { }
	// RVA: 0x25e2ce8 VA: 0x7594bface8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x25e2d50 VA: 0x7594bfad50
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x25e2ec8 VA: 0x7594bfaec8
	private Void _OnJumpToTempInventory(IStateBean obj) { }
	// RVA: 0x25e2fcc VA: 0x7594bfafcc
	public override Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x25e3160 VA: 0x7594bfb160
	private Void _EventOnBackBtnClicked() { }
	// RVA: 0x25e32c0 VA: 0x7594bfb2c0
	private Void _EventOnRacerCardClicked(String instId) { }
	// RVA: 0x25e33fc VA: 0x7594bfb3fc
	private Void _EventOnRacerMarkClicked() { }
	// RVA: 0x25e3b18 VA: 0x7594bfbb18
	private Void _EventOnReleaseClicked() { }
	// RVA: 0x25e3688 VA: 0x7594bfb688
	private Void _EventOnRefreshTalentClicked() { }
	// RVA: 0x25e3e18 VA: 0x7594bfbe18
	private Void _EventOnStartBattleClicked() { }
	// RVA: 0x25e4040 VA: 0x7594bfc040
	private Void _EventOnOpenTempBagClicked() { }
	// RVA: 0x25e41fc VA: 0x7594bfc1fc
	private Void _EventOnMedalGroupClicked() { }
	// RVA: 0x25e264c VA: 0x7594bfa64c
	private Void _InitIfNot() { }
	// RVA: 0x25e4864 VA: 0x7594bfc864
	private Void _HandleSaveMarkProceed(SandboxV2RacingSaveMarkResponse response) { }
	// RVA: 0x25e498c VA: 0x7594bfc98c
	private Void _RefreshTalent(String instId) { }
	// RVA: 0x25e4bfc VA: 0x7594bfcbfc
	private Void _ReleaseRacer(String instId) { }
	// RVA: 0x25e4f18 VA: 0x7594bfcf18
	private Void _HandleReleaseProceed(SandboxV2RacingReleaseResponse response) { }
	// RVA: 0x25e5100 VA: 0x7594bfd100
	private Void _HandleRefreshTalentProceed(SandboxV2RacingLearnTalentResponse response) { }
	// RVA: 0x25e5838 VA: 0x7594bfd838
	public Void .ctor() { }
	// RVA: 0x25e598c VA: 0x7594bfd98c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x25e5994 VA: 0x7594bfd994
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x25e599c VA: 0x7594bfd99c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```