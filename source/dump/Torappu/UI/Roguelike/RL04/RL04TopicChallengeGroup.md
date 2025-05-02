# RL04TopicChallengeGroup

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `UIAtlasObject _atlas`

- `UIAtlasImage _imgGroupName`

- `Boolean m_hasInited`

- `Int32 m_cachedGroupId`


## Methods

- `Void OnGroupSwitchClick()`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_set_eventOnGroupSwitch(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04TopicChallengeGroup : RoguelikeTopicChallengeGroup
{
	private UIAtlasObject _atlas; // 0x20
	private UIAtlasImage _imgGroupName; // 0x28
	private Action`1 <eventOnGroupSwitch>k__BackingField; // 0x30
	private Boolean m_hasInited; // 0x38
	private Int32 m_cachedGroupId; // 0x3c
	private readonly Single PER_PAGE_SWITCH_DUR; // 0x40
	private readonly String GROUP_NAME_PREFIX; // 0x48
	private static DelegateBridge __Hotfix0_get_eventOnGroupSwitch; // 0x0
	private static DelegateBridge __Hotfix0_set_eventOnGroupSwitch; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnGroupSwitchClick; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Action`1 eventOnGroupSwitch { get; set; }

	// RVA: 0x2b0da38 VA: 0x7595125a38
	public override Action`1 get_eventOnGroupSwitch() { }
	// RVA: 0x2b0daa0 VA: 0x7595125aa0
	public override Void set_eventOnGroupSwitch(Action`1 value) { }
	// RVA: 0x2b0db24 VA: 0x7595125b24
	public override Void Render(RoguelikeTopicChallengeModeViewModel challengeModeViewModel, RoguelikeTopicChallengePluginContext pluginContext) { }
	// RVA: 0x2b0dd14 VA: 0x7595125d14
	public Void OnGroupSwitchClick() { }
	// RVA: 0x2b0dc98 VA: 0x7595125c98
	private Void _InitIfNot() { }
	// RVA: 0x2b0ddc4 VA: 0x7595125dc4
	public Void .ctor() { }
	// RVA: 0x2b0de70 VA: 0x7595125e70
	private Action`1 <>xLuaBaseProxy_get_eventOnGroupSwitch() { }
	// RVA: 0x2b0de78 VA: 0x7595125e78
	private Void <>xLuaBaseProxy_set_eventOnGroupSwitch(Action`1 P0) { }
}
```