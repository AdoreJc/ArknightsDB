# RoguelikeTopicBattlePassView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RoguelikeTopicBattlePassAdapter _bpItemAdapter`

- `RoguelikeTopicBattlePassTopView _topView`

- `RoguelikeTopicBPGreatRewardView _middleView`

- `LoopHorizontalScrollRect _buttonScrollRect`

- `GridLayoutGroup _bpGridLayout`

- `GameObject _panelGetAllBtn`

- `UIAtlasImage _imgGotAllBtn`

- `Text _gotAllBtnText`

- `UIAtlasImage _imgBkg`

- `UIAtlasImage _imgDetailBtn`

- `UIAtlasImage _imgPurchaseBtn`

- `Boolean m_isInited`

- `RoguelikeTopicBattlePassViewModel m_cachedViewModel`

- `Tweener m_focusTween`

- `RoguelikeTopicBattlePassState <bindState>k__BackingField`


## Properties

- `RoguelikeTopicBattlePassState bindState`


## Methods

- `Void set_getRewardAction(Action`1)`

- `RoguelikeTopicBattlePassState get_bindState()`

- `Void set_bindState(RoguelikeTopicBattlePassState)`

- `Void Init(RoguelikeTopicBattlePassState)`

- `Void _InitIfNot()`

- `Void _OnGrandPrizeClick(Int32)`

- `Void _OnRewardItemClick(String)`

- `Void OnGotAllBtnClick()`

- `Void OnGuideBtnClick()`

- `Void OnBpPurchaseClick()`

- `Void FocusCurrentLv()`

- `Void _FocusOnIdx(Int32)`

- `Single <_FocusOnIdx>b__33_0()`

- `Void <_FocusOnIdx>b__33_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBattlePassView : DataBinder`1
{
	private RoguelikeTopicBattlePassAdapter _bpItemAdapter; // 0x20
	private RoguelikeTopicBattlePassTopView _topView; // 0x28
	private RoguelikeTopicBPGreatRewardView _middleView; // 0x30
	private LoopHorizontalScrollRect _buttonScrollRect; // 0x38
	private GridLayoutGroup _bpGridLayout; // 0x40
	private GameObject _panelGetAllBtn; // 0x48
	private UIAtlasImage _imgGotAllBtn; // 0x50
	private Text _gotAllBtnText; // 0x58
	private UIAtlasImage _imgBkg; // 0x60
	private UIAtlasImage _imgDetailBtn; // 0x68
	private UIAtlasImage _imgPurchaseBtn; // 0x70
	private Action`1 <getRewardAction>k__BackingField; // 0x78
	private const Int32 SLIDE_MAX_LENGTH; // 0x0
	private Boolean m_isInited; // 0x80
	private List`1 m_cachedObtainableList; // 0x88
	private RoguelikeTopicBattlePassViewModel m_cachedViewModel; // 0x90
	private Tweener m_focusTween; // 0x98
	private RoguelikeTopicBattlePassState <bindState>k__BackingField; // 0xa0
	private static DelegateBridge __Hotfix0_get_getRewardAction; // 0x0
	private static DelegateBridge __Hotfix0_set_getRewardAction; // 0x8
	private static DelegateBridge __Hotfix0_get_bindState; // 0x10
	private static DelegateBridge __Hotfix0_set_bindState; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__OnGrandPrizeClick; // 0x38
	private static DelegateBridge __Hotfix0__OnRewardItemClick; // 0x40
	private static DelegateBridge __Hotfix0_OnGotAllBtnClick; // 0x48
	private static DelegateBridge __Hotfix0_OnGuideBtnClick; // 0x50
	private static DelegateBridge __Hotfix0_OnBpPurchaseClick; // 0x58
	private static DelegateBridge __Hotfix0_FocusCurrentLv; // 0x60
	private static DelegateBridge __Hotfix0__FocusOnIdx; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	private Action`1 getRewardAction { get; set; }
	private RoguelikeTopicBattlePassState bindState { get; set; }

	// RVA: 0x26421e0 VA: 0x7594c5a1e0
	private Action`1 get_getRewardAction() { }
	// RVA: 0x263ff04 VA: 0x7594c57f04
	public Void set_getRewardAction(Action`1 value) { }
	// RVA: 0x2642248 VA: 0x7594c5a248
	private RoguelikeTopicBattlePassState get_bindState() { }
	// RVA: 0x26422b0 VA: 0x7594c5a2b0
	private Void set_bindState(RoguelikeTopicBattlePassState value) { }
	// RVA: 0x263fe84 VA: 0x7594c57e84
	public Void Init(RoguelikeTopicBattlePassState state) { }
	// RVA: 0x2642334 VA: 0x7594c5a334
	public override Void OnValueChanged(RoguelikeTopicBattlePassProperty property) { }
	// RVA: 0x2642680 VA: 0x7594c5a680
	private Void _InitIfNot() { }
	// RVA: 0x2642760 VA: 0x7594c5a760
	private Void _OnGrandPrizeClick(Int32 level) { }
	// RVA: 0x2642bf0 VA: 0x7594c5abf0
	private Void _OnRewardItemClick(String bpId) { }
	// RVA: 0x2642d64 VA: 0x7594c5ad64
	public Void OnGotAllBtnClick() { }
	// RVA: 0x2642e2c VA: 0x7594c5ae2c
	public Void OnGuideBtnClick() { }
	// RVA: 0x2642ef4 VA: 0x7594c5aef4
	public Void OnBpPurchaseClick() { }
	// RVA: 0x2641880 VA: 0x7594c59880
	public Void FocusCurrentLv() { }
	// RVA: 0x2642808 VA: 0x7594c5a808
	private Void _FocusOnIdx(Int32 focusIdx) { }
	// RVA: 0x2642fd0 VA: 0x7594c5afd0
	public Void .ctor() { }
	// RVA: 0x2643060 VA: 0x7594c5b060
	private Single <_FocusOnIdx>b__33_0() { }
	// RVA: 0x264307c VA: 0x7594c5b07c
	private Void <_FocusOnIdx>b__33_1(Single val) { }
}
```