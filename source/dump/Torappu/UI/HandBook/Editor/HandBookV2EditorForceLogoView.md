# HandBookV2EditorForceLogoView

**Namespace:** `Torappu.UI.HandBook.Editor`


## Fields

- `Image _imgLogo`

- `GameObject _borderGo`

- `CanvasGroup _canvasGroup`

- `HandBookV2ForceData m_forceData`

- `Vector2 m_startPos`


## Methods

- `Void SetRaycast(Boolean)`

- `Void SetSelect(Boolean)`

- `Void Render(HandBookV2ForceData)`

- `Void OnBeginMove()`

- `Void OnMove(Vector2)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook.Editor
public class HandBookV2EditorForceLogoView : MonoBehaviour
{
	private Image _imgLogo; // 0x18
	private GameObject _borderGo; // 0x20
	private CanvasGroup _canvasGroup; // 0x28
	private HandBookV2ForceData m_forceData; // 0x30
	private Vector2 m_startPos; // 0x38


	// RVA: 0x2ee3610 VA: 0x75954fb610
	public Void SetRaycast(Boolean canRaycast) { }
	// RVA: 0x2ee3630 VA: 0x75954fb630
	public Void SetSelect(Boolean isSelected) { }
	// RVA: 0x2ee3640 VA: 0x75954fb640
	public Void Render(HandBookV2ForceData forceData) { }
	// RVA: 0x2ee3790 VA: 0x75954fb790
	public Void OnBeginMove() { }
	// RVA: 0x2ee3838 VA: 0x75954fb838
	public Void OnMove(Vector2 delta) { }
	// RVA: 0x2ee3900 VA: 0x75954fb900
	public Void OnClick() { }
	// RVA: 0x2ee3994 VA: 0x75954fb994
	public Void .ctor() { }
}
```