# NameCardV2CollectModuleView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `GameObject _hotspot`

- `TwoStateToggle _dateToggle`

- `GameObject _dateSwitchGo`

- `Text _hiredTime`

- `Text _birthTime`

- `TwoStateToggle _assistThemeStateToggle`

- `Text _assistThemeName`

- `Text _assistThemeEnName`

- `Text _skinCount`

- `Text _characterCount`

- `SimpleLayoutContent _teamIconContent`

- `Image _operatorCollectPercent`

- `TwoStateToggle _operatorCollectToggle`

- `UIAnimationLocation _switchIconAnim`

- `Boolean m_hasInited`

- `TeamIconAdapter m_teamIconAdpter`

- `Tween m_switchIconTween`


## Methods

- `Void _InitIfNot()`

- `Void SwitchOperatorCountStyle()`

- `Void SwitchDateDisplay()`

- `Void CloseButtonFadeIn()`

- `Void <>xLuaBaseProxy_OnApplyStyle(NameCardV2SkinStyle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2CollectModuleView : NameCardV2BaseFixedModuleView`1
{
	private const String HIRED_TIME_FORMAT; // 0x0
	private const String BIRTH_TIME_FORMAT; // 0x0
	private const String CHAR_COLLECT_PERCENT_FORMAT; // 0x0
	private GameObject _hotspot; // 0x50
	private TwoStateToggle _dateToggle; // 0x58
	private GameObject _dateSwitchGo; // 0x60
	private Text _hiredTime; // 0x68
	private Text _birthTime; // 0x70
	private TwoStateToggle _assistThemeStateToggle; // 0x78
	private Text _assistThemeName; // 0x80
	private Text _assistThemeEnName; // 0x88
	private Text _skinCount; // 0x90
	private Text _characterCount; // 0x98
	private SimpleLayoutContent _teamIconContent; // 0xa0
	private Image _operatorCollectPercent; // 0xa8
	private TwoStateToggle _operatorCollectToggle; // 0xb0
	private UIAnimationLocation _switchIconAnim; // 0xb8
	private GameObject[] _switchOperatorObjects; // 0xc8
	private Image[] _themeColoredIcons; // 0xd0
	private Text[] _themeColoredTexts; // 0xd8
	private Boolean m_hasInited; // 0xe0
	private List`1 m_cachedTeamViewModelList; // 0xe8
	private TeamIconAdapter m_teamIconAdpter; // 0xf0
	private Tween m_switchIconTween; // 0xf8
	private static DelegateBridge __Hotfix0_OnModuleViewRendered; // 0x0
	private static DelegateBridge __Hotfix0_OnApplyStyle; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_SwitchOperatorCountStyle; // 0x18
	private static DelegateBridge __Hotfix0_SwitchDateDisplay; // 0x20
	private static DelegateBridge __Hotfix0_CloseButtonFadeIn; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x28e2648 VA: 0x7594efa648
	public override Void OnModuleViewRendered(NameCardV2CollectModuleModel model) { }
	// RVA: 0x28e2c8c VA: 0x7594efac8c
	protected override Void OnApplyStyle(NameCardV2SkinStyle style) { }
	// RVA: 0x28e2bbc VA: 0x7594efabbc
	private Void _InitIfNot() { }
	// RVA: 0x28e3058 VA: 0x7594efb058
	public Void SwitchOperatorCountStyle() { }
	// RVA: 0x28e32c8 VA: 0x7594efb2c8
	public Void SwitchDateDisplay() { }
	// RVA: 0x28e3378 VA: 0x7594efb378
	public Void CloseButtonFadeIn() { }
	// RVA: 0x28e3428 VA: 0x7594efb428
	public Void .ctor() { }
	// RVA: 0x28e34b8 VA: 0x7594efb4b8
	private Void <>xLuaBaseProxy_OnApplyStyle(NameCardV2SkinStyle P0) { }
}
```