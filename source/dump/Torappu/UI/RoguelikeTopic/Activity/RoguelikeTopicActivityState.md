# RoguelikeTopicActivityState

**Namespace:** `Torappu.UI.RoguelikeTopic.Activity`


## Fields

- `RectTransform _actPanelContent`

- `RoguelikeTopicActivityStateBean m_stateBean`

- `RoguelikeTopicActivityPanel m_actPanel`

- `Int32 m_dialogInst`


## Methods

- `Void _OnClickRemoveState()`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Activity
public class RoguelikeTopicActivityState : PopupFloatState, ICompDialogCallBack
{
	private RectTransform _actPanelContent; // 0x70
	private RoguelikeTopicActivityStateBean m_stateBean; // 0x78
	private RoguelikeTopicActivityPanel m_actPanel; // 0x80
	private Int32 m_dialogInst; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__OnClickRemoveState; // 0x18
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x26dd4e0 VA: 0x7594cf54e0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x26dd548 VA: 0x7594cf5548
	protected override Void OnEnter() { }
	// RVA: 0x26dd8e4 VA: 0x7594cf58e4
	protected override Void OnResume() { }
	// RVA: 0x26dd9a8 VA: 0x7594cf59a8
	private Void _OnClickRemoveState() { }
	// RVA: 0x26ddb04 VA: 0x7594cf5b04
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x26ddba8 VA: 0x7594cf5ba8
	public Void .ctor() { }
	// RVA: 0x26ddcc4 VA: 0x7594cf5cc4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x26ddccc VA: 0x7594cf5ccc
	private Void <>xLuaBaseProxy_OnResume() { }
}
```