# ActMultiV3BattleFinishReportPanel

**Namespace:** `Torappu.Activity.ActMultiV3.BattleFinish`


## Fields

- `UIBlurFloatPanel _blurFloatPanel`

- `SimpleLayoutContent _reportItemList`

- `Text _textTitle`

- `Image _imgAvatar`

- `Text _textTargetLv`

- `Text _textTargetName`

- `RectTransform _cancelBtnRect`

- `Boolean m_isInited`

- `ActMultiV3BattleFinishReportModel m_reportModel`

- `ReportItemAdapter m_itemListAdapter`

- `Action <onBtnCancelClick>k__BackingField`

- `Action <onBtnConfirmClick>k__BackingField`


## Properties

- `Action onBtnCancelClick`

- `Action onBtnConfirmClick`


## Methods

- `Action get_onBtnCancelClick()`

- `Void set_onBtnCancelClick(Action)`

- `Action get_onBtnConfirmClick()`

- `Void set_onBtnConfirmClick(Action)`

- `Void set_onReportItemClick(Action`1)`

- `Void Render(ActMultiV3BattleFinishReportModel)`

- `Void _InitIfNot()`

- `Void EventOnCancel()`

- `Void EventOnConfirm()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.BattleFinish
public class ActMultiV3BattleFinishReportPanel : MonoBehaviour, IHotfixable
{
	private UIBlurFloatPanel _blurFloatPanel; // 0x18
	private SimpleLayoutContent _reportItemList; // 0x20
	private Text _textTitle; // 0x28
	private Image _imgAvatar; // 0x30
	private Text _textTargetLv; // 0x38
	private Text _textTargetName; // 0x40
	private RectTransform _cancelBtnRect; // 0x48
	private Boolean m_isInited; // 0x50
	private ActMultiV3BattleFinishReportModel m_reportModel; // 0x58
	private ReportItemAdapter m_itemListAdapter; // 0x60
	private Action <onBtnCancelClick>k__BackingField; // 0x68
	private Action <onBtnConfirmClick>k__BackingField; // 0x70
	private Action`1 <onReportItemClick>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_onBtnCancelClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onBtnCancelClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onBtnConfirmClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onBtnConfirmClick; // 0x18
	private static DelegateBridge __Hotfix0_get_onReportItemClick; // 0x20
	private static DelegateBridge __Hotfix0_set_onReportItemClick; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0_EventOnCancel; // 0x40
	private static DelegateBridge __Hotfix0_EventOnConfirm; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Action onBtnCancelClick { get; set; }
	private Action onBtnConfirmClick { get; set; }
	private Action`1 onReportItemClick { get; set; }

	// RVA: 0x3183388 VA: 0x759579b388
	private Action get_onBtnCancelClick() { }
	// RVA: 0x31833f0 VA: 0x759579b3f0
	public Void set_onBtnCancelClick(Action value) { }
	// RVA: 0x3183474 VA: 0x759579b474
	private Action get_onBtnConfirmClick() { }
	// RVA: 0x31834dc VA: 0x759579b4dc
	public Void set_onBtnConfirmClick(Action value) { }
	// RVA: 0x3183560 VA: 0x759579b560
	private Action`1 get_onReportItemClick() { }
	// RVA: 0x31835c8 VA: 0x759579b5c8
	public Void set_onReportItemClick(Action`1 value) { }
	// RVA: 0x318364c VA: 0x759579b64c
	public Void Render(ActMultiV3BattleFinishReportModel reportModel) { }
	// RVA: 0x3183800 VA: 0x759579b800
	private Void _InitIfNot() { }
	// RVA: 0x31839f0 VA: 0x759579b9f0
	public Void EventOnCancel() { }
	// RVA: 0x3183a8c VA: 0x759579ba8c
	public Void EventOnConfirm() { }
	// RVA: 0x3183b28 VA: 0x759579bb28
	public Void .ctor() { }
}
```