# TempFPSComponent

**Namespace:** `Torappu.UI`


## Fields

- `Double _lastInterval`

- `Int32 _frames`

- `Single _fps`

- `Text m_text`


## Properties

- `Single FPS`


## Methods

- `Void Start()`

- `Void Update()`

- `Single get_FPS()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class TempFPSComponent : MonoBehaviour
{
	private const Single UPDATE_INTERVAL; // 0x0
	private Double _lastInterval; // 0x18
	private Int32 _frames; // 0x20
	private Single _fps; // 0x24
	private Text m_text; // 0x28

	public Single FPS { get; }

	// RVA: 0x21cd324 VA: 0x75947e5324
	private Void Start() { }
	// RVA: 0x21cd390 VA: 0x75947e5390
	private Void Update() { }
	// RVA: 0x21cd420 VA: 0x75947e5420
	public Single get_FPS() { }
	// RVA: 0x21cd428 VA: 0x75947e5428
	public Void .ctor() { }
}
```