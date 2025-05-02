# SiracusaBigMapTaskArrow

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `CanvasGroup _alphaHandler`

- `RectTransform _transArrow`

- `Graphic _themeGraphic`

- `Vector2 _boundSize`

- `Vector2 m_cachedDirection`

- `Color m_cachedColor`

- `FadeSwitchTween m_switchTween`


## Properties

- `Vector2 boundSize`


## Methods

- `FadeSwitchTween _EnsureSwitchTween()`

- `Vector2 get_boundSize()`

- `Void Init()`

- `Void Disable()`

- `Void Render(Vector2, Color)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaBigMapTaskArrow : MonoBehaviour, IHotfixable
{
	private CanvasGroup _alphaHandler; // 0x18
	private RectTransform _transArrow; // 0x20
	private Graphic _themeGraphic; // 0x28
	private Vector2 _boundSize; // 0x30
	private Vector2 m_cachedDirection; // 0x38
	private Color m_cachedColor; // 0x40
	private FadeSwitchTween m_switchTween; // 0x50
	private static DelegateBridge __Hotfix0__EnsureSwitchTween; // 0x0
	private static DelegateBridge __Hotfix0_get_boundSize; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_Disable; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Vector2 boundSize { get; }

	// RVA: 0x240c288 VA: 0x7594a24288
	private FadeSwitchTween _EnsureSwitchTween() { }
	// RVA: 0x240c350 VA: 0x7594a24350
	public Vector2 get_boundSize() { }
	// RVA: 0x240c3b4 VA: 0x7594a243b4
	public Void Init() { }
	// RVA: 0x240c430 VA: 0x7594a24430
	public Void Disable() { }
	// RVA: 0x240c4ac VA: 0x7594a244ac
	public Void Render(Vector2 direction, Color themeColor) { }
	// RVA: 0x240c6c8 VA: 0x7594a246c8
	public Void .ctor() { }
}
```