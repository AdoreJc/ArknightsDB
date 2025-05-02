# FireworkPlateView

**Namespace:** `Torappu.UI.Firework`


## Fields

- `RectTransform _elementContainer`

- `FireworkPlateElementView _prefabElementView`

- `Vector2 _gridSize`

- `Vector2 _padding`

- `UIAtlasImage _imgBkgOutline`

- `Single _tweenDuration`

- `UIAtlasImage _imgBkgFront`

- `UIAtlasImage _imgBkgShadow`

- `Tween m_tween`

- `Int32 m_cachedLoadSeqNum`


## Methods

- `Void Render(FireworkPlateModel, FireworkPlateViewStyle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework
public class FireworkPlateView : MonoBehaviour, IHotfixable
{
	private RectTransform _elementContainer; // 0x18
	private FireworkPlateElementView _prefabElementView; // 0x20
	private Vector2 _gridSize; // 0x28
	private Vector2 _padding; // 0x30
	private UIAtlasImage _imgBkgOutline; // 0x38
	private Single _tweenDuration; // 0x40
	private UIAtlasImage _imgBkgFront; // 0x48
	private UIAtlasImage _imgBkgShadow; // 0x50
	private List`1 m_gridElements; // 0x58
	private Tween m_tween; // 0x60
	private Int32 m_cachedLoadSeqNum; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x28f2d78 VA: 0x7594f0ad78
	public Void Render(FireworkPlateModel plateModel, FireworkPlateViewStyle style) { }
	// RVA: 0x28f3268 VA: 0x7594f0b268
	public Void .ctor() { }
}
```