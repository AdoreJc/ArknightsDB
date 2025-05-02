# MissionProgressBar

**Namespace:** `Torappu.UI.Mission`


## Fields

- `RectTransform _rectTransform`

- `Text _valueText`

- `Single _fullLength`

- `Single _height`

- `Int32 m_currentTarget`

- `Int32 m_currentValue`


## Properties

- `Single fullLength`


## Methods

- `Single get_fullLength()`

- `Void set_fullLength(Single)`

- `Void _RefreshLength()`

- `Void InitData(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class MissionProgressBar : MonoBehaviour
{
	private RectTransform _rectTransform; // 0x18
	private Text _valueText; // 0x20
	private Single _fullLength; // 0x28
	private Single _height; // 0x2c
	private Int32 m_currentTarget; // 0x30
	private Int32 m_currentValue; // 0x34

	public Single fullLength { get; set; }

	// RVA: 0x2743838 VA: 0x7594d5b838
	public Single get_fullLength() { }
	// RVA: 0x2743840 VA: 0x7594d5b840
	public Void set_fullLength(Single value) { }
	// RVA: 0x2743848 VA: 0x7594d5b848
	private Void _RefreshLength() { }
	// RVA: 0x2742c0c VA: 0x7594d5ac0c
	public Void InitData(Int32 target, Int32 value) { }
	// RVA: 0x2743888 VA: 0x7594d5b888
	public Void .ctor() { }
}
```