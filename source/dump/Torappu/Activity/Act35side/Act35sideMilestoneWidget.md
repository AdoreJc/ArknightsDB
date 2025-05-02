# Act35sideMilestoneWidget

**Namespace:** `Torappu.Activity.Act35side`


## Fields

- `Text _textProgress`

- `Text _textLevel`

- `GameObject _objMax`

- `GameObject _objExp`

- `Slider _sliderProgress`

- `Act35sideMilestoneDisplayRewardItemView _prefabGrandReward`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act35side
public class Act35sideMilestoneWidget : TemplateActivityMilestoneWidget, IHotfixable
{
	private Text _textProgress; // 0x18
	private Text _textLevel; // 0x20
	private GameObject _objMax; // 0x28
	private GameObject _objExp; // 0x30
	private Slider _sliderProgress; // 0x38
	private RectTransform[] _grandRewardContainer; // 0x40
	private Act35sideMilestoneDisplayRewardItemView _prefabGrandReward; // 0x48
	private List`1 m_grandRewardViewList; // 0x50
	private Boolean m_hasInited; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32537b4 VA: 0x759586b7b4
	public override Void Render(TemplateActivityMilestoneGroupViewModel viewModel) { }
	// RVA: 0x3253ad8 VA: 0x759586bad8
	private Void _InitIfNot() { }
	// RVA: 0x3253cf8 VA: 0x759586bcf8
	public Void .ctor() { }
}
```