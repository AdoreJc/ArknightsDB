# RecruitGachaCharButton

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `String _charId`

- `EvolvePhase _evolvePhase`

- `Int32 _level`

- `Int32 _skillIndex`

- `Int32 _skillLevel`


## Properties

- `String CharId`


## Methods

- `Void set_CharId(String)`

- `String get_CharId()`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitGachaCharButton : MonoBehaviour
{
	private String _charId; // 0x18
	private EvolvePhase _evolvePhase; // 0x20
	private Int32 _level; // 0x24
	private Int32 _skillIndex; // 0x28
	private Int32 _skillLevel; // 0x2c

	public String CharId { get; set; }

	// RVA: 0x2715798 VA: 0x7594d2d798
	public Void set_CharId(String value) { }
	// RVA: 0x27157a0 VA: 0x7594d2d7a0
	public String get_CharId() { }
	// RVA: 0x27157a8 VA: 0x7594d2d7a8
	public Void OnClick() { }
	// RVA: 0x27158b4 VA: 0x7594d2d8b4
	public Void .ctor() { }
}
```