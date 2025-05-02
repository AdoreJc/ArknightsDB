# Act1VAutoChessChessShopQuickAssistState

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessChessShopQuickAssistView _view`

- `RectTransform _rectTopMenuContainer`

- `Boolean m_inited`

- `Act1VAutoChessChessShopQuickAssistStateBean m_stateBean`

- `Act1VAutoChessFriendAssistPlugin m_friendAssistPlugin`


## Methods

- `Void _RegisterFromCommonFriendAssistState(IStateBean)`

- `Void _RegisterToCommonFriendAssistState(IStateBean)`

- `Void _InitIfNot()`

- `Void _TryToTriggerShopAvg()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnItemCardCancelClick(Object)`

- `Void _OnChessCharItemCancelSuc(String)`

- `Void _OnItemCardAssistClick(Object)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopQuickAssistState : PopupFadeState, IValueMsgReceiver
{
	private Act1VAutoChessChessShopQuickAssistView _view; // 0x70
	private RectTransform _rectTopMenuContainer; // 0x78
	private Boolean m_inited; // 0x80
	private Act1VAutoChessChessShopQuickAssistStateBean m_stateBean; // 0x88
	private Act1VAutoChessFriendAssistPlugin m_friendAssistPlugin; // 0x90
	public const Int32 MSG_ITEM_CARD_CANCEL_CLICK; // 0x0
	public const Int32 MSG_ITEM_CARD_ASSIST_CLICK; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__RegisterFromCommonFriendAssistState; // 0x20
	private static DelegateBridge __Hotfix0__RegisterToCommonFriendAssistState; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__TryToTriggerShopAvg; // 0x38
	private static DelegateBridge __Hotfix0_OnMessage; // 0x40
	private static DelegateBridge __Hotfix0__OnItemCardCancelClick; // 0x48
	private static DelegateBridge __Hotfix0__OnChessCharItemCancelSuc; // 0x50
	private static DelegateBridge __Hotfix0__OnItemCardAssistClick; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x330be58 VA: 0x7595923e58
	public override IStateBean GetCacheBean() { }
	// RVA: 0x330bec0 VA: 0x7595923ec0
	protected override Void OnEnter() { }
	// RVA: 0x330c328 VA: 0x7595924328
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x330c4a0 VA: 0x75959244a0
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x330c618 VA: 0x7595924618
	private Void _RegisterFromCommonFriendAssistState(IStateBean stateBean) { }
	// RVA: 0x330c768 VA: 0x7595924768
	private Void _RegisterToCommonFriendAssistState(IStateBean stateBean) { }
	// RVA: 0x330c06c VA: 0x759592406c
	private Void _InitIfNot() { }
	// RVA: 0x330c26c VA: 0x759592426c
	private Void _TryToTriggerShopAvg() { }
	// RVA: 0x330c848 VA: 0x7595924848
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x330c910 VA: 0x7595924910
	private Void _OnItemCardCancelClick(Object msgObj) { }
	// RVA: 0x330cfdc VA: 0x7595924fdc
	private Void _OnChessCharItemCancelSuc(String chessId) { }
	// RVA: 0x330cc70 VA: 0x7595924c70
	private Void _OnItemCardAssistClick(Object msgObj) { }
	// RVA: 0x330d0c0 VA: 0x75959250c0
	public Void .ctor() { }
	// RVA: 0x330d1b0 VA: 0x75959251b0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x330d1b8 VA: 0x75959251b8
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x330d1c0 VA: 0x75959251c0
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```