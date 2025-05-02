# ClimbTowerTrapItemView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Image _imgIcon`

- `Text _textName`

- `Text _textDesc`

- `UIAtlasImage _imgTrapBkg`

- `GameObject _panelArrow`

- `UIAtlasImage _imgNameBkg`

- `UIAtlasObject _atlasObject`

- `String _mainCardBkgId`

- `String _subCardBkgId`

- `String _subCardEmptyBkgId`

- `String _curseCardBkgId`

- `String _trapCardBkgId`

- `String _nameNormalBkgId`

- `String _nameEmptyBkgId`

- `String _nameCurseBkgId`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void Render(ClimbTowerTrapViewModel)`

- `Void _RenderViewWithType(ClimbTowerTrapViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerTrapItemView : MonoBehaviour, IHotfixable
{
	private Image _imgIcon; // 0x18
	private Text _textName; // 0x20
	private Text _textDesc; // 0x28
	private UIAtlasImage _imgTrapBkg; // 0x30
	private GameObject _panelArrow; // 0x38
	private UIAtlasImage _imgNameBkg; // 0x40
	private UIAtlasObject _atlasObject; // 0x48
	private String _mainCardBkgId; // 0x50
	private String _subCardBkgId; // 0x58
	private String _subCardEmptyBkgId; // 0x60
	private String _curseCardBkgId; // 0x68
	private String _trapCardBkgId; // 0x70
	private String _nameNormalBkgId; // 0x78
	private String _nameEmptyBkgId; // 0x80
	private String _nameCurseBkgId; // 0x88
	private UIPage <page>k__BackingField; // 0x90
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__RenderViewWithType; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private UIPage page { get; set; }

	// RVA: 0x2c8ec20 VA: 0x75952a6c20
	private UIPage get_page() { }
	// RVA: 0x2c8ea64 VA: 0x75952a6a64
	public Void set_page(UIPage value) { }
	// RVA: 0x2c8eae8 VA: 0x75952a6ae8
	public Void Render(ClimbTowerTrapViewModel trapViewModel) { }
	// RVA: 0x2c8edc0 VA: 0x75952a6dc0
	private Void _RenderViewWithType(ClimbTowerTrapViewModel trapViewModel) { }
	// RVA: 0x2c8f1a0 VA: 0x75952a71a0
	public Void .ctor() { }
}
```