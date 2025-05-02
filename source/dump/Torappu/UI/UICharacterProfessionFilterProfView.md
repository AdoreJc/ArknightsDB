# UICharacterProfessionFilterProfView

**Namespace:** `Torappu.UI`


## Fields

- `UICharacterProfessionFilterProfItem _allItem`

- `SimpleLayoutContent _content`

- `RectTransform _cursorRect`

- `RectTransform _cursorContainer`

- `CanvasGroup _cursorBackCg`

- `ILoadAsset assetLoader`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `Tween m_moveTween`

- `FadeSwitchTween m_cursorSwitch`

- `RectTransform m_cachedCursorTarget`

- `UILayoutDimensionListener m_dimensionListener`

- `UICharacterProfessionFilterViewModel m_cachedModel`


## Methods

- `Void _InitIfNot()`

- `Void Render(UICharacterProfessionFilterViewModel, Boolean)`

- `Void _RenderCursor(UICharacterProfessionFilterViewModel, Boolean)`

- `Void _MoveCursor(RectTransform, Boolean, Boolean)`

- `Void _OnPostLayout()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterProfessionFilterProfView : MonoBehaviour, IHotfixable
{
	private const Single MOVE_DURATION; // 0x0
	private UICharacterProfessionFilterProfItem _allItem; // 0x18
	private SimpleLayoutContent _content; // 0x20
	private RectTransform _cursorRect; // 0x28
	private RectTransform _cursorContainer; // 0x30
	private CanvasGroup _cursorBackCg; // 0x38
	public ILoadAsset assetLoader; // 0x40
	public Action`2 onProfessionClick; // 0x48
	private Boolean m_isInited; // 0x50
	private Adapter m_adapter; // 0x58
	private Tween m_moveTween; // 0x60
	private FadeSwitchTween m_cursorSwitch; // 0x68
	private RectTransform m_cachedCursorTarget; // 0x70
	private UILayoutDimensionListener m_dimensionListener; // 0x78
	private UICharacterProfessionFilterViewModel m_cachedModel; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__RenderCursor; // 0x10
	private static DelegateBridge __Hotfix0__MoveCursor; // 0x18
	private static DelegateBridge __Hotfix0__OnPostLayout; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2125510 VA: 0x759473d510
	private Void _InitIfNot() { }
	// RVA: 0x21257fc VA: 0x759473d7fc
	public Void Render(UICharacterProfessionFilterViewModel model, Boolean isFastMode) { }
	// RVA: 0x21258e8 VA: 0x759473d8e8
	private Void _RenderCursor(UICharacterProfessionFilterViewModel model, Boolean isFastMode) { }
	// RVA: 0x2125b48 VA: 0x759473db48
	private Void _MoveCursor(RectTransform target, Boolean isFastMode, Boolean forceUpdate) { }
	// RVA: 0x2125d70 VA: 0x759473dd70
	private Void _OnPostLayout() { }
	// RVA: 0x2125de4 VA: 0x759473dde4
	public Void .ctor() { }
}
```