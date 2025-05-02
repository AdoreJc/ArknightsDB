# Act24sideNoteView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `GameObject _leftArrow`

- `GameObject _rightArrow`

- `ScrollViewPager _scrollViewPager`

- `Int32 _noteCount`

- `Boolean m_isInited`


## Methods

- `Void Render()`

- `Void _UpdateArrowDisplay(Int32)`

- `Void _InitIfNot()`

- `Void TransToLeft()`

- `Void TransToRight()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideNoteView : MonoBehaviour, IHotfixable
{
	private GameObject _leftArrow; // 0x18
	private GameObject _rightArrow; // 0x20
	private ScrollViewPager _scrollViewPager; // 0x28
	private Int32 _noteCount; // 0x30
	private Boolean m_isInited; // 0x34
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__UpdateArrowDisplay; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_TransToLeft; // 0x18
	private static DelegateBridge __Hotfix0_TransToRight; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x32c0404 VA: 0x75958d8404
	public Void Render() { }
	// RVA: 0x32c07a4 VA: 0x75958d87a4
	private Void _UpdateArrowDisplay(Int32 page) { }
	// RVA: 0x32c069c VA: 0x75958d869c
	private Void _InitIfNot() { }
	// RVA: 0x32c0848 VA: 0x75958d8848
	public Void TransToLeft() { }
	// RVA: 0x32c08f4 VA: 0x75958d88f4
	public Void TransToRight() { }
	// RVA: 0x32c09a8 VA: 0x75958d89a8
	public Void .ctor() { }
}
```