# ShopRecommendItemView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Button _button`

- `Single _lockMaskAlpha`

- `GameObject _lockedObj`

- `Image m_image`

- `CanvasGroup m_canvasGroup`


## Methods

- `Void Render(Sprite, Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopRecommendItemView : MonoBehaviour, IHotfixable
{
	private Button _button; // 0x18
	private Single _lockMaskAlpha; // 0x20
	private GameObject _lockedObj; // 0x28
	private Image m_image; // 0x30
	private CanvasGroup m_canvasGroup; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x245ae1c VA: 0x7594a72e1c
	public Void Render(Sprite imageSprite, Boolean isLocked) { }
	// RVA: 0x245afc0 VA: 0x7594a72fc0
	private Void _InitIfNot() { }
	// RVA: 0x245b0cc VA: 0x7594a730cc
	public Void .ctor() { }
}
```