# FxDelay

**Namespace:** `Torappu.Fx`


## Fields

- `Single _delayTime`

- `Single m_playbackSpeed`

- `Boolean m_isWaiting`


## Properties

- `Single playbackSpeed`


## Methods

- `Single get_playbackSpeed()`

- `Void set_playbackSpeed(Single)`

- `Void OnEnable()`

- `Void ForceToEnd()`

- `Void OnRecycle()`

- `Void _DelayFunc()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Fx
public class FxDelay : MonoBehaviour, IHotfixable
{
	private const String DELAY_FUNC; // 0x0
	private Single _delayTime; // 0x18
	private Single m_playbackSpeed; // 0x1c
	private Boolean m_isWaiting; // 0x20
	private static DelegateBridge __Hotfix0_get_playbackSpeed; // 0x0
	private static DelegateBridge __Hotfix0_set_playbackSpeed; // 0x8
	private static DelegateBridge __Hotfix0_OnEnable; // 0x10
	private static DelegateBridge __Hotfix0_ForceToEnd; // 0x18
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x20
	private static DelegateBridge __Hotfix0__DelayFunc; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Single playbackSpeed { get; set; }

	// RVA: 0x3efc710 VA: 0x7596514710
	public Single get_playbackSpeed() { }
	// RVA: 0x3efc778 VA: 0x7596514778
	public Void set_playbackSpeed(Single value) { }
	// RVA: 0x3efc7f4 VA: 0x75965147f4
	private Void OnEnable() { }
	// RVA: 0x3efc8bc VA: 0x75965148bc
	public Void ForceToEnd() { }
	// RVA: 0x3efc98c VA: 0x759651498c
	public Void OnRecycle() { }
	// RVA: 0x3efca2c VA: 0x7596514a2c
	private Void _DelayFunc() { }
	// RVA: 0x3efcabc VA: 0x7596514abc
	public Void .ctor() { }
}
```