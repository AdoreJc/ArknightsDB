# EnvSelectorManager

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 _maxTargetNum`

- `FilterType _postFilter`

- `String _entityToStatus`

- `TargetOptions _targetOptions`

- `String _intervalKey`

- `Single _interval`

- `Boolean _characterWithProfessionOnly`

- `PeriodicTimer m_intervalTicker`

- `FP m_interval`


## Methods

- `Void OnGameReady(Object)`

- `Boolean IsCharacter(Unit)`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnvSelectorManager : EnvManager
{
	private Int32 _maxTargetNum; // 0x28
	private FilterType _postFilter; // 0x2c
	private String _entityToStatus; // 0x30
	private TargetOptions _targetOptions; // 0x38
	private EffectSetting[] _cameraEffect; // 0x98
	private String _intervalKey; // 0xa0
	private Single _interval; // 0xa8
	private Boolean _characterWithProfessionOnly; // 0xac
	private PeriodicTimer m_intervalTicker; // 0xb0
	private FP m_interval; // 0xb8
	private List`1 m_candidates; // 0xc0
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0_IsCharacter; // 0x20
	private static DelegateBridge __Hotfix0_SelectTargets; // 0x28
	private static DelegateBridge __Hotfix0_VerifyTarget; // 0x30
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x404ab2c VA: 0x7596662b2c
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x4043570 VA: 0x759665b570
	public override Void Init(GlobalEnvSystem system) { }
	// RVA: 0x404ac94 VA: 0x7596662c94
	public Void OnGameReady(Object arg) { }
	// RVA: 0x40438dc VA: 0x759665b8dc
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x404ae54 VA: 0x7596662e54
	private Boolean IsCharacter(Unit unit) { }
	// RVA: 0x4044570 VA: 0x759665c570
	protected virtual Void SelectTargets(List`1 candidates) { }
	// RVA: 0x4044054 VA: 0x759665c054
	protected virtual Boolean VerifyTarget(Entity entity) { }
	// RVA: 0x404af8c VA: 0x7596662f8c
	protected virtual Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x404444c VA: 0x759665c44c
	public Void .ctor() { }
	// RVA: 0x404b040 VA: 0x7596663040
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
	// RVA: 0x404b048 VA: 0x7596663048
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x404b050 VA: 0x7596663050
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```