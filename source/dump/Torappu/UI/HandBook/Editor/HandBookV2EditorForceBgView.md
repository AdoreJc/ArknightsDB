# HandBookV2EditorForceBgView

**Namespace:** `Torappu.UI.HandBook.Editor`


## Fields

- `HandBookV2EditorForcePointView _pointTemplate`

- `CanvasGroup _canvasGroup`

- `HandBookV2ForceData m_forceData`


## Properties

- `String editColor`

- `Int32 currentPointCount`


## Methods

- `String get_editColor()`

- `Int32 GetMaxPointIndex()`

- `Int32 get_currentPointCount()`

- `Void SetRaycast(Boolean)`

- `Boolean IsInRange(Vector2, out, out)`

- `Void UpdateColor(Nullable`1)`

- `Void _ClearColor()`

- `Void _UpdateColor()`

- `Void Render(HandBookV2ForceData)`

- `Void SavePointList(List`1)`

- `Void ToggleBgStyle(Boolean)`

- `Void TogglePointBgStyle(Int32, Boolean)`

- `Void RemovePoint(Int32)`

- `Void AddPoint(Vector2)`

- `Boolean IsAdjacent(Vector2, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook.Editor
public class HandBookV2EditorForceBgView : MonoBehaviour
{
	private HandBookV2EditorForcePointView _pointTemplate; // 0x18
	private CanvasGroup _canvasGroup; // 0x20
	private Dictionary`2 m_pointViewMap; // 0x28
	private HandBookV2ForceData m_forceData; // 0x30
	private Nullable`1 m_editColor; // 0x38

	public String editColor { get; }
	public Int32 currentPointCount { get; }

	// RVA: 0x2ee0e1c VA: 0x75954f8e1c
	public String get_editColor() { }
	// RVA: 0x2ee0e9c VA: 0x75954f8e9c
	private Int32 GetMaxPointIndex() { }
	// RVA: 0x2ee0ff0 VA: 0x75954f8ff0
	public Int32 get_currentPointCount() { }
	// RVA: 0x2ee1040 VA: 0x75954f9040
	public Void SetRaycast(Boolean canRaycast) { }
	// RVA: 0x2ee1060 VA: 0x75954f9060
	public Boolean IsInRange(Vector2 pos, out Int32 forceIndex, out Int32 pointIndex) { }
	// RVA: 0x2ee1270 VA: 0x75954f9270
	public Void UpdateColor(Nullable`1 color) { }
	// RVA: 0x2ee1480 VA: 0x75954f9480
	private Void _ClearColor() { }
	// RVA: 0x2ee1284 VA: 0x75954f9284
	private Void _UpdateColor() { }
	// RVA: 0x2ee1560 VA: 0x75954f9560
	public Void Render(HandBookV2ForceData forceData) { }
	// RVA: 0x2ee185c VA: 0x75954f985c
	public Void SavePointList(List`1 pointList) { }
	// RVA: 0x2ee1f9c VA: 0x75954f9f9c
	public Void ToggleBgStyle(Boolean isSolid) { }
	// RVA: 0x2ee2160 VA: 0x75954fa160
	public Void TogglePointBgStyle(Int32 pointIndex, Boolean isSolid) { }
	// RVA: 0x2ee21f8 VA: 0x75954fa1f8
	public Void RemovePoint(Int32 pointIndex) { }
	// RVA: 0x2ee22bc VA: 0x75954fa2bc
	public Void AddPoint(Vector2 position) { }
	// RVA: 0x2ee2640 VA: 0x75954fa640
	public Boolean IsAdjacent(Vector2 roughPos, out Vector2 precisePos) { }
	// RVA: 0x2ee28ec VA: 0x75954fa8ec
	public Void .ctor() { }
}
```