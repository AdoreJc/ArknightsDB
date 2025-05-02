# ClimbTowerBuffTabItemView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `TwoStateToggle _displayToggle`

- `Text _textType1`

- `Text _textType2`

- `Image _imgUnselectBg`

- `Color _colorLocked`

- `Color _colorNormal`

- `Int32 m_index`

- `TacticalBuffItemModel m_buffItemModel`


## Methods

- `Void set_onTabClick(Action`2)`

- `Void Render(Int32, Boolean, TacticalBuffItemModel)`

- `Void OnTabClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerBuffTabItemView : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _displayToggle; // 0x18
	private Text _textType1; // 0x20
	private Text _textType2; // 0x28
	private Image _imgUnselectBg; // 0x30
	private Color _colorLocked; // 0x38
	private Color _colorNormal; // 0x48
	private Action`2 <onTabClick>k__BackingField; // 0x58
	private Int32 m_index; // 0x60
	private TacticalBuffItemModel m_buffItemModel; // 0x68
	private static DelegateBridge __Hotfix0_get_onTabClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onTabClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnTabClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`2 onTabClick { get; set; }

	// RVA: 0x2c8cbf0 VA: 0x75952a4bf0
	private Action`2 get_onTabClick() { }
	// RVA: 0x2c8cc58 VA: 0x75952a4c58
	public Void set_onTabClick(Action`2 value) { }
	// RVA: 0x2c8ccdc VA: 0x75952a4cdc
	public Void Render(Int32 index, Boolean isSelect, TacticalBuffItemModel buffItemModel) { }
	// RVA: 0x2c8cebc VA: 0x75952a4ebc
	public Void OnTabClick() { }
	// RVA: 0x2c8cfc8 VA: 0x75952a4fc8
	public Void .ctor() { }
}
```