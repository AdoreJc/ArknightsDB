# Act1LockSquadAssistState

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `UIBlurFloatPanel _blurPanel`

- `RectTransform _topMenuContainer`

- `Act1LockAssistView _assistView`

- `Boolean m_isInited`

- `Act1LockSquadAssistStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Void _OnSkillClick(Int32)`

- `Void _OnConfirmBtnClick()`

- `Void <_InitIfNot>b__7_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockSquadAssistState : PopupFadeState
{
	private UIBlurFloatPanel _blurPanel; // 0x70
	private RectTransform _topMenuContainer; // 0x78
	private Act1LockAssistView _assistView; // 0x80
	private Boolean m_isInited; // 0x88
	private Act1LockSquadAssistStateBean m_stateBean; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__OnSkillClick; // 0x18
	private static DelegateBridge __Hotfix0__OnConfirmBtnClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x33a25bc VA: 0x75959ba5bc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x33a2624 VA: 0x75959ba624
	protected override Void OnEnter() { }
	// RVA: 0x33a26ac VA: 0x75959ba6ac
	private Void _InitIfNot() { }
	// RVA: 0x33a2908 VA: 0x75959ba908
	private Void _OnSkillClick(Int32 index) { }
	// RVA: 0x33a2994 VA: 0x75959ba994
	private Void _OnConfirmBtnClick() { }
	// RVA: 0x33a2a3c VA: 0x75959baa3c
	public Void .ctor() { }
	// RVA: 0x33a2aec VA: 0x75959baaec
	private Void <_InitIfNot>b__7_0() { }
	// RVA: 0x33a2afc VA: 0x75959baafc
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```