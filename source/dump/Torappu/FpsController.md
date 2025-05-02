# FpsController

**Namespace:** `Torappu`


## Fields

- `Boolean _lockTargetFps`

- `Boolean _makeNeverSleep`

- `FpsMode _targetFpsMode`

- `Single _periodToProfile`

- `Int32 _fpsFontSize`

- `Color _fpsFontColor`

- `Rect _fpsRect`

- `Single m_fpsCountTime`

- `Int32 m_frameCnt`

- `Single m_lastFps`

- `Rect m_overdrawRect`

- `UISleepBlocker m_blocker`

- `Int32 m_originTargetFps`

- `Int32 m_originVSync`


## Properties

- `Boolean lockTargetFps`


## Methods

- `Boolean get_lockTargetFps()`

- `Void Start()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class FpsController : MonoBehaviour, IHotfixable
{
	private const Int32 MAX_TARGET_FPS; // 0x0
	public static readonly Int32[] TARGET_FPS_PER_MODE; // 0x0
	private Boolean _lockTargetFps; // 0x18
	private Boolean _makeNeverSleep; // 0x19
	private FpsMode _targetFpsMode; // 0x1c
	private Single _periodToProfile; // 0x20
	private Int32 _fpsFontSize; // 0x24
	private Color _fpsFontColor; // 0x28
	private Rect _fpsRect; // 0x38
	private Single m_fpsCountTime; // 0x48
	private Int32 m_frameCnt; // 0x4c
	private Single m_lastFps; // 0x50
	private Rect m_overdrawRect; // 0x54
	private UISleepBlocker m_blocker; // 0x68
	private Int32 m_originTargetFps; // 0x70
	private Int32 m_originVSync; // 0x74
	private static DelegateBridge __Hotfix0_get_lockTargetFps; // 0x8
	private static DelegateBridge __Hotfix0_Start; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean lockTargetFps { get; }

	// RVA: 0x311497c VA: 0x759572c97c
	public Boolean get_lockTargetFps() { }
	// RVA: 0x31149f4 VA: 0x759572c9f4
	private Void Start() { }
	// RVA: 0x3114d64 VA: 0x759572cd64
	private Void OnDestroy() { }
	// RVA: 0x3114eac VA: 0x759572ceac
	public Void .ctor() { }
	// RVA: 0x3114ff0 VA: 0x759572cff0
	private static Void .cctor() { }
}
```