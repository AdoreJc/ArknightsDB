# UICustomAnchor

**Namespace:** `Torappu.UI`


## Fields

- `UpdateType updateType`

- `TargetType targetType`

- `RectTransform leftTarget`

- `TargetDirection leftTargetDirection`

- `Single leftMargin`

- `RectTransform rightTarget`

- `TargetDirection rightTargetDirection`

- `Single rightMargin`

- `RectTransform topTarget`

- `TargetDirection topTargetDirection`

- `Single topMargin`

- `RectTransform bottomTarget`

- `TargetDirection bottomTargetDirection`

- `Single bottomMargin`


## Methods

- `Void Refresh()`

- `Void _AdjustSize()`

- `Single _GetAdjustedPos(RectTransform, TargetDirection, TargetDirection, Single)`

- `Void OnEnable()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICustomAnchor : MonoBehaviour
{
	public UpdateType updateType; // 0x18
	public TargetType targetType; // 0x1c
	public RectTransform leftTarget; // 0x20
	public TargetDirection leftTargetDirection; // 0x28
	public Single leftMargin; // 0x2c
	public RectTransform rightTarget; // 0x30
	public TargetDirection rightTargetDirection; // 0x38
	public Single rightMargin; // 0x3c
	public RectTransform topTarget; // 0x40
	public TargetDirection topTargetDirection; // 0x48
	public Single topMargin; // 0x4c
	public RectTransform bottomTarget; // 0x50
	public TargetDirection bottomTargetDirection; // 0x58
	public Single bottomMargin; // 0x5c


	// RVA: 0x21d3cf4 VA: 0x75947ebcf4
	public Void Refresh() { }
	// RVA: 0x21d3cf8 VA: 0x75947ebcf8
	private Void _AdjustSize() { }
	// RVA: 0x21d3f7c VA: 0x75947ebf7c
	private Single _GetAdjustedPos(RectTransform targetTransform, TargetDirection targetDirection, TargetDirection currentDirection, Single margin) { }
	// RVA: 0x21d4188 VA: 0x75947ec188
	private Void OnEnable() { }
	// RVA: 0x21d4198 VA: 0x75947ec198
	private Void Update() { }
	// RVA: 0x21d41ac VA: 0x75947ec1ac
	public Void .ctor() { }
}
```