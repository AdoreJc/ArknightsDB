# RoguelikeTopicBattlePassEntryView

**Namespace:** `Torappu.Scripts.UI.RoguelikeTopic.Mode`


## Fields

- `Text _textBpLevel`

- `Text _textBpNotice`

- `GameObject _objBpNotice`

- `UIActTrackPoint _bpTrackPoint`

- `TrackPointViewProperty m_bpRewardProperty`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void EventOnBattlePass()`

- `Void <>xLuaBaseProxy_OnValueChanged(RoguelikeTopicModeViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Scripts.UI.RoguelikeTopic.Mode
public class RoguelikeTopicBattlePassEntryView : RoguelikeTopicSubView
{
	private Text _textBpLevel; // 0x28
	private Text _textBpNotice; // 0x30
	private GameObject _objBpNotice; // 0x38
	private UIActTrackPoint _bpTrackPoint; // 0x40
	private TrackPointViewProperty m_bpRewardProperty; // 0x48
	private Boolean m_isInited; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_EventOnBattlePass; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x376f594 VA: 0x7595d87594
	private Void _InitIfNot() { }
	// RVA: 0x376f67c VA: 0x7595d8767c
	public override Void OnValueChanged(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x376f8b0 VA: 0x7595d878b0
	public Void EventOnBattlePass() { }
	// RVA: 0x376f948 VA: 0x7595d87948
	public Void .ctor() { }
	// RVA: 0x376f9b8 VA: 0x7595d879b8
	private Void <>xLuaBaseProxy_OnValueChanged(RoguelikeTopicModeViewProperty P0) { }
}
```