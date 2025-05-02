# Act24sideMeldingGoodGridView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `UIAtlasImage _imgTitle`

- `UIAtlasImage _imgTitleLeft`

- `UIAtlasImage _imgTitleRight`

- `UIAtlasObject _atlas`

- `SimpleLayoutContent _layoutContent`

- `MeldingGoodDisplayType m_cachedDisplayType`

- `Adapter m_adapter`

- `Act24sideMeldingGoodDisplayViewModel m_model`

- `Boolean m_isInited`

- `MeldingGoodDisplayType m_displayType`

- `UILayoutDimensionListener m_dimensionListener`

- `String m_cachedColThemeStr`


## Methods

- `Void set_onGridPostLayout(Action`1)`

- `Void Render(Act24sideMeldingGoodDisplayViewModel)`

- `Void _InitIfNot()`

- `Void _RefreshThemeCol()`

- `Void _OnPostLayout()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMeldingGoodGridView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _imgTitle; // 0x18
	private UIAtlasImage _imgTitleLeft; // 0x20
	private UIAtlasImage _imgTitleRight; // 0x28
	private UIAtlasObject _atlas; // 0x30
	private SimpleLayoutContent _layoutContent; // 0x38
	private MeldingGoodDisplayType m_cachedDisplayType; // 0x40
	private Adapter m_adapter; // 0x48
	private Act24sideMeldingGoodDisplayViewModel m_model; // 0x50
	private static readonly String TITLE_PREFIX; // 0x0
	private Boolean m_isInited; // 0x58
	private MeldingGoodDisplayType m_displayType; // 0x5c
	private UILayoutDimensionListener m_dimensionListener; // 0x60
	private String m_cachedColThemeStr; // 0x68
	private Action`1 <onGridPostLayout>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_onGridPostLayout; // 0x8
	private static DelegateBridge __Hotfix0_set_onGridPostLayout; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__RefreshThemeCol; // 0x28
	private static DelegateBridge __Hotfix0__OnPostLayout; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Action`1 onGridPostLayout { get; set; }

	// RVA: 0x32a136c VA: 0x75958b936c
	public Action`1 get_onGridPostLayout() { }
	// RVA: 0x32a13e4 VA: 0x75958b93e4
	public Void set_onGridPostLayout(Action`1 value) { }
	// RVA: 0x32a1478 VA: 0x75958b9478
	public Void Render(Act24sideMeldingGoodDisplayViewModel groupViewModel) { }
	// RVA: 0x32a16a4 VA: 0x75958b96a4
	private Void _InitIfNot() { }
	// RVA: 0x32a18d4 VA: 0x75958b98d4
	private Void _RefreshThemeCol() { }
	// RVA: 0x32a1a3c VA: 0x75958b9a3c
	private Void _OnPostLayout() { }
	// RVA: 0x32a1af4 VA: 0x75958b9af4
	public Void .ctor() { }
	// RVA: 0x32a1b74 VA: 0x75958b9b74
	private static Void .cctor() { }
}
```