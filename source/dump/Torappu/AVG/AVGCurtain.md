# AVGCurtain

**Namespace:** `Torappu.AVG`


## Fields

- `RectTransform _curtainRect`

- `CanvasGroup _canvasGroup`

- `Image _curtainImg`

- `Image _gradientImg`

- `Vector2 _originSize`


## Properties

- `Single currentAlpha`

- `Color currentColor`

- `Vector2 currentSize`

- `Vector2 originSize`


## Methods

- `Single get_currentAlpha()`

- `Color get_currentColor()`

- `Vector2 get_currentSize()`

- `Vector2 get_originSize()`

- `Tween SetCurtainSizeTween(Vector2, Single, Boolean)`

- `Tween SetCurtainAlphaTween(Single, Single, Single)`

- `Void SetCurtainSize(Vector2, Boolean)`

- `Void SetCurtainAlpha(Single)`

- `Void ResetCurtain()`

- `Void HideCurtain(Single)`

- `Void RecycleCurtain()`

- `Void <HideCurtain>b__20_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGCurtain : MonoBehaviour, IHotfixable
{
	private RectTransform _curtainRect; // 0x18
	private CanvasGroup _canvasGroup; // 0x20
	private Image _curtainImg; // 0x28
	private Image _gradientImg; // 0x30
	private Vector2 _originSize; // 0x38
	private const Single DEFAULT_ALPHA; // 0x0
	private const Single ALPHA_ZERO; // 0x0
	private static DelegateBridge __Hotfix0_get_currentAlpha; // 0x0
	private static DelegateBridge __Hotfix0_get_currentColor; // 0x8
	private static DelegateBridge __Hotfix0_get_currentSize; // 0x10
	private static DelegateBridge __Hotfix0_get_originSize; // 0x18
	private static DelegateBridge __Hotfix0_SetCurtainSizeTween; // 0x20
	private static DelegateBridge __Hotfix0_SetCurtainAlphaTween; // 0x28
	private static DelegateBridge __Hotfix0_SetCurtainSize; // 0x30
	private static DelegateBridge __Hotfix0_SetCurtainAlpha; // 0x38
	private static DelegateBridge __Hotfix0_ResetCurtain; // 0x40
	private static DelegateBridge __Hotfix0_HideCurtain; // 0x48
	private static DelegateBridge __Hotfix0_RecycleCurtain; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Single currentAlpha { get; }
	public Color currentColor { get; }
	public Vector2 currentSize { get; }
	public Vector2 originSize { get; }

	// RVA: 0x3ea5140 VA: 0x75964bd140
	public Single get_currentAlpha() { }
	// RVA: 0x3ea51b4 VA: 0x75964bd1b4
	public Color get_currentColor() { }
	// RVA: 0x3ea5230 VA: 0x75964bd230
	public Vector2 get_currentSize() { }
	// RVA: 0x3ea52a4 VA: 0x75964bd2a4
	public Vector2 get_originSize() { }
	// RVA: 0x3ea5308 VA: 0x75964bd308
	public Tween SetCurtainSizeTween(Vector2 targetSize, Single fadetime, Boolean useGradient) { }
	// RVA: 0x3ea5404 VA: 0x75964bd404
	public Tween SetCurtainAlphaTween(Single afrom, Single ato, Single fadetime) { }
	// RVA: 0x3ea54fc VA: 0x75964bd4fc
	public Void SetCurtainSize(Vector2 targetSize, Boolean useGradient) { }
	// RVA: 0x3ea55e0 VA: 0x75964bd5e0
	public Void SetCurtainAlpha(Single targetAlpha) { }
	// RVA: 0x3ea566c VA: 0x75964bd66c
	public Void ResetCurtain() { }
	// RVA: 0x3ea573c VA: 0x75964bd73c
	public Void HideCurtain(Single fadetime) { }
	// RVA: 0x3ea58dc VA: 0x75964bd8dc
	public Void RecycleCurtain() { }
	// RVA: 0x3ea59f4 VA: 0x75964bd9f4
	public Void .ctor() { }
	// RVA: 0x3ea5a64 VA: 0x75964bda64
	private Void <HideCurtain>b__20_0() { }
}
```