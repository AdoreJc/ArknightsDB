# HomeCheckInCommonRewardView

**Namespace:** `Torappu.UI.Home`


## Fields

- `GameObject _panelGradient`

- `GameObject _panelDailyBonus`

- `SimpleLayoutContent _dailyBonusContent`

- `GameObject _panelDailyBonusCountDown`

- `Text _textDailyBonusRemainTime`

- `Text _textDailyBonusTitle`

- `SimpleLayoutContent _normalRewardContent`

- `Text _textNormalRewardTitle`

- `Boolean m_hasInited`

- `Adapter m_dailyBonusAdapter`

- `Adapter m_normalRewardAdapter`


## Methods

- `Void _InitIfNot()`

- `Void _RenderDailyBonus(HomeCheckInViewModel)`

- `Void _RenderNormalReward(HomeCheckInViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCheckInCommonRewardView : DataBinder`1, IHotfixable
{
	private const Int32 COUNT_DOWN_LIMIT_DAYS; // 0x0
	private GameObject _panelGradient; // 0x20
	private GameObject _panelDailyBonus; // 0x28
	private SimpleLayoutContent _dailyBonusContent; // 0x30
	private GameObject _panelDailyBonusCountDown; // 0x38
	private Text _textDailyBonusRemainTime; // 0x40
	private Text _textDailyBonusTitle; // 0x48
	private SimpleLayoutContent _normalRewardContent; // 0x50
	private Text _textNormalRewardTitle; // 0x58
	private Boolean m_hasInited; // 0x60
	private Adapter m_dailyBonusAdapter; // 0x68
	private Adapter m_normalRewardAdapter; // 0x70
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RenderDailyBonus; // 0x10
	private static DelegateBridge __Hotfix0__RenderNormalReward; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x282e7a8 VA: 0x7594e467a8
	public override Void OnValueChanged(HomeCheckInProperty property) { }
	// RVA: 0x282e880 VA: 0x7594e46880
	private Void _InitIfNot() { }
	// RVA: 0x282e99c VA: 0x7594e4699c
	private Void _RenderDailyBonus(HomeCheckInViewModel model) { }
	// RVA: 0x282ec98 VA: 0x7594e46c98
	private Void _RenderNormalReward(HomeCheckInViewModel model) { }
	// RVA: 0x282ee28 VA: 0x7594e46e28
	public Void .ctor() { }
}
```