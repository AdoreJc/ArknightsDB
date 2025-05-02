# FadeInDecoIfScrollEnd

**Namespace:** `Torappu.UI`


## Fields

- `DecoInfo _topDecoInfo`

- `DecoInfo _downDecoInfo`

- `DecoInfo _leftDecoInfo`

- `DecoInfo _rightDecoInfo`

- `Boolean m_isInited`

- `Wrapper m_scrollRect`

- `Boolean m_isScrollVertical`

- `Boolean m_isScrollHorizontal`


## Methods

- `Void _InitIfNot()`

- `Void _OnValueChanged(Vector2)`

- `Void _UpdateDecoState(Vector2)`

- `Void _OnContentLayoutRebuilt()`

- `Void Start()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class FadeInDecoIfScrollEnd : MonoBehaviour, IHotfixable
{
	private DecoInfo _topDecoInfo; // 0x18
	private DecoInfo _downDecoInfo; // 0x20
	private DecoInfo _leftDecoInfo; // 0x28
	private DecoInfo _rightDecoInfo; // 0x30
	private Boolean m_isInited; // 0x38
	private Wrapper m_scrollRect; // 0x40
	private Boolean m_isScrollVertical; // 0x48
	private Boolean m_isScrollHorizontal; // 0x49
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__UpdateDecoState; // 0x10
	private static DelegateBridge __Hotfix0__OnContentLayoutRebuilt; // 0x18
	private static DelegateBridge __Hotfix0_Start; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x21c39c8 VA: 0x75947db9c8
	private Void _InitIfNot() { }
	// RVA: 0x21c3cd0 VA: 0x75947dbcd0
	private Void _OnValueChanged(Vector2 size) { }
	// RVA: 0x21c3d5c VA: 0x75947dbd5c
	private Void _UpdateDecoState(Vector2 size) { }
	// RVA: 0x21c3f28 VA: 0x75947dbf28
	private Void _OnContentLayoutRebuilt() { }
	// RVA: 0x21c4004 VA: 0x75947dc004
	private Void Start() { }
	// RVA: 0x21c4098 VA: 0x75947dc098
	public Void .ctor() { }
}
```