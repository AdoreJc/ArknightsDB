# UICharacterProfessionFilterSubProfView

**Namespace:** `Torappu.UI`


## Fields

- `UICharacterProfessionFilterSubProfItem _allItem`

- `SimpleLayoutContent _content`

- `ScrollRect _scrollRect`

- `ILoadAsset assetLoader`

- `Boolean m_isInited`

- `Boolean m_isOpen`

- `ProfessionCategory m_prof`

- `Adapter m_adapter`

- `UICharacterProfessionFilterViewModel m_cachedModel`

- `UILayoutDimensionListener m_dimensionListener`


## Methods

- `Void _InitIfNot()`

- `Void Render(UICharacterProfessionFilterViewModel, Boolean)`

- `Void _OnPostLayout()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterProfessionFilterSubProfView : MonoBehaviour, IHotfixable
{
	private UICharacterProfessionFilterSubProfItem _allItem; // 0x18
	private SimpleLayoutContent _content; // 0x20
	private ScrollRect _scrollRect; // 0x28
	public ILoadAsset assetLoader; // 0x30
	public Action`2 onSubProfessionClick; // 0x38
	private Boolean m_isInited; // 0x40
	private Boolean m_isOpen; // 0x41
	private ProfessionCategory m_prof; // 0x44
	private Adapter m_adapter; // 0x48
	private UICharacterProfessionFilterViewModel m_cachedModel; // 0x50
	private UILayoutDimensionListener m_dimensionListener; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__OnPostLayout; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x21267a8 VA: 0x759473e7a8
	private Void _InitIfNot() { }
	// RVA: 0x2126974 VA: 0x759473e974
	public Void Render(UICharacterProfessionFilterViewModel model, Boolean isOpen) { }
	// RVA: 0x2126b50 VA: 0x759473eb50
	private Void _OnPostLayout() { }
	// RVA: 0x2126cd8 VA: 0x759473ecd8
	public Void .ctor() { }
}
```