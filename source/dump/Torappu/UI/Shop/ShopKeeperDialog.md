# ShopKeeperDialog

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Text _text`

- `ShopKeeperWord <currentWord>k__BackingField`

- `CanvasGroup m_canvasGroup`

- `FadeSwitchTween m_fadeSwitchTween`


## Properties

- `Boolean isShown`

- `ShopKeeperWord currentWord`

- `CanvasGroup canvasGroup`

- `FadeSwitchTween fadeSwitchTween`


## Methods

- `Boolean get_isShown()`

- `Void set_isShown(Boolean)`

- `ShopKeeperWord get_currentWord()`

- `Void set_currentWord(ShopKeeperWord)`

- `CanvasGroup get_canvasGroup()`

- `FadeSwitchTween get_fadeSwitchTween()`

- `Void SetData(ShopKeeperWord, Boolean)`

- `Void _UpdateShown(Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopKeeperDialog : MonoBehaviour
{
	private const Single FADE_DURATION; // 0x0
	private Text _text; // 0x18
	private ShopKeeperWord <currentWord>k__BackingField; // 0x20
	private CanvasGroup m_canvasGroup; // 0x28
	private FadeSwitchTween m_fadeSwitchTween; // 0x30

	public Boolean isShown { get; set; }
	public ShopKeeperWord currentWord { get; set; }
	private CanvasGroup canvasGroup { get; }
	private FadeSwitchTween fadeSwitchTween { get; }

	// RVA: 0x24665fc VA: 0x7594a7e5fc
	public Boolean get_isShown() { }
	// RVA: 0x24666b4 VA: 0x7594a7e6b4
	public Void set_isShown(Boolean value) { }
	// RVA: 0x2466728 VA: 0x7594a7e728
	public ShopKeeperWord get_currentWord() { }
	// RVA: 0x2466730 VA: 0x7594a7e730
	private Void set_currentWord(ShopKeeperWord value) { }
	// RVA: 0x2466738 VA: 0x7594a7e738
	private CanvasGroup get_canvasGroup() { }
	// RVA: 0x2466618 VA: 0x7594a7e618
	private FadeSwitchTween get_fadeSwitchTween() { }
	// RVA: 0x24667e0 VA: 0x7594a7e7e0
	public Void SetData(ShopKeeperWord word, Boolean force) { }
	// RVA: 0x24666c0 VA: 0x7594a7e6c0
	private Void _UpdateShown(Boolean value, Boolean force) { }
	// RVA: 0x2466870 VA: 0x7594a7e870
	public Void .ctor() { }
}
```