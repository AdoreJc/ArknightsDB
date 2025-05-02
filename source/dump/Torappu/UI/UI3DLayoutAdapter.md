# UI3DLayoutAdapter

**Namespace:** `Torappu.UI`


## Fields

- `Vector2 _fromResolution`

- `Vector2 _toResolution`

- `FitMode _fitMode`

- `Vector2 _testResolution`


## Methods

- `Void Start()`

- `Void OnDestroy()`

- `Void OnSafeRectUpdated(SafeRect)`

- `Void _AdjustLayout(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UI3DLayoutAdapter : MonoBehaviour, ISafeAreaListener
{
	private UIVector3Lerp[] _targets; // 0x18
	private Vector2 _fromResolution; // 0x20
	private Vector2 _toResolution; // 0x28
	private FitMode _fitMode; // 0x30
	private Vector2 _testResolution; // 0x34


	// RVA: 0x21cb7bc VA: 0x75947e37bc
	private Void Start() { }
	// RVA: 0x21cb814 VA: 0x75947e3814
	private Void OnDestroy() { }
	// RVA: 0x21cb86c VA: 0x75947e386c
	public Void OnSafeRectUpdated(SafeRect rect) { }
	// RVA: 0x21cb8c8 VA: 0x75947e38c8
	private Void _AdjustLayout(Vector2 resolution) { }
	// RVA: 0x21cbadc VA: 0x75947e3adc
	public static Void CalcLayoutBoundaries(Boolean isForceUpdate) { }
	// RVA: 0x21cbbc8 VA: 0x75947e3bc8
	private static String _ConvertGraphicUtilName(String fieldName, String code1, String code2) { }
	// RVA: 0x21cbcd8 VA: 0x75947e3cd8
	public Void .ctor() { }
}
```