# ClimbTowerEntryGodCardSubCardView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `CanvasGroup _canvasGroupComplete`

- `Text _textCardName`

- `Text _textDesc`

- `Image _imgIcon`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void Render(ClimbTowerEntrySubCardModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryGodCardSubCardView : MonoBehaviour, IHotfixable
{
	private const Single ALPHA_USED; // 0x0
	private const Single ALPHA_UNUSED; // 0x0
	private CanvasGroup _canvasGroupComplete; // 0x18
	private Text _textCardName; // 0x20
	private Text _textDesc; // 0x28
	private Image _imgIcon; // 0x30
	private UIPage <page>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private UIPage page { get; set; }

	// RVA: 0x2c667e8 VA: 0x759527e7e8
	private UIPage get_page() { }
	// RVA: 0x2c66478 VA: 0x759527e478
	public Void set_page(UIPage value) { }
	// RVA: 0x2c66208 VA: 0x759527e208
	public Void Render(ClimbTowerEntrySubCardModel cardModel) { }
	// RVA: 0x2c66850 VA: 0x759527e850
	public Void .ctor() { }
}
```