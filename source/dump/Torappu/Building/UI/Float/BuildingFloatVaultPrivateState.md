# BuildingFloatVaultPrivateState

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `Text _comfortText`

- `GameObject _panelNoCharTip`

- `GameObject _panelFavor`

- `Text _txtFavor`

- `Image _imgFavorUpLevel`

- `GameObject _panelRoomChar`

- `Image _imgRoomChar`

- `GameObject _panelCharRecall`

- `Transform _shopPanelHolder`

- `DIYShopPanel m_diyShopPanel`

- `Coroutine m_interactFurniture`


## Properties

- `Boolean DIYShopShown`


## Methods

- `Boolean get_DIYShopShown()`

- `Void _UpdatePrivateRoomInfo()`

- `Void _UpdateFavorUpLevel(Int32)`

- `Int32 _LoadComfortBySlot(RoomSlotModel)`

- `Void EventOnDIYClick()`

- `Void EventOnDIYShopClick()`

- `Void <EventOnDIYShopClick>b__26_0(Int32)`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_TriggerModeChange()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Void <>xLuaBaseProxy_OnStateUpdated(Boolean)`

- `Void <>xLuaBaseProxy_OnStateFocusUpdate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatVaultPrivateState : BuildingFloatVaultInfoState
{
	private Text _comfortText; // 0xa0
	private GameObject _panelNoCharTip; // 0xa8
	private GameObject _panelFavor; // 0xb0
	private Text _txtFavor; // 0xb8
	private Image _imgFavorUpLevel; // 0xc0
	private Sprite[] _favorUpLevelIcons; // 0xc8
	private GameObject _panelRoomChar; // 0xd0
	private Image _imgRoomChar; // 0xd8
	private GameObject _panelCharRecall; // 0xe0
	private Transform _shopPanelHolder; // 0xe8
	private DIYShopPanel m_diyShopPanel; // 0xf0
	private Coroutine m_interactFurniture; // 0xf8
	private static DelegateBridge __Hotfix0_get_DIYShopShown; // 0x0
	private static DelegateBridge __Hotfix0_get_state; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_TriggerModeChange; // 0x20
	private static DelegateBridge __Hotfix0_OnExit; // 0x28
	private static DelegateBridge __Hotfix0_OnStateUpdated; // 0x30
	private static DelegateBridge __Hotfix0_OnStateFocusUpdate; // 0x38
	private static DelegateBridge __Hotfix0__UpdatePrivateRoomInfo; // 0x40
	private static DelegateBridge __Hotfix0__UpdateFavorUpLevel; // 0x48
	private static DelegateBridge __Hotfix0__LoadComfortBySlot; // 0x50
	private static DelegateBridge __Hotfix0_EventOnDIYClick; // 0x58
	private static DelegateBridge __Hotfix0_EventOnDIYShopClick; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Boolean DIYShopShown { get; }
	protected override FloatState state { get; }

	// RVA: 0x3e295d0 VA: 0x75964415d0
	public Boolean get_DIYShopShown() { }
	// RVA: 0x3e29690 VA: 0x7596441690
	protected override FloatState get_state() { }
	// RVA: 0x3e296f8 VA: 0x75964416f8
	protected override Void OnInit() { }
	// RVA: 0x3e298c4 VA: 0x75964418c4
	protected override Void OnEnter() { }
	// RVA: 0x3e29c50 VA: 0x7596441c50
	protected override Void TriggerModeChange() { }
	// RVA: 0x3e29d1c VA: 0x7596441d1c
	protected override Void OnExit() { }
	// RVA: 0x3e29df8 VA: 0x7596441df8
	protected override Void OnStateUpdated(Boolean isActive) { }
	// RVA: 0x3e2a364 VA: 0x7596442364
	protected override Void OnStateFocusUpdate() { }
	// RVA: 0x3e29ea0 VA: 0x7596441ea0
	private Void _UpdatePrivateRoomInfo() { }
	// RVA: 0x3e2a3d8 VA: 0x75964423d8
	private Void _UpdateFavorUpLevel(Int32 comfort) { }
	// RVA: 0x3e29ab8 VA: 0x7596441ab8
	private Int32 _LoadComfortBySlot(RoomSlotModel slotModel) { }
	// RVA: 0x3e2a5d0 VA: 0x75964425d0
	public Void EventOnDIYClick() { }
	// RVA: 0x3e2a690 VA: 0x7596442690
	public Void EventOnDIYShopClick() { }
	// RVA: 0x3e2a8ec VA: 0x75964428ec
	public Void .ctor() { }
	// RVA: 0x3e2a97c VA: 0x759644297c
	private Void <EventOnDIYShopClick>b__26_0(Int32 result) { }
	// RVA: 0x3e2ab50 VA: 0x7596442b50
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x3e2ab54 VA: 0x7596442b54
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3e2ab58 VA: 0x7596442b58
	private Void <>xLuaBaseProxy_TriggerModeChange() { }
	// RVA: 0x3e2ab5c VA: 0x7596442b5c
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x3e2ab60 VA: 0x7596442b60
	private Void <>xLuaBaseProxy_OnStateUpdated(Boolean P0) { }
	// RVA: 0x3e2ab68 VA: 0x7596442b68
	private Void <>xLuaBaseProxy_OnStateFocusUpdate() { }
}
```