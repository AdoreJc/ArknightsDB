# Behaviour

**Namespace:** ` `


## Fields

- `Effect <effect>k__BackingField`


## Properties

- `Effect effect`

- `SpawnLocation spawnLocation`

- `Boolean isPaused`

- `Boolean isFinished`


## Methods

- `Effect get_effect()`

- `Void set_effect(Effect)`

- `SpawnLocation get_spawnLocation()`

- `Boolean get_isPaused()`

- `Void set_isPaused(Boolean)`

- `Boolean get_isFinished()`

- `Void SetBehaviourPause(Boolean)`

- `Void FaceTo(Vector3)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Behaviour : MonoBehaviour, IHotfixable
{
	private Effect <effect>k__BackingField; // 0x18
	private static DelegateBridge __Hotfix0_get_effect; // 0x0
	private static DelegateBridge __Hotfix0_set_effect; // 0x8
	private static DelegateBridge __Hotfix0_get_owner; // 0x10
	private static DelegateBridge __Hotfix0_get_spawnLocation; // 0x18
	private static DelegateBridge __Hotfix0_get_isPaused; // 0x20
	private static DelegateBridge __Hotfix0_set_isPaused; // 0x28
	private static DelegateBridge __Hotfix0_get_isFinished; // 0x30
	private static DelegateBridge __Hotfix0_Init; // 0x38
	private static DelegateBridge __Hotfix0_OnPlay; // 0x40
	private static DelegateBridge __Hotfix0_OnFinish; // 0x48
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x50
	private static DelegateBridge __Hotfix0_OnPaused; // 0x58
	private static DelegateBridge __Hotfix0_OnPostImport; // 0x60
	private static DelegateBridge __Hotfix0_SetBehaviourPause; // 0x68
	private static DelegateBridge __Hotfix0_FaceTo; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	protected Effect effect { get; set; }
	protected ObjectPtr`1 owner { get; }
	protected SpawnLocation spawnLocation { get; }
	protected Boolean isPaused { get; set; }
	public Boolean isFinished { get; }

	// RVA: 0x1ff4374 VA: 0x759460c374
	protected Effect get_effect() { }
	// RVA: 0x1ff43dc VA: 0x759460c3dc
	private Void set_effect(Effect value) { }
	// RVA: 0x1ff4460 VA: 0x759460c460
	protected ObjectPtr`1 get_owner() { }
	// RVA: 0x1ff44dc VA: 0x759460c4dc
	protected SpawnLocation get_spawnLocation() { }
	// RVA: 0x1ff4558 VA: 0x759460c558
	protected Boolean get_isPaused() { }
	// RVA: 0x1ff45d0 VA: 0x759460c5d0
	protected Void set_isPaused(Boolean value) { }
	// RVA: 0x1ff4660 VA: 0x759460c660
	public Boolean get_isFinished() { }
	// RVA: 0x1ff4730 VA: 0x759460c730
	public virtual Void Init(Effect effect) { }
	// RVA: 0x1ff47b0 VA: 0x759460c7b0
	public virtual Void OnPlay() { }
	// RVA: 0x1ff4814 VA: 0x759460c814
	public virtual Void OnFinish() { }
	// RVA: 0x1ff4878 VA: 0x759460c878
	public virtual Void OnRecycle() { }
	// RVA: 0x1ff48dc VA: 0x759460c8dc
	public virtual Void OnPaused(Boolean paused) { }
	// RVA: 0x1ff4954 VA: 0x759460c954
	public virtual Void OnPostImport() { }
	// RVA: 0x1ff49b8 VA: 0x759460c9b8
	protected Void SetBehaviourPause(Boolean paused) { }
	// RVA: 0x1ff4bd0 VA: 0x759460cbd0
	protected Void FaceTo(Vector3 direction) { }
	// RVA: 0x1ff4c8c VA: 0x759460cc8c
	public Void .ctor() { }
}
```