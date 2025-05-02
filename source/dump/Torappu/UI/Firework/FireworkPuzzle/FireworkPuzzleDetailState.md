# FireworkPuzzleDetailState

**Namespace:** `Torappu.UI.Firework.FireworkPuzzle`


## Fields

- `FireworkPuzzleDetailView _view`

- `RectTransform _topMenuContainer`

- `FireworkPuzzleDetailStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void _RegisterToResultState(IStateBean)`

- `Void _InitIfNot()`

- `Void _EventOnBack()`

- `Boolean _IsUIStable()`

- `Void _EventOnSubListRaycastClick()`

- `Void _EventOnPlateListItemClick(String)`

- `Void _EventOnPlateSubListItemClick(Object)`

- `Void _EventOnPlateFilledListItemClick(Object)`

- `Void _EventOnBtnClearAllClick()`

- `Void _OpenResultState()`

- `Void EventOnBtnHintClick()`

- `Void EventOnBtnComfirm()`

- `Void <EventOnBtnComfirm>b__22_0(FireworkCompletePuzzleResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkPuzzle
public class FireworkPuzzleDetailState : FireworkBaseState
{
	private FireworkPuzzleDetailView _view; // 0x70
	private RectTransform _topMenuContainer; // 0x78
	private FireworkPuzzleDetailStateBean m_stateBean; // 0x80
	private List`1 m_cacheSlotList; // 0x88
	private List`1 m_cacheRewardList; // 0x90
	private Boolean m_hasInited; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x8
	private static DelegateBridge __Hotfix0__RegisterToResultState; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__EventOnBack; // 0x30
	private static DelegateBridge __Hotfix0__IsUIStable; // 0x38
	private static DelegateBridge __Hotfix0_OnMessage; // 0x40
	private static DelegateBridge __Hotfix0__EventOnSubListRaycastClick; // 0x48
	private static DelegateBridge __Hotfix0__EventOnPlateListItemClick; // 0x50
	private static DelegateBridge __Hotfix0__EventOnPlateSubListItemClick; // 0x58
	private static DelegateBridge __Hotfix0__EventOnPlateFilledListItemClick; // 0x60
	private static DelegateBridge __Hotfix0__EventOnBtnClearAllClick; // 0x68
	private static DelegateBridge __Hotfix0__OpenResultState; // 0x70
	private static DelegateBridge __Hotfix0_EventOnBtnHintClick; // 0x78
	private static DelegateBridge __Hotfix0_EventOnBtnComfirm; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x28fa790 VA: 0x7594f12790
	public override IStateBean GetCacheBean() { }
	// RVA: 0x28fa7f8 VA: 0x7594f127f8
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x28fa970 VA: 0x7594f12970
	private Void _RegisterToResultState(IStateBean targetBean) { }
	// RVA: 0x28faac0 VA: 0x7594f12ac0
	protected override Void OnEnter() { }
	// RVA: 0x28fae48 VA: 0x7594f12e48
	protected override Void OnResume() { }
	// RVA: 0x28fad70 VA: 0x7594f12d70
	private Void _InitIfNot() { }
	// RVA: 0x28faebc VA: 0x7594f12ebc
	private Void _EventOnBack() { }
	// RVA: 0x28fb0cc VA: 0x7594f130cc
	private Boolean _IsUIStable() { }
	// RVA: 0x28fb1a8 VA: 0x7594f131a8
	public override Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x28fb668 VA: 0x7594f13668
	private Void _EventOnSubListRaycastClick() { }
	// RVA: 0x28fb2d4 VA: 0x7594f132d4
	private Void _EventOnPlateListItemClick(String groupId) { }
	// RVA: 0x28fb3d0 VA: 0x7594f133d0
	private Void _EventOnPlateSubListItemClick(Object objVal) { }
	// RVA: 0x28fb524 VA: 0x7594f13524
	private Void _EventOnPlateFilledListItemClick(Object objVal) { }
	// RVA: 0x28fb748 VA: 0x7594f13748
	private Void _EventOnBtnClearAllClick() { }
	// RVA: 0x28fb828 VA: 0x7594f13828
	private Void _OpenResultState() { }
	// RVA: 0x28fb930 VA: 0x7594f13930
	public Void EventOnBtnHintClick() { }
	// RVA: 0x28fbc70 VA: 0x7594f13c70
	public Void EventOnBtnComfirm() { }
	// RVA: 0x28fbf60 VA: 0x7594f13f60
	public Void .ctor() { }
	// RVA: 0x28fc058 VA: 0x7594f14058
	private Void <EventOnBtnComfirm>b__22_0(FireworkCompletePuzzleResponse response) { }
	// RVA: 0x28fc080 VA: 0x7594f14080
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x28fc088 VA: 0x7594f14088
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x28fc090 VA: 0x7594f14090
	private Void <>xLuaBaseProxy_OnResume() { }
}
```