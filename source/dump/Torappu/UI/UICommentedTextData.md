# UICommentedTextData

**Namespace:** `Torappu.UI`


## Fields

- `String id`

- `InfoType type`

- `String populateText`

- `Int32 size`

- `Boolean valid`

- `Int32 m_startIndex`

- `Int32 m_length`


## Methods

- `Void SetStartIndex(Int32, Int32)`

- `Int32 GetStartIndex()`

- `Int32 GetEndIndex()`

- `Void SetValid(Boolean)`

- `Void AddBound(Vector4)`

- `Void ClearBound()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICommentedTextData
{
	public String id; // 0x10
	public InfoType type; // 0x18
	public String populateText; // 0x20
	public Int32 size; // 0x28
	public Boolean valid; // 0x2c
	private Int32 m_startIndex; // 0x30
	private Int32 m_length; // 0x34
	private List`1 m_boundList; // 0x38

	public List`1 BoundList { get; }

	// RVA: 0x2245f84 VA: 0x759485df84
	public List`1 get_BoundList() { }
	// RVA: 0x2245f8c VA: 0x759485df8c
	public Void .ctor(String content, InfoType infoType, String infoId) { }
	// RVA: 0x2245fe4 VA: 0x759485dfe4
	public Void SetStartIndex(Int32 index, Int32 length) { }
	// RVA: 0x2245fec VA: 0x759485dfec
	public Int32 GetStartIndex() { }
	// RVA: 0x2244c84 VA: 0x759485cc84
	public Int32 GetEndIndex() { }
	// RVA: 0x2245ff4 VA: 0x759485dff4
	public Void SetValid(Boolean valid) { }
	// RVA: 0x2244b50 VA: 0x759485cb50
	public Void AddBound(Vector4 bound) { }
	// RVA: 0x2244984 VA: 0x759485c984
	public Void ClearBound() { }
}
```