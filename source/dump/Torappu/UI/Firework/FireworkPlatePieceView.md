# FireworkPlatePieceView

**Namespace:** `Torappu.UI.Firework`


## Fields

- `Image _imgPlatePiece`

- `RectTransform _rectTransform`

- `PlateSlotData m_cachedSlotData`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(PlateSlotData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework
public class FireworkPlatePieceView : MonoBehaviour, IHotfixable
{
	private Image _imgPlatePiece; // 0x18
	private RectTransform _rectTransform; // 0x20
	private PlateSlotData m_cachedSlotData; // 0x28
	private UIStateFinder m_stateFinder; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x28ec474 VA: 0x7594f04474
	public Void Render(PlateSlotData plateSlotData) { }
	// RVA: 0x28f16a8 VA: 0x7594f096a8
	public Void .ctor() { }
}
```