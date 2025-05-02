# RoguelikeTopicOuterBuffState

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RectTransform _outerBuffViewHolder`

- `String m_topicId`

- `RoguelikeTopicOuterBuffController m_outerBuffController`


## Methods

- `Void _DestroyOuterBuffView()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicOuterBuffState : PopupFadeState
{
	private RectTransform _outerBuffViewHolder; // 0x70
	private String m_topicId; // 0x78
	private RoguelikeTopicOuterBuffController m_outerBuffController; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnExit; // 0x18
	private static DelegateBridge __Hotfix0__DestroyOuterBuffView; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x266a278 VA: 0x7594c82278
	public override IStateBean GetCacheBean() { }
	// RVA: 0x266a2dc VA: 0x7594c822dc
	protected override Void OnEnter() { }
	// RVA: 0x266a780 VA: 0x7594c82780
	protected override Void OnResume() { }
	// RVA: 0x266a860 VA: 0x7594c82860
	protected override Void OnExit() { }
	// RVA: 0x266a6ac VA: 0x7594c826ac
	private Void _DestroyOuterBuffView() { }
	// RVA: 0x266a92c VA: 0x7594c8292c
	public Void .ctor() { }
	// RVA: 0x266a99c VA: 0x7594c8299c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x266a9a4 VA: 0x7594c829a4
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x266a9ac VA: 0x7594c829ac
	private Void <>xLuaBaseProxy_OnExit() { }
}
```