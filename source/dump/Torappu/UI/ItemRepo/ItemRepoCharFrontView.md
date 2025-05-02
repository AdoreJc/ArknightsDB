# ItemRepoCharFrontView

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `Image _professionImg`

- `Text _charName`

- `Text _charTopName`

- `Image _charRarity`

- `Image _potentialImg`

- `GameObject _potentialBg`

- `GameObject _awarded`


## Methods

- `Void Render(ItemBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoCharFrontView : MonoBehaviour, IHotfixable
{
	private Image _professionImg; // 0x18
	private Text _charName; // 0x20
	private Text _charTopName; // 0x28
	private Image _charRarity; // 0x30
	private Image _potentialImg; // 0x38
	private GameObject _potentialBg; // 0x40
	private GameObject _awarded; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2d31588 VA: 0x7595349588
	public Void Render(ItemBundle charInfo) { }
	// RVA: 0x2d317f4 VA: 0x75953497f4
	public Void .ctor() { }
}
```