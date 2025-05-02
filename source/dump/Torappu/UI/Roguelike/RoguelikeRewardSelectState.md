# RoguelikeRewardSelectState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeRewardSelectStateBean m_stateBean`

- `RoguelikeRewardSelectView _view`

- `RectTransform _panelTopMenu`

- `UIStyleProvider _styleProvider`

- `RoguelikeCommonTopMenu m_topMenu`

- `MenuAdapter m_menuAdapter`

- `RoguelikeRewardStyle m_style`

- `Boolean m_inited`

- `String m_topicId`


## Methods

- `Void _InitIfNot()`

- `Void OnClick(Int32)`

- `Void _HandleOnReceive(RoguelikeRewardItemViewModel, Int32)`

- `Void _ProcessCapsuleReceive(RoguelikeItemBundle)`

- `Void _ProcessChestReceive(RoguelikeDungeonController, Int32, RoguelikeItemBundle)`

- `Void _ProcessRecruitReceive(RoguelikeDungeonController)`

- `Boolean _IsReceiveChest(RoguelikeItemBundle)`

- `Void _ProcessChestEvent(String, Int32)`

- `Void _UseDiceToUnlockChest(String)`

- `Void _LeaveChestDirectly()`

- `Void _UseKeyToUnlockChest()`

- `Boolean _IsReceiveCapsule(RoguelikeItemBundle)`

- `Boolean _IsReceiveItem(RoguelikeItemBundle, RoguelikeGameItemType)`

- `Void <_ProcessRecruitReceive>b__17_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardSelectState : PopupFloatState
{
	private RoguelikeRewardSelectStateBean m_stateBean; // 0x70
	private RoguelikeRewardSelectView _view; // 0x78
	private RectTransform _panelTopMenu; // 0x80
	private UIStyleProvider _styleProvider; // 0x88
	private RoguelikeCommonTopMenu m_topMenu; // 0x90
	private MenuAdapter m_menuAdapter; // 0x98
	private RoguelikeRewardStyle m_style; // 0xa0
	private Boolean m_inited; // 0xa8
	private String m_topicId; // 0xb0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0__HandleOnReceive; // 0x20
	private static DelegateBridge __Hotfix0__ProcessCapsuleReceive; // 0x28
	private static DelegateBridge __Hotfix0__ProcessChestReceive; // 0x30
	private static DelegateBridge __Hotfix0__ProcessRecruitReceive; // 0x38
	private static DelegateBridge __Hotfix0__IsReceiveChest; // 0x40
	private static DelegateBridge __Hotfix0__ProcessChestEvent; // 0x48
	private static DelegateBridge __Hotfix0__UseDiceToUnlockChest; // 0x50
	private static DelegateBridge __Hotfix0__LeaveChestDirectly; // 0x58
	private static DelegateBridge __Hotfix0__UseKeyToUnlockChest; // 0x60
	private static DelegateBridge __Hotfix0__IsReceiveCapsule; // 0x68
	private static DelegateBridge __Hotfix0__IsReceiveItem; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x2a90f58 VA: 0x75950a8f58
	private Void _InitIfNot() { }
	// RVA: 0x2a91164 VA: 0x75950a9164
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2a911cc VA: 0x75950a91cc
	protected override Void OnEnter() { }
	// RVA: 0x2a91360 VA: 0x75950a9360
	public Void OnClick(Int32 index) { }
	// RVA: 0x2a9150c VA: 0x75950a950c
	private Void _HandleOnReceive(RoguelikeRewardItemViewModel model, Int32 subIndex) { }
	// RVA: 0x2a91764 VA: 0x75950a9764
	private Void _ProcessCapsuleReceive(RoguelikeItemBundle itemBundle) { }
	// RVA: 0x2a91918 VA: 0x75950a9918
	private Void _ProcessChestReceive(RoguelikeDungeonController controller, Int32 subIndex, RoguelikeItemBundle itemBundle) { }
	// RVA: 0x2a91b98 VA: 0x75950a9b98
	private Void _ProcessRecruitReceive(RoguelikeDungeonController controller) { }
	// RVA: 0x2a91a40 VA: 0x75950a9a40
	private Boolean _IsReceiveChest(RoguelikeItemBundle itemBundle) { }
	// RVA: 0x2a91ac4 VA: 0x75950a9ac4
	private Void _ProcessChestEvent(String topicId, Int32 subIndex) { }
	// RVA: 0x2a91e30 VA: 0x75950a9e30
	private Void _UseDiceToUnlockChest(String topicId) { }
	// RVA: 0x2a91dbc VA: 0x75950a9dbc
	private Void _LeaveChestDirectly() { }
	// RVA: 0x2a91ee4 VA: 0x75950a9ee4
	private Void _UseKeyToUnlockChest() { }
	// RVA: 0x2a91894 VA: 0x75950a9894
	private Boolean _IsReceiveCapsule(RoguelikeItemBundle itemBundle) { }
	// RVA: 0x2a91ccc VA: 0x75950a9ccc
	private Boolean _IsReceiveItem(RoguelikeItemBundle itemBundle, RoguelikeGameItemType gameItemType) { }
	// RVA: 0x2a91fec VA: 0x75950a9fec
	public Void .ctor() { }
	// RVA: 0x2a92098 VA: 0x75950aa098
	private Void <_ProcessRecruitReceive>b__17_0() { }
	// RVA: 0x2a92164 VA: 0x75950aa164
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```