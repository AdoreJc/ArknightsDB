# UIDynIllustEditorView

**Namespace:** `Torappu.UI.Test`


## Fields

- `Transform _battleView`

- `Transform _charInfoView`

- `Transform _skinView`

- `Camera m_cam`

- `RenderTexture m_rt`

- `Material m_mat`

- `Boolean _attached`

- `Int32 _skinIdx`


## Methods

- `Void Awake()`

- `Void Update()`

- `Void _InitDisplay()`

- `DynIllustView _CreateIllustView(DynIllust, Transform)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Test
public class UIDynIllustEditorView : MonoBehaviour
{
	private Transform _battleView; // 0x18
	private Transform _charInfoView; // 0x20
	private Transform _skinView; // 0x28
	private Camera m_cam; // 0x30
	private RenderTexture m_rt; // 0x38
	private Material m_mat; // 0x40
	private Boolean _attached; // 0x48
	private List`1 _views; // 0x50
	private Int32 _skinIdx; // 0x58


	// RVA: 0x2c5c668 VA: 0x7595274668
	private Void Awake() { }
	// RVA: 0x2c5c6fc VA: 0x75952746fc
	public Void Update() { }
	// RVA: 0x2c5cccc VA: 0x7595274ccc
	private Void _InitDisplay() { }
	// RVA: 0x2c5cb98 VA: 0x7595274b98
	private DynIllustView _CreateIllustView(DynIllust res, Transform parent) { }
	// RVA: 0x2c5ce6c VA: 0x7595274e6c
	public Void .ctor() { }
}
```