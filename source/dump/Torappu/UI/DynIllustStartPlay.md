# DynIllustStartPlay

**Namespace:** `Torappu.UI`


## Fields

- `DynIllustStartParams _params`

- `CameraSettings _mainCamera`

- `PeriodicTimer m_playingTimer`


## Properties

- `Boolean isPlaying`

- `DynIllustStartParams param`


## Methods

- `Boolean get_isPlaying()`

- `DynIllustStartParams get_param()`

- `Void Play()`

- `Void Stop()`

- `Boolean TryFetchAndAddCameras(List`1)`

- `Void CopyManualParam(DynIllustStartPlay)`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class DynIllustStartPlay : MonoBehaviour, IHotfixable
{
	public const Single DEFAULT_START_PLAY_DURATION; // 0x0
	public const Single DEFAULT_CHAR_VOICE_OFFSET; // 0x0
	public const Single MAIN_CAMERA_DEPTH; // 0x0
	public const Single MAX_CAMERA_FAR_PLANE; // 0x0
	private DynIllustStartParams _params; // 0x18
	private CameraSettings _mainCamera; // 0x30
	private List`1 _exCameras; // 0x38
	private List`1 _effects; // 0x40
	private PeriodicTimer m_playingTimer; // 0x48
	private static DelegateBridge __Hotfix0_get_isPlaying; // 0x0
	private static DelegateBridge __Hotfix0_get_param; // 0x8
	private static DelegateBridge __Hotfix0_Play; // 0x10
	private static DelegateBridge __Hotfix0_Stop; // 0x18
	private static DelegateBridge __Hotfix0_TryFetchAndAddCameras; // 0x20
	private static DelegateBridge __Hotfix0_CopyManualParam; // 0x28
	private static DelegateBridge __Hotfix0_Update; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean isPlaying { get; }
	public DynIllustStartParams param { get; }

	// RVA: 0x2117350 VA: 0x759472f350
	public Boolean get_isPlaying() { }
	// RVA: 0x21170a0 VA: 0x759472f0a0
	public DynIllustStartParams get_param() { }
	// RVA: 0x2117130 VA: 0x759472f130
	public Void Play() { }
	// RVA: 0x21173f0 VA: 0x759472f3f0
	public Void Stop() { }
	// RVA: 0x2114990 VA: 0x759472c990
	public Boolean TryFetchAndAddCameras(List`1 cameras) { }
	// RVA: 0x2117508 VA: 0x759472f508
	public Void CopyManualParam(DynIllustStartPlay src) { }
	// RVA: 0x2117598 VA: 0x759472f598
	private Void Update() { }
	// RVA: 0x211767c VA: 0x759472f67c
	public Void .ctor() { }
}
```