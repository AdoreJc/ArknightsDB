# SpineOutline

**Namespace:** `Torappu`


## Fields

- `Shader _shader`

- `Single _outlineSize`

- `Color _outlineColor`

- `Boolean _useEightWays`

- `Material m_material`

- `MeshRenderer m_meshRenderer`

- `MeshFilter m_meshFilter`


## Methods

- `Void _Init()`

- `Void OnValidate()`

- `Void Start()`

- `Void LateUpdate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SpineOutline : MonoBehaviour
{
	private const String OUTLINE_SHADER_NAME; // 0x0
	private const Single OFFSET_Z; // 0x0
	private Shader _shader; // 0x18
	private Single _outlineSize; // 0x20
	private Color _outlineColor; // 0x24
	private Boolean _useEightWays; // 0x34
	private Material m_material; // 0x38
	private MeshRenderer m_meshRenderer; // 0x40
	private MeshFilter m_meshFilter; // 0x48


	// RVA: 0x31066f4 VA: 0x759571e6f4
	private Void _Init() { }
	// RVA: 0x3106928 VA: 0x759571e928
	private Void OnValidate() { }
	// RVA: 0x310692c VA: 0x759571e92c
	private Void Start() { }
	// RVA: 0x3106930 VA: 0x759571e930
	private Void LateUpdate() { }
	// RVA: 0x3106cd8 VA: 0x759571ecd8
	public Void .ctor() { }
}
```