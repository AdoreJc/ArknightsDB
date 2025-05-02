# Act1ArcadeSettlementStatusResultView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `UIAnimationLocation _entryAnim`

- `Text _textScore`

- `Text _textStageCode`

- `Text _textStageName`

- `Text _textPlayerName`

- `Text _textFinishTime`

- `Act1ArcadeSettlementCharCardView _charView`

- `Act1ArcadeSettlementIllustView _illustView`

- `Act1ArcadeSettlementMilestoneView _milestoneView`

- `Act1ArcadeToast _notifyToastPrefab`

- `Boolean m_blockClick`

- `Act1ArcadeSettlementModel m_model`


## Methods

- `IEnumerator _PlayEntryAnim()`

- `IEnumerator _ShowToast(Act1ArcadeSettlementModel)`

- `Void EventOnClickBg()`

- `Void <>xLuaBaseProxy_SetToDefaultShow()`

- `Void <>xLuaBaseProxy_ChangeInStatusAndRender(Act1ArcadeSettlementModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeSettlementStatusResultView : Act1ArcadeSettlementStatusBaseView
{
	private const Single TOAST_SHOW_DELAY; // 0x0
	private const Single TOAST_EACH_SHOW_DELAY; // 0x0
	private UIAnimationLocation _entryAnim; // 0x28
	private GameObject[] _rankIcons; // 0x38
	private Text _textScore; // 0x40
	private Text _textStageCode; // 0x48
	private Text _textStageName; // 0x50
	private Text _textPlayerName; // 0x58
	private Text _textFinishTime; // 0x60
	private Act1ArcadeSettlementCharCardView _charView; // 0x68
	private Act1ArcadeSettlementIllustView _illustView; // 0x70
	private Act1ArcadeSettlementMilestoneView _milestoneView; // 0x78
	private Act1ArcadeToast _notifyToastPrefab; // 0x80
	private Boolean m_blockClick; // 0x88
	private Act1ArcadeSettlementModel m_model; // 0x90
	private static DelegateBridge __Hotfix0_get_viewStatus; // 0x0
	private static DelegateBridge __Hotfix0_get_nextViewStatus; // 0x8
	private static DelegateBridge __Hotfix0_SetToDefaultShow; // 0x10
	private static DelegateBridge __Hotfix0_ChangeInStatusAndRender; // 0x18
	private static DelegateBridge __Hotfix0__PlayEntryAnim; // 0x20
	private static DelegateBridge __Hotfix0__ShowToast; // 0x28
	private static DelegateBridge __Hotfix0_EventOnClickBg; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override SettlementViewStatus viewStatus { get; }
	public override SettlementViewStatus nextViewStatus { get; }

	// RVA: 0x340a46c VA: 0x7595a2246c
	public override SettlementViewStatus get_viewStatus() { }
	// RVA: 0x340a4d4 VA: 0x7595a224d4
	public override SettlementViewStatus get_nextViewStatus() { }
	// RVA: 0x340a53c VA: 0x7595a2253c
	public override Void SetToDefaultShow() { }
	// RVA: 0x340a5f4 VA: 0x7595a225f4
	public override Void ChangeInStatusAndRender(Act1ArcadeSettlementModel model) { }
	// RVA: 0x340a8d0 VA: 0x7595a228d0
	private IEnumerator _PlayEntryAnim() { }
	// RVA: 0x340a97c VA: 0x7595a2297c
	private IEnumerator _ShowToast(Act1ArcadeSettlementModel model) { }
	// RVA: 0x340aa9c VA: 0x7595a22a9c
	public Void EventOnClickBg() { }
	// RVA: 0x340ab48 VA: 0x7595a22b48
	public Void .ctor() { }
	// RVA: 0x340abb4 VA: 0x7595a22bb4
	private Void <>xLuaBaseProxy_SetToDefaultShow() { }
	// RVA: 0x340abb8 VA: 0x7595a22bb8
	private Void <>xLuaBaseProxy_ChangeInStatusAndRender(Act1ArcadeSettlementModel P0) { }
}
```