# HandBookV2EditorForceView

**Namespace:** `Torappu.UI.HandBook.Editor`


## Fields

- `HandBookV2EditorForceBgView _bgView`

- `HandBookV2EditorForceLogoView _logoView`

- `HandBookV2ForceData <forceData>k__BackingField`

- `Vector2 m_startPos`


## Properties

- `HandBookV2ForceData forceData`

- `Int32 currentPointCount`

- `String editColor`

- `Vector2 bgPos`

- `Vector2 logoPos`

- `Single logoScale`


## Methods

- `HandBookV2ForceData get_forceData()`

- `Void set_forceData(HandBookV2ForceData)`

- `Int32 get_currentPointCount()`

- `String get_editColor()`

- `Void Render(HandBookV2ForceData, Boolean)`

- `Void _RenderLogo(HandBookV2ForceData)`

- `Void _RenderBg(HandBookV2ForceData)`

- `Void UpdateColor(Nullable`1)`

- `Void SetLogoRaycast(Boolean)`

- `Void SetBgRaycast(Boolean)`

- `Void SetSelectLogo(Boolean)`

- `Void SetSelectBg(Boolean)`

- `Void ToggleBgStyle(Boolean)`

- `Void TogglePointBgStyle(Int32, Boolean)`

- `Boolean IsInRange(Vector2, out, out)`

- `Void RemovePoint(Int32)`

- `Void AddPoint(Vector2)`

- `Boolean IsAdjacent(Vector2, out)`

- `Void SavePointList(List`1)`

- `Vector2 get_bgPos()`

- `Void set_bgPos(Vector2)`

- `Vector2 get_logoPos()`

- `Void set_logoPos(Vector2)`

- `Single get_logoScale()`

- `Void set_logoScale(Single)`

- `Void OnBeginMove()`

- `Void OnMove(Vector2)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook.Editor
public class HandBookV2EditorForceView : MonoBehaviour
{
	private HandBookV2EditorForceBgView _bgView; // 0x18
	private HandBookV2EditorForceLogoView _logoView; // 0x20
	private HandBookV2ForceData <forceData>k__BackingField; // 0x28
	private Vector2 m_startPos; // 0x30

	public HandBookV2ForceData forceData { get; set; }
	public Int32 currentPointCount { get; }
	public String editColor { get; }
	public Vector2 bgPos { get; set; }
	public Vector2 logoPos { get; set; }
	public Single logoScale { get; set; }

	// RVA: 0x2ee3ac8 VA: 0x75954fbac8
	public HandBookV2ForceData get_forceData() { }
	// RVA: 0x2ee3ad0 VA: 0x75954fbad0
	private Void set_forceData(HandBookV2ForceData value) { }
	// RVA: 0x2ee3ad8 VA: 0x75954fbad8
	public Int32 get_currentPointCount() { }
	// RVA: 0x2ee3af0 VA: 0x75954fbaf0
	public String get_editColor() { }
	// RVA: 0x2ee3b08 VA: 0x75954fbb08
	public Void Render(HandBookV2ForceData data, Boolean isTemp) { }
	// RVA: 0x2ee3c08 VA: 0x75954fbc08
	private Void _RenderLogo(HandBookV2ForceData forceData) { }
	// RVA: 0x2ee3bf0 VA: 0x75954fbbf0
	private Void _RenderBg(HandBookV2ForceData forceData) { }
	// RVA: 0x2ee3c20 VA: 0x75954fbc20
	public Void UpdateColor(Nullable`1 color) { }
	// RVA: 0x2ee3c60 VA: 0x75954fbc60
	public Void SetLogoRaycast(Boolean canRaycast) { }
	// RVA: 0x2ee3c88 VA: 0x75954fbc88
	public Void SetBgRaycast(Boolean canRaycast) { }
	// RVA: 0x2ee3cb0 VA: 0x75954fbcb0
	public Void SetSelectLogo(Boolean isSelected) { }
	// RVA: 0x2ee3cd4 VA: 0x75954fbcd4
	public Void SetSelectBg(Boolean isSelected) { }
	// RVA: 0x2ee3cf0 VA: 0x75954fbcf0
	public Void ToggleBgStyle(Boolean isSolid) { }
	// RVA: 0x2ee3d0c VA: 0x75954fbd0c
	public Void TogglePointBgStyle(Int32 pointIdx, Boolean isSolid) { }
	// RVA: 0x2ee3d28 VA: 0x75954fbd28
	public Boolean IsInRange(Vector2 pos, out Int32 forceIndex, out Int32 pointIndex) { }
	// RVA: 0x2ee3d40 VA: 0x75954fbd40
	public Void RemovePoint(Int32 pointIndex) { }
	// RVA: 0x2ee3d58 VA: 0x75954fbd58
	public Void AddPoint(Vector2 position) { }
	// RVA: 0x2ee3d70 VA: 0x75954fbd70
	public Boolean IsAdjacent(Vector2 localPosition, out Vector2 precisePos) { }
	// RVA: 0x2ee3d88 VA: 0x75954fbd88
	public Void SavePointList(List`1 pointList) { }
	// RVA: 0x2ee3da0 VA: 0x75954fbda0
	public Vector2 get_bgPos() { }
	// RVA: 0x2ee3dc0 VA: 0x75954fbdc0
	public Void set_bgPos(Vector2 value) { }
	// RVA: 0x2ee3df8 VA: 0x75954fbdf8
	public Vector2 get_logoPos() { }
	// RVA: 0x2ee3e1c VA: 0x75954fbe1c
	public Void set_logoPos(Vector2 value) { }
	// RVA: 0x2ee3e58 VA: 0x75954fbe58
	public Single get_logoScale() { }
	// RVA: 0x2ee3e7c VA: 0x75954fbe7c
	public Void set_logoScale(Single value) { }
	// RVA: 0x2ee3eb8 VA: 0x75954fbeb8
	public Void OnBeginMove() { }
	// RVA: 0x2ee3f50 VA: 0x75954fbf50
	public Void OnMove(Vector2 delta) { }
	// RVA: 0x2ee4178 VA: 0x75954fc178
	public Void OnClick() { }
	// RVA: 0x2ee4234 VA: 0x75954fc234
	public Void .ctor() { }
}
```