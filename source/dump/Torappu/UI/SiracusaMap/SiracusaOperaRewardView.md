# SiracusaOperaRewardView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `Text _charName`

- `Text _itemName`

- `Image _itemImage`

- `Image _charImage`

- `Text _closeText`


## Methods

- `Void Render(SiracusaOperaRewardViewModel, UIPage)`

- `Void _LoadIconSprite(String, String, UIPage)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaOperaRewardView : MonoBehaviour, IHotfixable
{
	private Text _charName; // 0x18
	private Text _itemName; // 0x20
	private Image _itemImage; // 0x28
	private Image _charImage; // 0x30
	private Text _closeText; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__LoadIconSprite; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x23f9214 VA: 0x7594a11214
	public Void Render(SiracusaOperaRewardViewModel itemData, UIPage page) { }
	// RVA: 0x23f9484 VA: 0x7594a11484
	private Void _LoadIconSprite(String itemIconId, String charCardId, UIPage page) { }
	// RVA: 0x23f9568 VA: 0x7594a11568
	public Void .ctor() { }
}
```