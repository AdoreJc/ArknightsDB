# PreviewCursor

**Namespace:** `Torappu.Battle`


## Fields

- `Single _height`

- `Single _moveSpeed`

- `Boolean _faceToDirection`

- `Int32 _times`

- `Transform _bodyTransform`

- `Single _delayToRecycle`

- `Transform _defaultEffect`

- `Action m_onFinishOnce`

- `DirectionCursor m_cursor`

- `Int32 m_remainingTime`

- `Boolean m_reached`

- `Vector2 m_direction`

- `MotionMode <pathMotionMode>k__BackingField`


## Properties

- `Single moveSpeed`

- `MotionMode pathMotionMode`

- `Vector2 footMapPosition`

- `Vector2 offsetMapPosition`

- `Boolean canMove`

- `DirectionCursor cursor`


## Methods

- `Single get_moveSpeed()`

- `MotionMode get_pathMotionMode()`

- `Void set_pathMotionMode(MotionMode)`

- `Vector2 get_footMapPosition()`

- `Vector2 get_offsetMapPosition()`

- `Boolean get_canMove()`

- `DirectionCursor get_cursor()`

- `Void Spawn(Route, SchedulerSnapshot, Action, String)`

- `Void _TryCreateOverrideEffect(String)`

- `Void _TryClearOverrideEffect()`

- `Void _Reborn()`

- `Void _FaceTo(Vector2)`

- `Void _UpdateMovement(Single)`

- `Void _UpdateHeight()`

- `Void _ClearTrails()`

- `Void _OnFinish()`

- `Void _CollectTrails()`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class PreviewCursor : BObject, IMovable, ILocatable
{
	private Single _height; // 0x38
	private Single _moveSpeed; // 0x3c
	private Boolean _faceToDirection; // 0x40
	private Int32 _times; // 0x44
	private Transform _bodyTransform; // 0x48
	private Single _delayToRecycle; // 0x50
	private Transform _defaultEffect; // 0x58
	private Action m_onFinishOnce; // 0x60
	private DirectionCursor m_cursor; // 0x68
	private Int32 m_remainingTime; // 0x70
	private Boolean m_reached; // 0x74
	private Vector2 m_direction; // 0x78
	private TrailRenderer[] m_trails; // 0x80
	private ObjectPtr`1 m_effect; // 0x88
	private MotionMode <pathMotionMode>k__BackingField; // 0x98

	public Single moveSpeed { get; }
	public MotionMode pathMotionMode { get; set; }
	public Vector2 footMapPosition { get; }
	public Vector2 offsetMapPosition { get; }
	public Boolean canMove { get; }
	public DirectionCursor cursor { get; }

	// RVA: 0x1c52274 VA: 0x759426a274
	public Single get_moveSpeed() { }
	// RVA: 0x1c5227c VA: 0x759426a27c
	public MotionMode get_pathMotionMode() { }
	// RVA: 0x1c52284 VA: 0x759426a284
	private Void set_pathMotionMode(MotionMode value) { }
	// RVA: 0x1c5228c VA: 0x759426a28c
	public Vector2 get_footMapPosition() { }
	// RVA: 0x1c52294 VA: 0x759426a294
	public Vector2 get_offsetMapPosition() { }
	// RVA: 0x1c5229c VA: 0x759426a29c
	public Boolean get_canMove() { }
	// RVA: 0x1c522a4 VA: 0x759426a2a4
	public DirectionCursor get_cursor() { }
	// RVA: 0x1c522ac VA: 0x759426a2ac
	public Void Spawn(Route route, SchedulerSnapshot snapshot, Action onFinish, String overrideEffect) { }
	// RVA: 0x1c52584 VA: 0x759426a584
	public override Void OnTick(FP fixedDeltaTime) { }
	// RVA: 0x1c529c0 VA: 0x759426a9c0
	public override Void OnRecycle() { }
	// RVA: 0x1c52a24 VA: 0x759426aa24
	protected override Void OnReset() { }
	// RVA: 0x1c52a94 VA: 0x759426aa94
	protected override Void OnDisappearChanged(Boolean newValue) { }
	// RVA: 0x1c52c4c VA: 0x759426ac4c
	protected override Void OnBorn() { }
	// RVA: 0x1c52438 VA: 0x759426a438
	private Void _TryCreateOverrideEffect(String effect) { }
	// RVA: 0x1c52cc0 VA: 0x759426acc0
	private Void _TryClearOverrideEffect() { }
	// RVA: 0x1c52dec VA: 0x759426adec
	private Void _Reborn() { }
	// RVA: 0x1c52ec8 VA: 0x759426aec8
	private Void _FaceTo(Vector2 direction) { }
	// RVA: 0x1c526f4 VA: 0x759426a6f4
	private Void _UpdateMovement(Single deltaTime) { }
	// RVA: 0x1c52ad8 VA: 0x759426aad8
	private Void _UpdateHeight() { }
	// RVA: 0x1c52bec VA: 0x759426abec
	private Void _ClearTrails() { }
	// RVA: 0x1c529dc VA: 0x759426a9dc
	private Void _OnFinish() { }
	// RVA: 0x1c52c68 VA: 0x759426ac68
	private Void _CollectTrails() { }
	// RVA: 0x1c52f3c VA: 0x759426af3c
	private Void Awake() { }
	// RVA: 0x1c52fd0 VA: 0x759426afd0
	public Void .ctor() { }
}
```