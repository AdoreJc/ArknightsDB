# Act1ArcadeSettlementStatusEntryView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `UIAnimationLocation _entryAnim`

- `GameObject _panelNewRecordTip`

- `GameObject _panelNewRecordBlock`

- `GameObject _panelCommonBlock`

- `Act1ArcadeSettlementScoreComp _scoreComp`

- `Boolean m_blockClick`

- `Act1ArcadeSettlementModel m_model`


## Methods

- `IEnumerator _PlayEntryAnim(Boolean)`

- `IEnumerator _PlayNewRecordAudio(Single)`

- `Void _InitAnim()`

- `Void EventOnClickBg()`

- `Void <>xLuaBaseProxy_SetToDefaultShow()`

- `Void <>xLuaBaseProxy_ChangeInStatusAndRender(Act1ArcadeSettlementModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeSettlementStatusEntryView : Act1ArcadeSettlementStatusBaseView
{
	private const Single SCORE_TWEEN_DELAY; // 0x0
	private const Single SCORE_TWEEN_DURATION; // 0x0
	private const Single NEW_RECORD_AUDIO_DELAY; // 0x0
	private UIAnimationLocation _entryAnim; // 0x28
	private GameObject _panelNewRecordTip; // 0x38
	private GameObject _panelNewRecordBlock; // 0x40
	private GameObject _panelCommonBlock; // 0x48
	private Act1ArcadeSettlementScoreComp _scoreComp; // 0x50
	private GameObject[] _rankIcons; // 0x58
	private Boolean m_blockClick; // 0x60
	private Act1ArcadeSettlementModel m_model; // 0x68
	private static DelegateBridge __Hotfix0_get_viewStatus; // 0x0
	private static DelegateBridge __Hotfix0_get_nextViewStatus; // 0x8
	private static DelegateBridge __Hotfix0_SetToDefaultShow; // 0x10
	private static DelegateBridge __Hotfix0_ChangeInStatusAndRender; // 0x18
	private static DelegateBridge __Hotfix0__PlayEntryAnim; // 0x20
	private static DelegateBridge __Hotfix0__PlayNewRecordAudio; // 0x28
	private static DelegateBridge __Hotfix0__InitAnim; // 0x30
	private static DelegateBridge __Hotfix0_EventOnClickBg; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override SettlementViewStatus viewStatus { get; }
	public override SettlementViewStatus nextViewStatus { get; }

	// RVA: 0x340993c VA: 0x7595a2193c
	public override SettlementViewStatus get_viewStatus() { }
	// RVA: 0x34099a4 VA: 0x7595a219a4
	public override SettlementViewStatus get_nextViewStatus() { }
	// RVA: 0x3409ad0 VA: 0x7595a21ad0
	public override Void SetToDefaultShow() { }
	// RVA: 0x3409be4 VA: 0x7595a21be4
	public override Void ChangeInStatusAndRender(Act1ArcadeSettlementModel model) { }
	// RVA: 0x3409e24 VA: 0x7595a21e24
	private IEnumerator _PlayEntryAnim(Boolean autoClick) { }
	// RVA: 0x3409eec VA: 0x7595a21eec
	private IEnumerator _PlayNewRecordAudio(Single delay) { }
	// RVA: 0x3409b58 VA: 0x7595a21b58
	private Void _InitAnim() { }
	// RVA: 0x3409ff0 VA: 0x7595a21ff0
	public Void EventOnClickBg() { }
	// RVA: 0x340a09c VA: 0x7595a2209c
	public Void .ctor() { }
	// RVA: 0x340a108 VA: 0x7595a22108
	private Void <>xLuaBaseProxy_SetToDefaultShow() { }
	// RVA: 0x340a10c VA: 0x7595a2210c
	private Void <>xLuaBaseProxy_ChangeInStatusAndRender(Act1ArcadeSettlementModel P0) { }
}
```