# RoguelikeTopicModeTab

**Namespace:** `Torappu.UI.RoguelikeTopic.Mode`


## Fields

- `RoguelikeTopicModeViewType _viewType`

- `UIAnimationLocation _switchAnim`

- `Boolean m_visible`

- `Boolean m_firstSetVisible`


## Methods

- `Void SetVisible(Boolean)`

- `Void _SetActive()`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnValueChanged(RoguelikeTopicModeViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Mode
public class RoguelikeTopicModeTab : RoguelikeTopicModeViewBase
{
	private RoguelikeTopicModeViewType _viewType; // 0x38
	private UIAnimationLocation _switchAnim; // 0x40
	private Boolean m_visible; // 0x50
	private Boolean m_firstSetVisible; // 0x51
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_SetVisible; // 0x10
	private static DelegateBridge __Hotfix0__SetActive; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x26d4ad0 VA: 0x7594cecad0
	protected override Void OnInit() { }
	// RVA: 0x26d4b50 VA: 0x7594cecb50
	public override Void OnValueChanged(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x26d4cec VA: 0x7594ceccec
	public Void SetVisible(Boolean v) { }
	// RVA: 0x26d4f4c VA: 0x7594cecf4c
	private Void _SetActive() { }
	// RVA: 0x26d4fc4 VA: 0x7594cecfc4
	public Void .ctor() { }
	// RVA: 0x26d50c0 VA: 0x7594ced0c0
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x26d5128 VA: 0x7594ced128
	private Void <>xLuaBaseProxy_OnValueChanged(RoguelikeTopicModeViewProperty P0) { }
}
```