# SandboxV2AdminMainCharRepoPanel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2SquadGroupPanel _squadGroupPanelPrefab`

- `RectTransform _squadPanelRt`

- `Boolean m_hasInited`

- `SandboxV2SquadGroupPanel m_squadGroupPanel`

- `Int32 m_cachedDineCharInstId`

- `OpenOption m_cachedOpenOption`

- `Input m_cachedToolSelectInput`


## Methods

- `Void OpenDineState(Int32)`

- `Boolean IsStateStable()`

- `Void OpenWorkbenchDialog(Options)`

- `Void OpenCharSelectState(OpenOption)`

- `Void OpenToolSelectState(Input)`

- `Void _OnJumpFromToolSelectState(IStateBean)`

- `Void _OnJumpToToolSelectState(IStateBean)`

- `Void _OnJumpFromCharSelectState(IStateBean)`

- `Void _OnJumpToCharSelectState(IStateBean)`

- `Void _OnJumpFromDineState(IStateBean)`

- `Void _OnJumpToDineState(IStateBean)`

- `Void _InitIfNot()`

- `Boolean IsRepoShow()`

- `Boolean IsNaviPanelShow()`

- `SandboxV2SquadPanelShowMode GetPanelShowMode()`

- `Void <>xLuaBaseProxy_OnHideProcess(Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainCharRepoPanel : SandboxV2AdminMainTabPanel, ISandboxV2SquadPanelContext
{
	private SandboxV2SquadGroupPanel _squadGroupPanelPrefab; // 0x60
	private RectTransform _squadPanelRt; // 0x68
	private Boolean m_hasInited; // 0x70
	private SandboxV2SquadGroupPanel m_squadGroupPanel; // 0x78
	private Int32 m_cachedDineCharInstId; // 0x80
	private OpenOption m_cachedOpenOption; // 0x88
	private Input m_cachedToolSelectInput; // 0xe0
	private static DelegateBridge __Hotfix0_get_panelType; // 0x0
	private static DelegateBridge __Hotfix0_get_topTitle; // 0x8
	private static DelegateBridge __Hotfix0_OpenDineState; // 0x10
	private static DelegateBridge __Hotfix0_IsStateStable; // 0x18
	private static DelegateBridge __Hotfix0_OpenWorkbenchDialog; // 0x20
	private static DelegateBridge __Hotfix0_OpenCharSelectState; // 0x28
	private static DelegateBridge __Hotfix0_OpenToolSelectState; // 0x30
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x38
	private static DelegateBridge __Hotfix0_OnHideProcess; // 0x40
	private static DelegateBridge __Hotfix0_GetToDataListener; // 0x48
	private static DelegateBridge __Hotfix0_GetFromDataListener; // 0x50
	private static DelegateBridge __Hotfix0_GetBinderView; // 0x58
	private static DelegateBridge __Hotfix0__OnJumpFromToolSelectState; // 0x60
	private static DelegateBridge __Hotfix0__OnJumpToToolSelectState; // 0x68
	private static DelegateBridge __Hotfix0__OnJumpFromCharSelectState; // 0x70
	private static DelegateBridge __Hotfix0__OnJumpToCharSelectState; // 0x78
	private static DelegateBridge __Hotfix0__OnJumpFromDineState; // 0x80
	private static DelegateBridge __Hotfix0__OnJumpToDineState; // 0x88
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x90
	private static DelegateBridge __Hotfix0_IsRepoShow; // 0x98
	private static DelegateBridge __Hotfix0_IsNaviPanelShow; // 0xa0
	private static DelegateBridge __Hotfix0_GetPanelShowMode; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public override SandboxV2AdminMainPanelType panelType { get; }
	public override String topTitle { get; }

	// RVA: 0x24b8934 VA: 0x7594ad0934
	public override SandboxV2AdminMainPanelType get_panelType() { }
	// RVA: 0x24b899c VA: 0x7594ad099c
	public override String get_topTitle() { }
	// RVA: 0x24b8a28 VA: 0x7594ad0a28
	public Void OpenDineState(Int32 charInstId) { }
	// RVA: 0x24b8b54 VA: 0x7594ad0b54
	public Boolean IsStateStable() { }
	// RVA: 0x24b8ca0 VA: 0x7594ad0ca0
	public Void OpenWorkbenchDialog(Options options) { }
	// RVA: 0x24b8d30 VA: 0x7594ad0d30
	public Void OpenCharSelectState(OpenOption option) { }
	// RVA: 0x24b8e7c VA: 0x7594ad0e7c
	public Void OpenToolSelectState(Input toolSelectInput) { }
	// RVA: 0x24b8fc4 VA: 0x7594ad0fc4
	protected override Void OnUpdate(SandboxV2AdminMainTabPanelUpdateCase updateCase) { }
	// RVA: 0x24b9184 VA: 0x7594ad1184
	protected override Void OnHideProcess(Action done) { }
	// RVA: 0x24b9260 VA: 0x7594ad1260
	public override IEnumerable`1 GetToDataListener() { }
	// RVA: 0x24b9350 VA: 0x7594ad1350
	public override IEnumerable`1 GetFromDataListener() { }
	// RVA: 0x24b9440 VA: 0x7594ad1440
	public DataBinder`1 GetBinderView() { }
	// RVA: 0x24b94a4 VA: 0x7594ad14a4
	private Void _OnJumpFromToolSelectState(IStateBean stateBean) { }
	// RVA: 0x24b95e0 VA: 0x7594ad15e0
	private Void _OnJumpToToolSelectState(IStateBean stateBean) { }
	// RVA: 0x24b96e0 VA: 0x7594ad16e0
	private Void _OnJumpFromCharSelectState(IStateBean stateBean) { }
	// RVA: 0x24b9818 VA: 0x7594ad1818
	private Void _OnJumpToCharSelectState(IStateBean stateBean) { }
	// RVA: 0x24b9918 VA: 0x7594ad1918
	private Void _OnJumpFromDineState(IStateBean obj) { }
	// RVA: 0x24b99a0 VA: 0x7594ad19a0
	private Void _OnJumpToDineState(IStateBean stateBean) { }
	// RVA: 0x24b9070 VA: 0x7594ad1070
	private Void _InitIfNot() { }
	// RVA: 0x24b9a88 VA: 0x7594ad1a88
	public Boolean IsRepoShow() { }
	// RVA: 0x24b9af0 VA: 0x7594ad1af0
	public Boolean IsNaviPanelShow() { }
	// RVA: 0x24b9b54 VA: 0x7594ad1b54
	public SandboxV2SquadPanelShowMode GetPanelShowMode() { }
	// RVA: 0x24b9bb8 VA: 0x7594ad1bb8
	public Void .ctor() { }
	// RVA: 0x24b9c24 VA: 0x7594ad1c24
	private Void <>xLuaBaseProxy_OnHideProcess(Action P0) { }
	// RVA: 0x24b9c28 VA: 0x7594ad1c28
	private IEnumerable`1 <>xLuaBaseProxy_GetToDataListener() { }
	// RVA: 0x24b9c2c VA: 0x7594ad1c2c
	private IEnumerable`1 <>xLuaBaseProxy_GetFromDataListener() { }
}
```