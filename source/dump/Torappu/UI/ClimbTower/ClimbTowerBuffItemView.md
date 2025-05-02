# ClimbTowerBuffItemView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Text _textProfession`

- `Text _textDesc`

- `Text _textBuffName`

- `UIAtlasImage _imgProfession`

- `UIAtlasObject _professionAtlas`

- `UIAnimationLocation _toggleAnim`

- `Image _imgToggleBg`

- `Single _disableToggleAlpha`

- `TacticalBuffModel m_tacticalBuffModel`

- `Boolean m_hasInited`

- `AnimationSwitchTween m_toggleSwitchTween`


## Methods

- `Void set_onBuffToggle(Action`1)`

- `Void Render(TacticalBuffModel, Boolean)`

- `Void _InitIfNot()`

- `Void OnBuffToggle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerBuffItemView : MonoBehaviour, IHotfixable
{
	private Text _textProfession; // 0x18
	private Text _textDesc; // 0x20
	private Text _textBuffName; // 0x28
	private UIAtlasImage _imgProfession; // 0x30
	private UIAtlasObject _professionAtlas; // 0x38
	private UIAnimationLocation _toggleAnim; // 0x40
	private Image _imgToggleBg; // 0x50
	private Single _disableToggleAlpha; // 0x58
	private TacticalBuffModel m_tacticalBuffModel; // 0x60
	private Boolean m_hasInited; // 0x68
	private AnimationSwitchTween m_toggleSwitchTween; // 0x70
	private Action`1 <onBuffToggle>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_onBuffToggle; // 0x0
	private static DelegateBridge __Hotfix0_set_onBuffToggle; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_OnBuffToggle; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onBuffToggle { get; set; }

	// RVA: 0x2c88bb8 VA: 0x75952a0bb8
	private Action`1 get_onBuffToggle() { }
	// RVA: 0x2c88c20 VA: 0x75952a0c20
	public Void set_onBuffToggle(Action`1 value) { }
	// RVA: 0x2c88ca4 VA: 0x75952a0ca4
	public Void Render(TacticalBuffModel tacticalBuffModel, Boolean canToggle) { }
	// RVA: 0x2c88ea8 VA: 0x75952a0ea8
	private Void _InitIfNot() { }
	// RVA: 0x2c89378 VA: 0x75952a1378
	public Void OnBuffToggle() { }
	// RVA: 0x2c89428 VA: 0x75952a1428
	public Void .ctor() { }
}
```