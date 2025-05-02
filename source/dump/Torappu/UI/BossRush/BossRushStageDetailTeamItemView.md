# BossRushStageDetailTeamItemView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `UIAnimationLocation _animationLocation`

- `SimpleLayoutContent _charCardContent`

- `TwoStateToggle _toggleSelect`

- `TwoStateToggle _toggleUnselect`

- `Image _imgTeamIconUnselect`

- `Image _imgTeamIconSelect`

- `Text _textFreeNumUnselect`

- `Text _textFreeNumSelect`

- `Text _textFreeNumSelect2`

- `Text _textTeamName`

- `LayoutElement _layoutElement`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `AnimationSwitchTween m_switchTween`

- `BossRushTeamModel m_cachedModel`


## Properties

- `Single itemWidth`


## Methods

- `Void set_afterItemExpand(Action`1)`

- `Void set_onTeamClick(Action`1)`

- `Single get_itemWidth()`

- `Void Render(Int32, String, String, BossRushTeamModel, Boolean)`

- `Void OnTeamCardClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageDetailTeamItemView : MonoBehaviour, IHotfixable
{
	public const Single TWEEN_DURATION; // 0x0
	private const String TEXT_FORMAT_FREE_OPERATOR; // 0x0
	private UIAnimationLocation _animationLocation; // 0x18
	private SimpleLayoutContent _charCardContent; // 0x28
	private TwoStateToggle _toggleSelect; // 0x30
	private TwoStateToggle _toggleUnselect; // 0x38
	private Image _imgTeamIconUnselect; // 0x40
	private Image _imgTeamIconSelect; // 0x48
	private Text _textFreeNumUnselect; // 0x50
	private Text _textFreeNumSelect; // 0x58
	private Text _textFreeNumSelect2; // 0x60
	private Text _textTeamName; // 0x68
	private UIAtlasImage[] _charPortrait; // 0x70
	private LayoutElement _layoutElement; // 0x78
	private Boolean m_hasInited; // 0x80
	private Adapter m_adapter; // 0x88
	private AnimationSwitchTween m_switchTween; // 0x90
	private BossRushTeamModel m_cachedModel; // 0x98
	private Action`1 <afterItemExpand>k__BackingField; // 0xa0
	private Action`1 <onTeamClick>k__BackingField; // 0xa8
	private static DelegateBridge __Hotfix0_get_afterItemExpand; // 0x0
	private static DelegateBridge __Hotfix0_set_afterItemExpand; // 0x8
	private static DelegateBridge __Hotfix0_get_onTeamClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onTeamClick; // 0x18
	private static DelegateBridge __Hotfix0_get_itemWidth; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0_OnTeamCardClick; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Action`1 afterItemExpand { get; set; }
	private Action`1 onTeamClick { get; set; }
	public Single itemWidth { get; }

	// RVA: 0x2e7c614 VA: 0x7595494614
	private Action`1 get_afterItemExpand() { }
	// RVA: 0x2e7be28 VA: 0x7595493e28
	public Void set_afterItemExpand(Action`1 value) { }
	// RVA: 0x2e7c67c VA: 0x759549467c
	private Action`1 get_onTeamClick() { }
	// RVA: 0x2e7beac VA: 0x7595493eac
	public Void set_onTeamClick(Action`1 value) { }
	// RVA: 0x2e7c578 VA: 0x7595494578
	public Single get_itemWidth() { }
	// RVA: 0x2e7bf30 VA: 0x7595493f30
	public Void Render(Int32 position, String selectTeamId, String actId, BossRushTeamModel teamModel, Boolean needRefresh) { }
	// RVA: 0x2e7c840 VA: 0x7595494840
	public Void OnTeamCardClick() { }
	// RVA: 0x2e7c6e4 VA: 0x75954946e4
	private Void _InitIfNot() { }
	// RVA: 0x2e7c984 VA: 0x7595494984
	public Void .ctor() { }
}
```