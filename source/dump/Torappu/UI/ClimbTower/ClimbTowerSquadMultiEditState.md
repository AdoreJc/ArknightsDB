# ClimbTowerSquadMultiEditState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerSquadMultiEditView _view`

- `ClimbTowerMenuButton _menuButtonPrefab`

- `RectTransform _backBtnRt`

- `ScrollRect _scrollRect`

- `ClimbTowerSquadMultiEditStateBean m_stateBean`

- `Boolean m_hasInited`

- `MenuAdapter m_menuAdapter`


## Methods

- `Void _InitIfNot()`

- `Void _NavToEditState(IStateBean)`

- `Void OnEditTypeSwitch()`

- `Void _OnProfessionClicked(ProfessionCategory)`

- `Void _OnConfirmBtnClicked()`

- `Void _OnSkillSelect(Int32, String)`

- `Void _OnEquipSelect(Int32, String)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _SetScrollViewDragDelegate(UIWrappedScrollRect)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadMultiEditState : PopupFadeState, IValueMsgReceiver
{
	private ClimbTowerSquadMultiEditView _view; // 0x70
	private ClimbTowerMenuButton _menuButtonPrefab; // 0x78
	private RectTransform _backBtnRt; // 0x80
	private ScrollRect _scrollRect; // 0x88
	private ClimbTowerSquadMultiEditStateBean m_stateBean; // 0x90
	private Boolean m_hasInited; // 0x98
	private MenuAdapter m_menuAdapter; // 0xa0
	public const Int32 SET_EQUIP_SCROLL_DRAG_DELEGATE; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__NavToEditState; // 0x20
	private static DelegateBridge __Hotfix0_OnEditTypeSwitch; // 0x28
	private static DelegateBridge __Hotfix0__OnProfessionClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnConfirmBtnClicked; // 0x38
	private static DelegateBridge __Hotfix0__OnSkillSelect; // 0x40
	private static DelegateBridge __Hotfix0__OnEquipSelect; // 0x48
	private static DelegateBridge __Hotfix0_OnMessage; // 0x50
	private static DelegateBridge __Hotfix0__SetScrollViewDragDelegate; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x2cc4588 VA: 0x75952dc588
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2cc45f0 VA: 0x75952dc5f0
	protected override Void OnEnter() { }
	// RVA: 0x2cc4818 VA: 0x75952dc818
	private Void _InitIfNot() { }
	// RVA: 0x2cc4c18 VA: 0x75952dcc18
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2cc4d90 VA: 0x75952dcd90
	private Void _NavToEditState(IStateBean stateBean) { }
	// RVA: 0x2cc4e9c VA: 0x75952dce9c
	public Void OnEditTypeSwitch() { }
	// RVA: 0x2cc4f80 VA: 0x75952dcf80
	private Void _OnProfessionClicked(ProfessionCategory profession) { }
	// RVA: 0x2cc500c VA: 0x75952dd00c
	private Void _OnConfirmBtnClicked() { }
	// RVA: 0x2cc52fc VA: 0x75952dd2fc
	private Void _OnSkillSelect(Int32 cardId, String skillId) { }
	// RVA: 0x2cc5500 VA: 0x75952dd500
	private Void _OnEquipSelect(Int32 cardId, String equipId) { }
	// RVA: 0x2cc5648 VA: 0x75952dd648
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2cc577c VA: 0x75952dd77c
	private Void _SetScrollViewDragDelegate(UIWrappedScrollRect equipScrollRect) { }
	// RVA: 0x2cc5808 VA: 0x75952dd808
	public Void .ctor() { }
	// RVA: 0x2cc5964 VA: 0x75952dd964
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2cc596c VA: 0x75952dd96c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```