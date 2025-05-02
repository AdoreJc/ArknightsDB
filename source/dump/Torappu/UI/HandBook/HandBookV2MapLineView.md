# HandBookV2MapLineView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Image _lineSprite`

- `Sprite _commonLine`

- `Sprite _spLine`


## Methods

- `Void Render(RectTransform, RectTransform, LineData)`

- `Void OnShow()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2MapLineView : MonoBehaviour, IHotfixable
{
	private Image _lineSprite; // 0x18
	private Sprite _commonLine; // 0x20
	private Sprite _spLine; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnShow; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2eccd54 VA: 0x75954e4d54
	public Void Render(RectTransform trans1, RectTransform trans2, LineData lineData) { }
	// RVA: 0x2ecd0c8 VA: 0x75954e50c8
	public Void OnShow() { }
	// RVA: 0x2ed6878 VA: 0x75954ee878
	public Void .ctor() { }
}
```