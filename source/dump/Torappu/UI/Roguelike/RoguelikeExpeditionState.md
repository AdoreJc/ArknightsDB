# RoguelikeExpeditionState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _viewHolder`

- `RoguelikeExpeditionStateBean m_stateBean`

- `RoguelikeExpeditionView m_view`

- `RoguelikeExpeditionPluginContext m_pluginContext`

- `Boolean m_inited`

- `MenuAdapter m_menuAdapter`

- `String m_topicId`


## Methods

- `Void _InitIfNot()`

- `Void _InitView()`

- `Void _OnCharSelectChange(String)`

- `Void _OnConfirmBtnClicked()`

- `Void _OnConfirmExpedition(String)`

- `Void <_OnConfirmExpedition>b__15_0(RoguelikeExpeditionResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeExpeditionState : PopupFadeState
{
	private RectTransform _viewHolder; // 0x70
	private RoguelikeExpeditionStateBean m_stateBean; // 0x78
	private RoguelikeExpeditionView m_view; // 0x80
	private RoguelikeExpeditionPluginContext m_pluginContext; // 0x88
	private Boolean m_inited; // 0x90
	private MenuAdapter m_menuAdapter; // 0x98
	private String m_topicId; // 0xa0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__InitView; // 0x18
	private static DelegateBridge __Hotfix0__OnCharSelectChange; // 0x20
	private static DelegateBridge __Hotfix0__OnConfirmBtnClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnConfirmExpedition; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2a33710 VA: 0x759504b710
	protected override Void OnEnter() { }
	// RVA: 0x2a33e9c VA: 0x759504be9c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2a33910 VA: 0x759504b910
	private Void _InitIfNot() { }
	// RVA: 0x2a33e2c VA: 0x759504be2c
	private Void _InitView() { }
	// RVA: 0x2a34198 VA: 0x759504c198
	private Void _OnCharSelectChange(String charInstId) { }
	// RVA: 0x2a3431c VA: 0x759504c31c
	private Void _OnConfirmBtnClicked() { }
	// RVA: 0x2a346b4 VA: 0x759504c6b4
	private Void _OnConfirmExpedition(String selectedCharInstId) { }
	// RVA: 0x2a348fc VA: 0x759504c8fc
	public Void .ctor() { }
	// RVA: 0x2a34a54 VA: 0x759504ca54
	private Void <_OnConfirmExpedition>b__15_0(RoguelikeExpeditionResponse response) { }
	// RVA: 0x2a34a64 VA: 0x759504ca64
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```