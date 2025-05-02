# UICharacterProfessionFilterProfItem

**Namespace:** `Torappu.UI`


## Fields

- `Image _profIcon`

- `Graphic _colorGraphic`

- `GameObject _panelSubShow`

- `GameObject _panelSubHide`

- `GameObject _panelSubSelected`

- `Color _colorSelected`

- `Color _colorUnSelected`

- `ILoadAsset assetLoader`

- `ProfessionCategory m_cachedProf`


## Methods

- `Void Render(UICharacterProfessionFilterViewModel, ProfessionFilterProfItemViewModel, Boolean)`

- `Void _RenderImpl(Boolean, Boolean, Boolean)`

- `Void OnAllClick()`

- `Void OnProfessionClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterProfessionFilterProfItem : MonoBehaviour, IHotfixable
{
	private Image _profIcon; // 0x18
	private Graphic _colorGraphic; // 0x20
	private GameObject _panelSubShow; // 0x28
	private GameObject _panelSubHide; // 0x30
	private GameObject _panelSubSelected; // 0x38
	private Color _colorSelected; // 0x40
	private Color _colorUnSelected; // 0x50
	public ILoadAsset assetLoader; // 0x60
	public Action`2 onProfessionClick; // 0x68
	private ProfessionCategory m_cachedProf; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderImpl; // 0x8
	private static DelegateBridge __Hotfix0_OnAllClick; // 0x10
	private static DelegateBridge __Hotfix0_OnProfessionClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2125038 VA: 0x759473d038
	public Void Render(UICharacterProfessionFilterViewModel model, ProfessionFilterProfItemViewModel itemModel, Boolean isAllItem) { }
	// RVA: 0x212522c VA: 0x759473d22c
	private Void _RenderImpl(Boolean isSelected, Boolean isSubProfSelected, Boolean isSubShow) { }
	// RVA: 0x212537c VA: 0x759473d37c
	public Void OnAllClick() { }
	// RVA: 0x2125408 VA: 0x759473d408
	public Void OnProfessionClick() { }
	// RVA: 0x21254a0 VA: 0x759473d4a0
	public Void .ctor() { }
}
```