# UIColorGroupSetter

**Namespace:** `Torappu.UI`


## Fields

- `String m_currentColorSign`


## Methods

- `Void RebuildGroupInfo()`

- `Void MixColor(Color, Single)`

- `Void SetColor(Color)`

- `Void RecoverColor()`

- `Void _InitIfNot()`

- `Void _InitInfoRecursively(Transform)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIColorGroupSetter : MonoBehaviour
{
	private ListDict`2 m_colorDict; // 0x18
	private String m_currentColorSign; // 0x20


	// RVA: 0x2242b64 VA: 0x759485ab64
	public Void RebuildGroupInfo() { }
	// RVA: 0x2242c8c VA: 0x759485ac8c
	public Void MixColor(Color mixColor, Single weight) { }
	// RVA: 0x224300c VA: 0x759485b00c
	public Void SetColor(Color targetColor) { }
	// RVA: 0x22431c0 VA: 0x759485b1c0
	public Void RecoverColor() { }
	// RVA: 0x2242be0 VA: 0x759485abe0
	private Void _InitIfNot() { }
	// RVA: 0x22432c4 VA: 0x759485b2c4
	private Void _InitInfoRecursively(Transform root) { }
	// RVA: 0x22434e0 VA: 0x759485b4e0
	public Void .ctor() { }
}
```