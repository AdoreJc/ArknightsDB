# RoguelikeRewardItemListState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeRewardListView _listView`

- `RectTransform _panelTopMenu`

- `UIStyleProvider _styleProvider`

- `RoguelikeCommonTopMenu m_topMenu`

- `MenuAdapter m_menuAdapter`

- `RoguelikeRewardItemViewModel m_cacheViewModel`

- `RoguelikeRewardStyle m_style`

- `String m_topicId`

- `RoguelikeRewardStateBean m_stateBean`

- `String m_cachedTopicId`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Void OnClick(Int32)`

- `Void _HandleOnLeave()`

- `Void HandleOnLeave()`

- `Void _HandleOnReceive(RoguelikeRewardItemViewModel, String)`

- `Void <RegisterToDataListener>b__14_0(IStateBean)`

- `Void <RegisterToDataListener>b__14_1(IStateBean)`

- `Void <_HandleOnLeave>b__18_0(RoguelikeFinishNodeResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardItemListState : PopupFloatState
{
	private RoguelikeRewardListView _listView; // 0x70
	private RectTransform _panelTopMenu; // 0x78
	private UIStyleProvider _styleProvider; // 0x80
	private RoguelikeCommonTopMenu m_topMenu; // 0x88
	private MenuAdapter m_menuAdapter; // 0x90
	private RoguelikeRewardItemViewModel m_cacheViewModel; // 0x98
	private RoguelikeRewardStyle m_style; // 0xa0
	private String m_topicId; // 0xa8
	private RoguelikeRewardStateBean m_stateBean; // 0xb0
	private String m_cachedTopicId; // 0xb8
	private Boolean m_inited; // 0xc0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge __Hotfix0_OnClick; // 0x28
	private static DelegateBridge __Hotfix0__HandleOnLeave; // 0x30
	private static DelegateBridge __Hotfix0_HandleOnLeave; // 0x38
	private static DelegateBridge __Hotfix0__HandleOnReceive; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2a8f264 VA: 0x75950a7264
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2a8f2cc VA: 0x75950a72cc
	private Void _InitIfNot() { }
	// RVA: 0x2a8f638 VA: 0x75950a7638
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2a8f82c VA: 0x75950a782c
	protected override Void OnEnter() { }
	// RVA: 0x2a8fa14 VA: 0x75950a7a14
	protected override Void OnResume() { }
	// RVA: 0x2a8fb88 VA: 0x75950a7b88
	public Void OnClick(Int32 index) { }
	// RVA: 0x2a90314 VA: 0x75950a8314
	private Void _HandleOnLeave() { }
	// RVA: 0x2a8ff3c VA: 0x75950a7f3c
	public Void HandleOnLeave() { }
	// RVA: 0x2a900b8 VA: 0x75950a80b8
	private Void _HandleOnReceive(RoguelikeRewardItemViewModel item, String topicId) { }
	// RVA: 0x2a904ec VA: 0x75950a84ec
	public Void .ctor() { }
	// RVA: 0x2a905d4 VA: 0x75950a85d4
	private Void <RegisterToDataListener>b__14_0(IStateBean stateBean) { }
	// RVA: 0x2a90704 VA: 0x75950a8704
	private Void <RegisterToDataListener>b__14_1(IStateBean stateBean) { }
	// RVA: 0x2a90794 VA: 0x75950a8794
	private Void <_HandleOnLeave>b__18_0(RoguelikeFinishNodeResponse response) { }
	// RVA: 0x2a9095c VA: 0x75950a895c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2a90964 VA: 0x75950a8964
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2a9096c VA: 0x75950a896c
	private Void <>xLuaBaseProxy_OnResume() { }
}
```