# UIHeapLayout

**Namespace:** `Torappu.UI`


## Fields

- `Single _normalExpectation`

- `Single _normalVariance`

- `Single _positionNormalSize`

- `Single _rotationNormalSize`

- `Single _maxRotationAngle`

- `RectTransform m_rectTrans`


## Properties

- `RectTransform rectTrans`


## Methods

- `RectTransform get_rectTrans()`

- `Void ResetRandomLayout()`

- `Single GetNormalRandomFactor(Single)`

- `Void _RelayoutChildren()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIHeapLayout : LayoutGroup
{
	private Single _normalExpectation; // 0x58
	private Single _normalVariance; // 0x5c
	private Single _positionNormalSize; // 0x60
	private Single _rotationNormalSize; // 0x64
	private Single _maxRotationAngle; // 0x68
	private RectTransform m_rectTrans; // 0x70
	private ListDict`2 m_childrenInfo; // 0x78

	public RectTransform rectTrans { get; }

	// RVA: 0x220e0ac VA: 0x75948260ac
	public override Void CalculateLayoutInputVertical() { }
	// RVA: 0x220e0b0 VA: 0x75948260b0
	public override Void SetLayoutHorizontal() { }
	// RVA: 0x220e0b4 VA: 0x75948260b4
	public override Void SetLayoutVertical() { }
	// RVA: 0x220e0b8 VA: 0x75948260b8
	public RectTransform get_rectTrans() { }
	// RVA: 0x220e14c VA: 0x759482614c
	public Void ResetRandomLayout() { }
	// RVA: 0x220e538 VA: 0x7594826538
	protected override Void OnRectTransformDimensionsChange() { }
	// RVA: 0x220e554 VA: 0x7594826554
	protected override Void OnTransformChildrenChanged() { }
	// RVA: 0x220e570 VA: 0x7594826570
	protected virtual Vector2 GetPosition(RectTransform child, Int32 index) { }
	// RVA: 0x220e698 VA: 0x7594826698
	protected virtual Quaternion GetRotation(RectTransform child, Int32 index) { }
	// RVA: 0x220e650 VA: 0x7594826650
	protected Single GetNormalRandomFactor(Single normalSize) { }
	// RVA: 0x220e1b8 VA: 0x75948261b8
	private Void _RelayoutChildren() { }
	// RVA: 0x220e704 VA: 0x7594826704
	public Void .ctor() { }
}
```