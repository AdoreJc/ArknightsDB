# HandBookForceLogoEdit

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Text _forceID`

- `ForceData m_forceData`


## Methods

- `Void AddForceDirection()`

- `Void ChangeForceDirection()`

- `Void Render(ForceData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookForceLogoEdit : HandBookGroupCommonPosEdit
{
	private Text _forceID; // 0x28
	private List`1 _directionLogo; // 0x30
	private ForceData m_forceData; // 0x38


	// RVA: 0x2ec0eac VA: 0x75954d8eac
	public override Void ApplyPos(Vector3 vect) { }
	// RVA: 0x2ec0ecc VA: 0x75954d8ecc
	public Void AddForceDirection() { }
	// RVA: 0x2ec0f0c VA: 0x75954d8f0c
	public Void ChangeForceDirection() { }
	// RVA: 0x2ec0f90 VA: 0x75954d8f90
	public Void Render(ForceData forceData) { }
	// RVA: 0x2ec1004 VA: 0x75954d9004
	public Void .ctor() { }
}
```