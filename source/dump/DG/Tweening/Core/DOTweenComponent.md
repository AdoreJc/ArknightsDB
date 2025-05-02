# DOTweenComponent

**Namespace:** `DG.Tweening.Core`


## Fields

- `Int32 inspectorUpdater`

- `Single _unscaledTime`

- `Single _unscaledDeltaTime`

- `Boolean _paused`

- `Single _pausedTime`

- `Boolean _isQuitting`

- `Boolean _duplicateToDestroy`


## Methods

- `Void Awake()`

- `Void Start()`

- `Void Update()`

- `Void LateUpdate()`

- `Void FixedUpdate()`

- `Void OnDrawGizmos()`

- `Void OnDestroy()`

- `Void OnApplicationPause(Boolean)`

- `Void OnApplicationQuit()`

- `IDOTweenInit SetCapacity(Int32, Int32)`


## Dump
```C#
// Dll : DOTween.dll
// Namespace : DG.Tweening.Core
public class DOTweenComponent : MonoBehaviour, IDOTweenInit
{
	public Int32 inspectorUpdater; // 0x18
	private Single _unscaledTime; // 0x1c
	private Single _unscaledDeltaTime; // 0x20
	private Boolean _paused; // 0x24
	private Single _pausedTime; // 0x28
	private Boolean _isQuitting; // 0x2c
	private Boolean _duplicateToDestroy; // 0x2d


	// RVA: 0x4196810 VA: 0x75967ae810
	private Void Awake() { }
	// RVA: 0x4196a28 VA: 0x75967aea28
	private Void Start() { }
	// RVA: 0x4196b00 VA: 0x75967aeb00
	private Void Update() { }
	// RVA: 0x4196dec VA: 0x75967aedec
	private Void LateUpdate() { }
	// RVA: 0x4196f04 VA: 0x75967aef04
	private Void FixedUpdate() { }
	// RVA: 0x419707c VA: 0x75967af07c
	private Void OnDrawGizmos() { }
	// RVA: 0x41971bc VA: 0x75967af1bc
	private Void OnDestroy() { }
	// RVA: 0x4197624 VA: 0x75967af624
	public Void OnApplicationPause(Boolean pauseStatus) { }
	// RVA: 0x4197680 VA: 0x75967af680
	private Void OnApplicationQuit() { }
	// RVA: 0x41976e0 VA: 0x75967af6e0
	public IDOTweenInit SetCapacity(Int32 tweenersCapacity, Int32 sequencesCapacity) { }
	// RVA: 0x4197754 VA: 0x75967af754
	internal IEnumerator WaitForCompletion(Tween t) { }
	// RVA: 0x41977f0 VA: 0x75967af7f0
	internal IEnumerator WaitForRewind(Tween t) { }
	// RVA: 0x4197864 VA: 0x75967af864
	internal IEnumerator WaitForKill(Tween t) { }
	// RVA: 0x4197900 VA: 0x75967af900
	internal IEnumerator WaitForElapsedLoops(Tween t, Int32 elapsedLoops) { }
	// RVA: 0x41979ac VA: 0x75967af9ac
	internal IEnumerator WaitForPosition(Tween t, Single position) { }
	// RVA: 0x4197a58 VA: 0x75967afa58
	internal IEnumerator WaitForStart(Tween t) { }
	// RVA: 0x4197acc VA: 0x75967afacc
	internal static Void Create() { }
	// RVA: 0x4197c24 VA: 0x75967afc24
	internal static Void DestroyInstance() { }
	// RVA: 0x4197d28 VA: 0x75967afd28
	public Void .ctor() { }
}
```