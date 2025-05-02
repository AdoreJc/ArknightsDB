# BuildingMessageLeaveBoardBottomInfoView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `Text _visitorNumThisWeek`

- `Text _visitorNumToday`

- `Text _rightText`

- `GameObject _panelLeft`

- `Single m_timer`

- `DateTime m_countDownTime`

- `Boolean m_isInited`

- `Boolean m_needCountDown`

- `TimerData m_timeData`


## Methods

- `Void Update()`

- `Void _InitIfNot()`

- `Void _RendPlayerInfoView(BuildingPayloadGetMessageBoardContentResponse)`

- `Void _RendVisitorInfoView(BuildingPayloadGetOthersMessageBoardContentResponse)`

- `Void _RefreshTimeCountDown()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingMessageLeaveBoardBottomInfoView : DataBinder`1, IHotfixable
{
	private Text _visitorNumThisWeek; // 0x20
	private Text _visitorNumToday; // 0x28
	private Text _rightText; // 0x30
	private GameObject _panelLeft; // 0x38
	private Single m_timer; // 0x40
	private DateTime m_countDownTime; // 0x48
	private Boolean m_isInited; // 0x50
	private Boolean m_needCountDown; // 0x51
	private TimerData m_timeData; // 0x58
	private static DelegateBridge __Hotfix0_Update; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__RendPlayerInfoView; // 0x18
	private static DelegateBridge __Hotfix0__RendVisitorInfoView; // 0x20
	private static DelegateBridge __Hotfix0__RefreshTimeCountDown; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3dc71e4 VA: 0x75963df1e4
	private Void Update() { }
	// RVA: 0x3dc7718 VA: 0x75963df718
	private Void _InitIfNot() { }
	// RVA: 0x3dc77e4 VA: 0x75963df7e4
	public override Void OnValueChanged(BuildingMessageLeaveBoardProperty property) { }
	// RVA: 0x3dc78d4 VA: 0x75963df8d4
	private Void _RendPlayerInfoView(BuildingPayloadGetMessageBoardContentResponse response) { }
	// RVA: 0x3dc7a34 VA: 0x75963dfa34
	private Void _RendVisitorInfoView(BuildingPayloadGetOthersMessageBoardContentResponse response) { }
	// RVA: 0x3dc729c VA: 0x75963df29c
	private Void _RefreshTimeCountDown() { }
	// RVA: 0x3dc7b30 VA: 0x75963dfb30
	public Void .ctor() { }
}
```