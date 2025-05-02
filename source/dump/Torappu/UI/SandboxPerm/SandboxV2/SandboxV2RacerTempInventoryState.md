# SandboxV2RacerTempInventoryState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2RacerTempInventoryTopView _topView`

- `SandboxV2RacerTempInventoryListView _listView`

- `SandboxV2RacerTempInventoryInfoView _infoView`

- `Sprite _imgReleaseIcon`

- `SandboxV2RacerTempInventoryStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void _EventOnBackBtnClicked()`

- `Void _EventOnRacerCardClicked(String)`

- `Void _EventOnRegisterClicked()`

- `Void _EventOnReleaseAllClicked()`

- `Void _InitIfNot()`

- `Void _HandleRegisterProceed(SandboxV2RacingRegisterResponse)`

- `Void _ReleaseAllRacer()`

- `Void _HandleReleaseAllProceed(SandboxV2RacingReleaseResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacerTempInventoryState : SandboxV2RacerInventoryBaseState, IHotfixable
{
	private SandboxV2RacerTempInventoryTopView _topView; // 0x70
	private SandboxV2RacerTempInventoryListView _listView; // 0x78
	private SandboxV2RacerTempInventoryInfoView _infoView; // 0x80
	private Sprite _imgReleaseIcon; // 0x88
	private SandboxV2RacerTempInventoryStateBean m_stateBean; // 0x90
	private Boolean m_hasInited; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__EventOnBackBtnClicked; // 0x20
	private static DelegateBridge __Hotfix0__EventOnRacerCardClicked; // 0x28
	private static DelegateBridge __Hotfix0__EventOnRegisterClicked; // 0x30
	private static DelegateBridge __Hotfix0__EventOnReleaseAllClicked; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__HandleRegisterProceed; // 0x48
	private static DelegateBridge __Hotfix0__ReleaseAllRacer; // 0x50
	private static DelegateBridge __Hotfix0__HandleReleaseAllProceed; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x25f4728 VA: 0x7594c0c728
	public override IStateBean GetCacheBean() { }
	// RVA: 0x25f4790 VA: 0x7594c0c790
	protected override Void OnEnter() { }
	// RVA: 0x25f49e4 VA: 0x7594c0c9e4
	protected override Void OnResume() { }
	// RVA: 0x25f4fe0 VA: 0x7594c0cfe0
	public override Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x25f5114 VA: 0x7594c0d114
	private Void _EventOnBackBtnClicked() { }
	// RVA: 0x25f5270 VA: 0x7594c0d270
	private Void _EventOnRacerCardClicked(String instId) { }
	// RVA: 0x25f53ac VA: 0x7594c0d3ac
	private Void _EventOnRegisterClicked() { }
	// RVA: 0x25f56b0 VA: 0x7594c0d6b0
	private Void _EventOnReleaseAllClicked() { }
	// RVA: 0x25f4840 VA: 0x7594c0c840
	private Void _InitIfNot() { }
	// RVA: 0x25f5944 VA: 0x7594c0d944
	private Void _HandleRegisterProceed(SandboxV2RacingRegisterResponse response) { }
	// RVA: 0x25f5c18 VA: 0x7594c0dc18
	private Void _ReleaseAllRacer() { }
	// RVA: 0x25f5f68 VA: 0x7594c0df68
	private Void _HandleReleaseAllProceed(SandboxV2RacingReleaseResponse response) { }
	// RVA: 0x25f6074 VA: 0x7594c0e074
	public Void .ctor() { }
	// RVA: 0x25f61cc VA: 0x7594c0e1cc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x25f61d4 VA: 0x7594c0e1d4
	private Void <>xLuaBaseProxy_OnResume() { }
}
```