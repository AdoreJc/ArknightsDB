# PerformanceTest

**Namespace:** `Torappu.Grading`


## Fields

- `Material _mat`

- `Vector2 _buttomLeft`

- `Vector2 _buttomRight`

- `Vector2 _topLeft`

- `Vector2 _topRight`

- `Int32 _sampleCount`

- `Int32 _drawCountPerFrame`

- `Single _standerdScore`

- `Single _maxRenderTime`

- `PerformanceTestState m_state`

- `Int32 m_frameCount`

- `Single m_totalDrawMilliseconds`

- `Single m_startTimestemp`

- `Single m_width`

- `Single m_height`

- `Action m_onTestComplete`

- `DeviceLevel <deviceLevel>k__BackingField`


## Properties

- `DeviceLevel deviceLevel`


## Methods

- `DeviceLevel get_deviceLevel()`

- `Void set_deviceLevel(DeviceLevel)`

- `Void Start()`

- `Void OnPostRender()`

- `Void _Draw(Single, Single, Single, Single, Single, Single, Single, Single)`

- `Void _DrawQuads()`

- `Void _CalculateLevel()`

- `Void StartTest(Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Grading
public class PerformanceTest : MonoBehaviour
{
	private Material _mat; // 0x18
	private Vector2 _buttomLeft; // 0x20
	private Vector2 _buttomRight; // 0x28
	private Vector2 _topLeft; // 0x30
	private Vector2 _topRight; // 0x38
	private Int32 _sampleCount; // 0x40
	private Int32 _drawCountPerFrame; // 0x44
	private Single _standerdScore; // 0x48
	private Single _maxRenderTime; // 0x4c
	private PerformanceTestState m_state; // 0x50
	private Int32 m_frameCount; // 0x54
	private Single m_totalDrawMilliseconds; // 0x58
	private Single m_startTimestemp; // 0x5c
	private List`1 m_scoreList; // 0x60
	private Single m_width; // 0x68
	private Single m_height; // 0x6c
	private Action m_onTestComplete; // 0x70
	private DeviceLevel <deviceLevel>k__BackingField; // 0x78

	public DeviceLevel deviceLevel { get; set; }

	// RVA: 0x35c4e2c VA: 0x7595bdce2c
	public DeviceLevel get_deviceLevel() { }
	// RVA: 0x35c4e34 VA: 0x7595bdce34
	private Void set_deviceLevel(DeviceLevel value) { }
	// RVA: 0x35c4e3c VA: 0x7595bdce3c
	private Void Start() { }
	// RVA: 0x35c4e58 VA: 0x7595bdce58
	private Void OnPostRender() { }
	// RVA: 0x35c51a0 VA: 0x7595bdd1a0
	private Void _Draw(Single x1, Single y1, Single x2, Single y2, Single x3, Single y3, Single x4, Single y4) { }
	// RVA: 0x35c5040 VA: 0x7595bdd040
	private Void _DrawQuads() { }
	// RVA: 0x35c5054 VA: 0x7595bdd054
	private Void _CalculateLevel() { }
	// RVA: 0x35c52d4 VA: 0x7595bdd2d4
	public Void StartTest(Action onTestComplete) { }
	// RVA: 0x35c5314 VA: 0x7595bdd314
	public Void .ctor() { }
}
```