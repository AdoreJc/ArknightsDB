# RL04NodeUpgradeSummaryView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL04`


## Fields

- `Image _imgTitle`

- `Text _textTypeName`

- `RL04NodeUpgradeMuralView _muralPrefab`

- `RectTransform _muralContainer`

- `Single _muralPermCompleteDuration`

- `ScrollRect _scrollRect`

- `SimpleLayoutContent _btnTypeList`

- `SimpleLayoutContent _permList`

- `SimpleLayoutContent _tempList`

- `UIAtlasImage _imgTempCaptionLine`

- `UIAtlasImage _imgTempInfoLine`

- `Text _textTempCaption1`

- `Text _textTempCaption2`

- `GameObject _lockTempIconGo`

- `GameObject _todoTempIconGo`

- `Text _textTempCost`

- `UIAnimationLocation _animEnter`

- `UIAnimationLocation _animSwitch`

- `INodeConfigFetcher m_configFetcher`

- `Boolean m_hasInited`

- `RL04NodeUpgradeMuralView m_muralView`

- `RL04NodeUpgradeModel m_currUpgradeModel`

- `RL04NodeUpgradeSummaryModel m_summaryModel`

- `BtnTypeListAdapter m_btnTypeListAdapter`

- `PermListAdapter m_permListAdapter`

- `TempListAdapter m_tempListAdapter`

- `Tween m_enterTween`

- `Tween m_switchTween`

- `Int32 m_cacheEnterSeq`

- `Int32 m_cacheSwitchSeq`


## Methods

- `Void set_onBtnTypeClick(Action`1)`

- `Void _RenderView(RL04NodeUpgradeConfig)`

- `Void _PlayEnterAnimIfNeed()`

- `Void _PlaySwitchAnimIfNeed()`

- `Void _InitIfNot()`

- `Void SetConfigFetcher(INodeConfigFetcher)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL04
public class RL04NodeUpgradeSummaryView : DataBinder`1
{
	private Image _imgTitle; // 0x20
	private Text _textTypeName; // 0x28
	private RL04NodeUpgradeMuralView _muralPrefab; // 0x30
	private RectTransform _muralContainer; // 0x38
	private Single _muralPermCompleteDuration; // 0x40
	private ScrollRect _scrollRect; // 0x48
	private SimpleLayoutContent _btnTypeList; // 0x50
	private SimpleLayoutContent _permList; // 0x58
	private SimpleLayoutContent _tempList; // 0x60
	private UIAtlasImage _imgTempCaptionLine; // 0x68
	private UIAtlasImage _imgTempInfoLine; // 0x70
	private Text _textTempCaption1; // 0x78
	private Text _textTempCaption2; // 0x80
	private GameObject _lockTempIconGo; // 0x88
	private GameObject _todoTempIconGo; // 0x90
	private Text _textTempCost; // 0x98
	private UIAnimationLocation _animEnter; // 0xa0
	private UIAnimationLocation _animSwitch; // 0xb0
	private INodeConfigFetcher m_configFetcher; // 0xc0
	private Boolean m_hasInited; // 0xc8
	private RL04NodeUpgradeMuralView m_muralView; // 0xd0
	private RL04NodeUpgradeModel m_currUpgradeModel; // 0xd8
	private RL04NodeUpgradeSummaryModel m_summaryModel; // 0xe0
	private BtnTypeListAdapter m_btnTypeListAdapter; // 0xe8
	private PermListAdapter m_permListAdapter; // 0xf0
	private TempListAdapter m_tempListAdapter; // 0xf8
	private Tween m_enterTween; // 0x100
	private Tween m_switchTween; // 0x108
	private Int32 m_cacheEnterSeq; // 0x110
	private Int32 m_cacheSwitchSeq; // 0x114
	private Dictionary`2 m_cacheMuralShowSeqNumDict; // 0x118
	private Action`1 <onBtnTypeClick>k__BackingField; // 0x120
	private static DelegateBridge __Hotfix0_get_onBtnTypeClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onBtnTypeClick; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__RenderView; // 0x18
	private static DelegateBridge __Hotfix0__GenerateShowAnimIdxList; // 0x20
	private static DelegateBridge __Hotfix0__PlayEnterAnimIfNeed; // 0x28
	private static DelegateBridge __Hotfix0__PlaySwitchAnimIfNeed; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0_SetConfigFetcher; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Action`1 onBtnTypeClick { get; set; }

	// RVA: 0x26e660c VA: 0x7594cfe60c
	private Action`1 get_onBtnTypeClick() { }
	// RVA: 0x26e4300 VA: 0x7594cfc300
	public Void set_onBtnTypeClick(Action`1 value) { }
	// RVA: 0x26e6674 VA: 0x7594cfe674
	public override Void OnValueChanged(RL04NodeUpgradeSummaryProp property) { }
	// RVA: 0x26e6a2c VA: 0x7594cfea2c
	private Void _RenderView(RL04NodeUpgradeConfig nodeConfig) { }
	// RVA: 0x26e7008 VA: 0x7594cff008
	private List`1 _GenerateShowAnimIdxList() { }
	// RVA: 0x26e6d94 VA: 0x7594cfed94
	private Void _PlayEnterAnimIfNeed() { }
	// RVA: 0x26e6ebc VA: 0x7594cfeebc
	private Void _PlaySwitchAnimIfNeed() { }
	// RVA: 0x26e6834 VA: 0x7594cfe834
	private Void _InitIfNot() { }
	// RVA: 0x26e427c VA: 0x7594cfc27c
	public Void SetConfigFetcher(INodeConfigFetcher configFetcher) { }
	// RVA: 0x26e740c VA: 0x7594cff40c
	public Void .ctor() { }
}
```