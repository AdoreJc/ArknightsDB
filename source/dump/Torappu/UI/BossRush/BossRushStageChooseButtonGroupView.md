# BossRushStageChooseButtonGroupView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `BossRushStageChooseButtonView _buttonPrefab`

- `Boolean m_hasInited`

- `TweenWrapper m_tweenWrapper`


## Methods

- `Void set_onStageGroupBtnClick(Action`1)`

- `Void _InitIfNot()`

- `Void _PlayEnterAnim(BossRushStageChooseViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageChooseButtonGroupView : DataBinder`1, IHotfixable
{
	private const Single BUTTON_CARD_DELAY; // 0x0
	private const String BUTTON_ANIM_KEY; // 0x0
	private RectTransform[] _buttonContainers; // 0x20
	private BossRushStageChooseButtonView _buttonPrefab; // 0x28
	private List`1 m_buttonViews; // 0x30
	private Boolean m_hasInited; // 0x38
	private TweenWrapper m_tweenWrapper; // 0x40
	private Action`1 <onStageGroupBtnClick>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_onStageGroupBtnClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onStageGroupBtnClick; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onStageGroupBtnClick { get; set; }

	// RVA: 0x2e6e830 VA: 0x7595486830
	private Action`1 get_onStageGroupBtnClick() { }
	// RVA: 0x2e6e898 VA: 0x7595486898
	public Void set_onStageGroupBtnClick(Action`1 value) { }
	// RVA: 0x2e6e91c VA: 0x759548691c
	public override Void OnValueChanged(BossRushStageChooseProperty property) { }
	// RVA: 0x2e6eadc VA: 0x7595486adc
	private Void _InitIfNot() { }
	// RVA: 0x2e6ef70 VA: 0x7595486f70
	private Void _PlayEnterAnim(BossRushStageChooseViewModel model) { }
	// RVA: 0x2e6f2e8 VA: 0x75954872e8
	public Void .ctor() { }
}
```