# Act13sideDailySearchOrgItemView

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `GameObject _selectedBgGo`

- `GameObject _normalBgGo`

- `GameObject _normalPartGo`

- `GameObject _lockPartGo`

- `Image _imgLogo`

- `Image _imgTextBg`

- `Text _textPrestige`

- `Color _colorNormal`

- `Color _colorNormalText`

- `Color _colorSelected`

- `Color _colorSelectedText`

- `OrgData m_orgData`


## Methods

- `Void set_onItemClick(Action`1)`

- `Void Render(Act13sideDailySearchViewModel, OrgData)`

- `Void OnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideDailySearchOrgItemView : MonoBehaviour, IHotfixable
{
	private GameObject _selectedBgGo; // 0x18
	private GameObject _normalBgGo; // 0x20
	private GameObject _normalPartGo; // 0x28
	private GameObject _lockPartGo; // 0x30
	private Image _imgLogo; // 0x38
	private Image _imgTextBg; // 0x40
	private Text _textPrestige; // 0x48
	private Color _colorNormal; // 0x50
	private Color _colorNormalText; // 0x60
	private Color _colorSelected; // 0x70
	private Color _colorSelectedText; // 0x80
	private Action`1 <onItemClick>k__BackingField; // 0x90
	private OrgData m_orgData; // 0x98
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onItemClick { get; set; }

	// RVA: 0x3440ea0 VA: 0x7595a58ea0
	private Action`1 get_onItemClick() { }
	// RVA: 0x343fca8 VA: 0x7595a57ca8
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x343fd2c VA: 0x7595a57d2c
	public Void Render(Act13sideDailySearchViewModel searchModel, OrgData orgData) { }
	// RVA: 0x3440f08 VA: 0x7595a58f08
	public Void OnItemClick() { }
	// RVA: 0x3440fb0 VA: 0x7595a58fb0
	public Void .ctor() { }
}
```