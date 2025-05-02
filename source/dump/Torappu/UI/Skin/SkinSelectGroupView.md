# SkinSelectGroupView

**Namespace:** `Torappu.UI.Skin`


## Fields

- `Text _skinGroupObj`

- `Text _defaultSkinGroupObj`

- `Text _skinGroupConstText`

- `Text _defaultSkinGroupConstText`

- `Image _colorImgBack`

- `GameObject _defaultTypePart`

- `GameObject _buyableTypePart`

- `SimpleLayoutContent _leftContent`

- `SimpleLayoutContent _rightContent`

- `Adapter m_leftAdapter`

- `Adapter m_rightAdapter`

- `Single m_currentScroll`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void InitData(List`1)`

- `Void ApplyState(Single, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Skin
public class SkinSelectGroupView : MonoBehaviour, IHotfixable
{
	private Text _skinGroupObj; // 0x18
	private Text _defaultSkinGroupObj; // 0x20
	private Text _skinGroupConstText; // 0x28
	private Text _defaultSkinGroupConstText; // 0x30
	private Image _colorImgBack; // 0x38
	private GameObject _defaultTypePart; // 0x40
	private GameObject _buyableTypePart; // 0x48
	private SimpleLayoutContent _leftContent; // 0x50
	private SimpleLayoutContent _rightContent; // 0x58
	private Adapter m_leftAdapter; // 0x60
	private Adapter m_rightAdapter; // 0x68
	private const Int32 MAXCOLORCOUNT; // 0x0
	private Single m_currentScroll; // 0x70
	private List`1 m_viewModelList; // 0x78
	private Boolean m_isInited; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge __Hotfix0_ApplyState; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x23d5200 VA: 0x75949ed200
	private Void _InitIfNot() { }
	// RVA: 0x23d5378 VA: 0x75949ed378
	public Void InitData(List`1 viewModel) { }
	// RVA: 0x23d5404 VA: 0x75949ed404
	public Void ApplyState(Single state, Boolean shopTitleBarFlag) { }
	// RVA: 0x23d5bd4 VA: 0x75949edbd4
	public Void .ctor() { }
}
```