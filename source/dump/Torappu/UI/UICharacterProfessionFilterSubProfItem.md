# UICharacterProfessionFilterSubProfItem

**Namespace:** `Torappu.UI`


## Fields

- `Text _name`

- `Image _profIcon`

- `GameObject _bg`

- `Color _colorSelected`

- `Color _colorUnSelected`

- `Single _alphaInvalid`

- `ILoadAsset assetLoader`

- `String m_cachedSubProf`


## Methods

- `Void Render(UICharacterProfessionFilterViewModel, ProfessionFilterSubProfItemViewModel, Boolean)`

- `Void _RenderView(String, String)`

- `Void _RenderSelect(Boolean, Boolean)`

- `Void OnAllClick()`

- `Void OnProfessionClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterProfessionFilterSubProfItem : MonoBehaviour, IHotfixable
{
	private Text _name; // 0x18
	private Image _profIcon; // 0x20
	private GameObject _bg; // 0x28
	private Color _colorSelected; // 0x30
	private Color _colorUnSelected; // 0x40
	private Single _alphaInvalid; // 0x50
	public ILoadAsset assetLoader; // 0x58
	public Action`2 onSubProfessionClick; // 0x60
	private String m_cachedSubProf; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderView; // 0x8
	private static DelegateBridge __Hotfix0__RenderSelect; // 0x10
	private static DelegateBridge __Hotfix0_OnAllClick; // 0x18
	private static DelegateBridge __Hotfix0_OnProfessionClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2126180 VA: 0x759473e180
	public Void Render(UICharacterProfessionFilterViewModel model, ProfessionFilterSubProfItemViewModel itemModel, Boolean isAllItem) { }
	// RVA: 0x2126310 VA: 0x759473e310
	private Void _RenderView(String name, String iconId) { }
	// RVA: 0x2126448 VA: 0x759473e448
	private Void _RenderSelect(Boolean isSelected, Boolean isSubProfInvalid) { }
	// RVA: 0x2126608 VA: 0x759473e608
	public Void OnAllClick() { }
	// RVA: 0x2126694 VA: 0x759473e694
	public Void OnProfessionClick() { }
	// RVA: 0x2126730 VA: 0x759473e730
	public Void .ctor() { }
}
```