# AVGCameraEffect

**Namespace:** `Torappu.AVG`


## Fields

- `Camera _sceneCamera`

- `RectTransform _sceneRoot`

- `Single _defaultFadetime`


## Methods

- `CameraEffectRecord _EnsureCameraEffectRecord(String)`

- `Void _ClearEffects()`

- `Void _ClearEffect(String)`

- `Boolean _ExecuteCameraEffect(Command)`

- `Boolean _ExecuteFocusout(Command)`

- `EffectConfig _GenCfgByType(String, String)`

- `Void _ResetCameraLocation()`

- `Boolean _ExecuteCameraShake(Command)`

- `Single CalculateFadetime(Single)`

- `Boolean NeedSkipAnimation(Single)`

- `Tweener _TweenGrayscaleAmount(String, Single, Single, Single)`

- `Void _EnableColorInverse(Boolean)`

- `Void <>xLuaBaseProxy_OnReset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGCameraEffect : ExecutorComponent, IFadeTimeRatio
{
	private Camera _sceneCamera; // 0x50
	private RectTransform _sceneRoot; // 0x58
	private Single _defaultFadetime; // 0x60
	private const String FOCUSOUT_KEY_CHAR; // 0x0
	private const String FOCUSOUT_KEY_CG; // 0x0
	private const String FOCUSOUT_KEY_BG; // 0x0
	private const String FOCUSOUT_KEY_CGITEM; // 0x0
	private const String FOCUSOUT_KEY_LARGE_BG; // 0x0
	private const String FX_KEY_GRAYSCALE; // 0x0
	private const String FX_KEY_COLORINVERSE; // 0x0
	private Dictionary`2 m_usedEffects; // 0x68
	private static DelegateBridge __Hotfix0__EnsureCameraEffectRecord; // 0x0
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x8
	private static DelegateBridge __Hotfix0_OnReset; // 0x10
	private static DelegateBridge __Hotfix0__ClearEffects; // 0x18
	private static DelegateBridge __Hotfix0__ClearEffect; // 0x20
	private static DelegateBridge __Hotfix0__ExecuteCameraEffect; // 0x28
	private static DelegateBridge __Hotfix0__ExecuteFocusout; // 0x30
	private static DelegateBridge __Hotfix0__GenCfgByType; // 0x38
	private static DelegateBridge __Hotfix0__ResetCameraLocation; // 0x40
	private static DelegateBridge __Hotfix0__ExecuteCameraShake; // 0x48
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x50
	private static DelegateBridge __Hotfix0_CalculateFadetime; // 0x58
	private static DelegateBridge __Hotfix0_NeedSkipAnimation; // 0x60
	private static DelegateBridge __Hotfix0__TweenGrayscaleAmount; // 0x68
	private static DelegateBridge __Hotfix0__EnableColorInverse; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x3e639e0 VA: 0x759647b9e0
	private CameraEffectRecord _EnsureCameraEffectRecord(String effect) { }
	// RVA: 0x3e63be8 VA: 0x759647bbe8
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e63ddc VA: 0x759647bddc
	public override Void OnReset() { }
	// RVA: 0x3e63f5c VA: 0x759647bf5c
	private Void _ClearEffects() { }
	// RVA: 0x3e6420c VA: 0x759647c20c
	private Void _ClearEffect(String effect) { }
	// RVA: 0x3e6430c VA: 0x759647c30c
	private Boolean _ExecuteCameraEffect(Command command) { }
	// RVA: 0x3e64ac8 VA: 0x759647cac8
	private Boolean _ExecuteFocusout(Command command) { }
	// RVA: 0x3e64df4 VA: 0x759647cdf4
	private EffectConfig _GenCfgByType(String type, String id) { }
	// RVA: 0x3e63e64 VA: 0x759647be64
	private Void _ResetCameraLocation() { }
	// RVA: 0x3e654fc VA: 0x759647d4fc
	private Boolean _ExecuteCameraShake(Command command) { }
	// RVA: 0x3e65a10 VA: 0x759647da10
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e658c4 VA: 0x759647d8c4
	public Single CalculateFadetime(Single initialFadetime) { }
	// RVA: 0x3e6596c VA: 0x759647d96c
	public Boolean NeedSkipAnimation(Single fadetime) { }
	// RVA: 0x3e64694 VA: 0x759647c694
	private Tweener _TweenGrayscaleAmount(String effect, Single initAmount, Single amount, Single fadetime) { }
	// RVA: 0x3e6491c VA: 0x759647c91c
	private Void _EnableColorInverse(Boolean enable) { }
	// RVA: 0x3e65ac8 VA: 0x759647dac8
	public Void .ctor() { }
	// RVA: 0x3e65b94 VA: 0x759647db94
	private Void <>xLuaBaseProxy_OnReset() { }
}
```