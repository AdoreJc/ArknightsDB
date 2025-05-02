# UIChildrenColorGraphic

**Namespace:** `Torappu.UI`


## Methods

- `Boolean _IsExcept(Graphic)`

- `Void ForceRefreshChildren()`

- `Void CrossFadeColor(Color, Single, Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIChildrenColorGraphic : MonoBehaviour
{
	private Graphic[] _exceptGraphics; // 0x18
	private Graphic[] m_allGraphics; // 0x20

	private Graphic[] allGraphics { get; }

	// RVA: 0x21d1674 VA: 0x75947e9674
	private Graphic[] get_allGraphics() { }
	// RVA: 0x21d16ec VA: 0x75947e96ec
	private Boolean _IsExcept(Graphic graphic) { }
	// RVA: 0x21d1750 VA: 0x75947e9750
	public Void ForceRefreshChildren() { }
	// RVA: 0x21d175c VA: 0x75947e975c
	public Void CrossFadeColor(Color targetColor, Single duration, Boolean ignoreTimeScale, Boolean useAlpha) { }
	// RVA: 0x21d18cc VA: 0x75947e98cc
	public Void .ctor() { }
}
```