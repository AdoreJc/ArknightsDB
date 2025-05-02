# Act1VAutoChessEntryState

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Boolean m_isInited`

- `Act1VAutoChessEntryController m_controller`


## Methods

- `Boolean CustomSetActive(Boolean)`

- `Void _InitIfNot()`

- `Void <RegisterToDataListener>b__7_0(IStateBean)`

- `Void <RegisterToDataListener>b__7_1(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryState : PopupFadeState, IPopupCustomActive
{
	private Boolean m_isInited; // 0x70
	private Act1VAutoChessEntryController m_controller; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_CustomSetActive; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x333b0bc VA: 0x75959530bc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x333b120 VA: 0x7595953120
	public Boolean CustomSetActive(Boolean active) { }
	// RVA: 0x333b1f4 VA: 0x75959531f4
	protected override Void OnEnter() { }
	// RVA: 0x333b364 VA: 0x7595953364
	protected override Void OnResume() { }
	// RVA: 0x333b268 VA: 0x7595953268
	private Void _InitIfNot() { }
	// RVA: 0x333b3fc VA: 0x75959533fc
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x333b670 VA: 0x7595953670
	public Void .ctor() { }
	// RVA: 0x333b6e0 VA: 0x75959536e0
	private Void <RegisterToDataListener>b__7_0(IStateBean stateBean) { }
	// RVA: 0x333b784 VA: 0x7595953784
	private Void <RegisterToDataListener>b__7_1(IStateBean stateBean) { }
	// RVA: 0x333b884 VA: 0x7595953884
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x333b88c VA: 0x759595388c
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x333b894 VA: 0x7595953894
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```