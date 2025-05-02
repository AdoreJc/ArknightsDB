# HandBookV2EditorForcePointView

**Namespace:** `Torappu.UI.HandBook.Editor`


## Fields

- `HandBookV2AlphaHexagonView _hexView`

- `Material _bgMat`

- `HandBookV2PointData m_pointData`


## Properties

- `HandBookV2PointData pointData`


## Methods

- `HandBookV2PointData get_pointData()`

- `Void Render(HandBookV2PointData, String)`

- `Void UpdateColor(Color)`

- `Void ToggleHexStyle(Boolean)`

- `Boolean IsInRange(Vector2, out)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook.Editor
public class HandBookV2EditorForcePointView : MonoBehaviour
{
	private HandBookV2AlphaHexagonView _hexView; // 0x18
	private Material _bgMat; // 0x20
	private HandBookV2PointData m_pointData; // 0x28

	public HandBookV2PointData pointData { get; }

	// RVA: 0x2ee399c VA: 0x75954fb99c
	public HandBookV2PointData get_pointData() { }
	// RVA: 0x2ee17b4 VA: 0x75954f97b4
	public Void Render(HandBookV2PointData pointData, String htmlColor) { }
	// RVA: 0x2ee152c VA: 0x75954f952c
	public Void UpdateColor(Color color) { }
	// RVA: 0x2ee2124 VA: 0x75954fa124
	public Void ToggleHexStyle(Boolean isSolid) { }
	// RVA: 0x2ee1220 VA: 0x75954f9220
	public Boolean IsInRange(Vector2 pos, out Int32 pointIndex) { }
	// RVA: 0x2ee39a4 VA: 0x75954fb9a4
	public Void OnClick() { }
	// RVA: 0x2ee3ac0 VA: 0x75954fbac0
	public Void .ctor() { }
}
```