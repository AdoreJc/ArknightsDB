# RoguelikeAlchemyState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _viewContainer`

- `Boolean m_hasInited`

- `RoguelikeDungeonPage m_page`

- `String m_topicId`

- `AbstractRoguelikeAlchemyController m_alchemyController`

- `IRoguelikeAlchemyViewModel m_alchemyViewModel`

- `MenuAdapter m_menuAdapter`

- `RoguelikeRewardStyle <rewardStyle>k__BackingField`


## Properties

- `RoguelikeRewardStyle rewardStyle`


## Methods

- `RoguelikeRewardStyle get_rewardStyle()`

- `Void set_rewardStyle(RoguelikeRewardStyle)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void ReloadDungeon()`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeAlchemyState : PopupFadeState, IValueMsgReceiver
{
	private RectTransform _viewContainer; // 0x70
	private Boolean m_hasInited; // 0x78
	private RoguelikeDungeonPage m_page; // 0x80
	private String m_topicId; // 0x88
	private AbstractRoguelikeAlchemyController m_alchemyController; // 0x90
	private IRoguelikeAlchemyViewModel m_alchemyViewModel; // 0x98
	private MenuAdapter m_menuAdapter; // 0xa0
	private RoguelikeRewardStyle <rewardStyle>k__BackingField; // 0xa8
	private static DelegateBridge __Hotfix0_get_rewardStyle; // 0x0
	private static DelegateBridge __Hotfix0_set_rewardStyle; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge __Hotfix0_OnMessage; // 0x28
	private static DelegateBridge __Hotfix0_ReloadDungeon; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public RoguelikeRewardStyle rewardStyle { get; set; }

	// RVA: 0x29e852c VA: 0x759500052c
	public RoguelikeRewardStyle get_rewardStyle() { }
	// RVA: 0x29e8594 VA: 0x7595000594
	private Void set_rewardStyle(RoguelikeRewardStyle value) { }
	// RVA: 0x29e8618 VA: 0x7595000618
	public override IStateBean GetCacheBean() { }
	// RVA: 0x29e867c VA: 0x759500067c
	protected override Void OnEnter() { }
	// RVA: 0x29e8b64 VA: 0x7595000b64
	protected override Void OnResume() { }
	// RVA: 0x29e8c30 VA: 0x7595000c30
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x29e8d28 VA: 0x7595000d28
	public Void ReloadDungeon() { }
	// RVA: 0x29e8964 VA: 0x7595000964
	private Void _InitIfNot() { }
	// RVA: 0x29e8e8c VA: 0x7595000e8c
	public Void .ctor() { }
	// RVA: 0x29e8efc VA: 0x7595000efc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x29e8f04 VA: 0x7595000f04
	private Void <>xLuaBaseProxy_OnResume() { }
}
```