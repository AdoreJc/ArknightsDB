# ItemRepoChooseCharState

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemRepoChooseCharStateBean m_stateBean`

- `ItemRepoSelectCharView _selectCharView`

- `ItemRepoSelectCharGridView _selectCharGrid`

- `Text _viewTitleText`

- `UIStringEvent m_clickEvent`

- `Boolean m_isInited`


## Methods

- `Void ToDetailState(IStateBean)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void OnItemClick(String)`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoChooseCharState : PopupFloatState, IValueMsgReceiver
{
	public const Int32 ITEM_CLICK_CALL; // 0x0
	private ItemRepoChooseCharStateBean m_stateBean; // 0x70
	private ItemRepoSelectCharView _selectCharView; // 0x78
	private ItemRepoSelectCharGridView _selectCharGrid; // 0x80
	private Text _viewTitleText; // 0x88
	private UIStringEvent m_clickEvent; // 0x90
	private Boolean m_isInited; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x8
	private static DelegateBridge __Hotfix0_ToDetailState; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2d1d048 VA: 0x7595335048
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d1d0b0 VA: 0x75953350b0
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2d1d228 VA: 0x7595335228
	public Void ToDetailState(IStateBean stateBean) { }
	// RVA: 0x2d1d324 VA: 0x7595335324
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2d1d3f4 VA: 0x75953353f4
	public Void OnItemClick(String itemId) { }
	// RVA: 0x2d1d4c0 VA: 0x75953354c0
	private Void _InitIfNot() { }
	// RVA: 0x2d1d644 VA: 0x7595335644
	protected override Void OnEnter() { }
	// RVA: 0x2d1d990 VA: 0x7595335990
	public Void .ctor() { }
	// RVA: 0x2d1da3c VA: 0x7595335a3c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2d1da44 VA: 0x7595335a44
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```