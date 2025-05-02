# RoguelikeSacrificeState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _viewHolder`

- `RoguelikeSacrificeStateBean m_stateBean`

- `RoguelikeSacrificeView m_view`

- `RoguelikeSacrificePlugin m_plugin`

- `MenuAdapter m_menuAdapter`

- `Boolean m_inited`

- `String m_topicId`


## Methods

- `Void _InitIfNot()`

- `Void _InitView()`

- `Void _OnItemClicked(String)`

- `Void _OnConfirmBtnClicked()`

- `Void _OnConfirmSacrifice(String)`

- `Void <_OnConfirmSacrifice>b__15_0(RoguelikeSacrificeResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeSacrificeState : PopupFadeState
{
	private RectTransform _viewHolder; // 0x70
	private RoguelikeSacrificeStateBean m_stateBean; // 0x78
	private RoguelikeSacrificeView m_view; // 0x80
	private RoguelikeSacrificePlugin m_plugin; // 0x88
	private MenuAdapter m_menuAdapter; // 0x90
	private Boolean m_inited; // 0x98
	private String m_topicId; // 0xa0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__InitView; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0__OnItemClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnConfirmBtnClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnConfirmSacrifice; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2ac00a8 VA: 0x75950d80a8
	private Void _InitIfNot() { }
	// RVA: 0x2ac0538 VA: 0x75950d8538
	private Void _InitView() { }
	// RVA: 0x2ac0620 VA: 0x75950d8620
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ac0688 VA: 0x75950d8688
	protected override Void OnEnter() { }
	// RVA: 0x2ac0a0c VA: 0x75950d8a0c
	private Void _OnItemClicked(String indexId) { }
	// RVA: 0x2ac0bb0 VA: 0x75950d8bb0
	private Void _OnConfirmBtnClicked() { }
	// RVA: 0x2ac0ff8 VA: 0x75950d8ff8
	private Void _OnConfirmSacrifice(String selectedIndexId) { }
	// RVA: 0x2ac1240 VA: 0x75950d9240
	public Void .ctor() { }
	// RVA: 0x2ac1398 VA: 0x75950d9398
	private Void <_OnConfirmSacrifice>b__15_0(RoguelikeSacrificeResponse response) { }
	// RVA: 0x2ac13a8 VA: 0x75950d93a8
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```