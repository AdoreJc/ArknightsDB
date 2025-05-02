# DIYComfortDetailView

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DIYComfortDetailGroupAdapter _furnitureAdapter`

- `DIYComfortDetailGroupAdapter _groupAdapter`

- `Text _furnitureTotalLabel`

- `Text _groupTotalLabel`

- `Text _totalLabel`

- `Image _backgroundImage`

- `CanvasGroup _canvasGroup`

- `Single _fadeDuration`

- `Text _furnitureComfortRuleHintLabel`

- `GameObject _furnitureComfortRuleHintPanel`


## Methods

- `Void Show()`

- `Void Hide()`

- `Void Setup(Int32, IFurnitureProvider, IDIYRoomModifierProvider, Int32, Int32)`

- `Void <Hide>b__14_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYComfortDetailView : MonoBehaviour, IHotfixable
{
	private DIYComfortDetailGroupAdapter _furnitureAdapter; // 0x18
	private DIYComfortDetailGroupAdapter _groupAdapter; // 0x20
	private Text _furnitureTotalLabel; // 0x28
	private Text _groupTotalLabel; // 0x30
	private Text _totalLabel; // 0x38
	private Image _backgroundImage; // 0x40
	private CanvasGroup _canvasGroup; // 0x48
	private Single _fadeDuration; // 0x50
	private Text _furnitureComfortRuleHintLabel; // 0x58
	private GameObject _furnitureComfortRuleHintPanel; // 0x60
	private static DelegateBridge __Hotfix0_Show; // 0x0
	private static DelegateBridge __Hotfix0_Hide; // 0x8
	private static DelegateBridge __Hotfix0_Setup; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3813d08 VA: 0x7595e2bd08
	public Void Show() { }
	// RVA: 0x3813df0 VA: 0x7595e2bdf0
	public Void Hide() { }
	// RVA: 0x3813f64 VA: 0x7595e2bf64
	public Void Setup(Int32 roomIndex, IFurnitureProvider furnitureProvider, IDIYRoomModifierProvider modifierProvider, Int32 maxComfort, Int32 comfortFurniLimit) { }
	// RVA: 0x3814920 VA: 0x7595e2c920
	public Void .ctor() { }
	// RVA: 0x3814990 VA: 0x7595e2c990
	private Void <Hide>b__14_0() { }
}
```