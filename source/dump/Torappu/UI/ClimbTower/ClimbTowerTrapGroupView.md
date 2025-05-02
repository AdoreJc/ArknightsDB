# ClimbTowerTrapGroupView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `SimpleLayoutContent _itemLayoutContent`

- `UIAtlasImage _imgGroupBkg`

- `UIAtlasObject _atlasObject`

- `String _godCardGroupBkgId`

- `String _curseGroupBkgId`

- `String _trapGroupBkgId`

- `ClimbTowerTrapGroupViewModel m_trapGroupViewModel`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void Render(ClimbTowerTrapGroupViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerTrapGroupView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _itemLayoutContent; // 0x18
	private UIAtlasImage _imgGroupBkg; // 0x20
	private UIAtlasObject _atlasObject; // 0x28
	private String _godCardGroupBkgId; // 0x30
	private String _curseGroupBkgId; // 0x38
	private String _trapGroupBkgId; // 0x40
	private ClimbTowerTrapGroupViewModel m_trapGroupViewModel; // 0x48
	private Boolean m_hasInited; // 0x50
	private Adapter m_adapter; // 0x58
	private UIPage <page>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private UIPage page { get; set; }

	// RVA: 0x2c8e29c VA: 0x75952a629c
	private UIPage get_page() { }
	// RVA: 0x2c8e304 VA: 0x75952a6304
	public Void set_page(UIPage value) { }
	// RVA: 0x2c8e388 VA: 0x75952a6388
	public Void Render(ClimbTowerTrapGroupViewModel trapGroupViewModel) { }
	// RVA: 0x2c8e544 VA: 0x75952a6544
	private Void _InitIfNot() { }
	// RVA: 0x2c8e710 VA: 0x75952a6710
	public Void .ctor() { }
}
```