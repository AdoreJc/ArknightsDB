# GridRangeDrawer

**Namespace:** `Torappu.Battle`


## Fields

- `Material _rangeMaterial`

- `Color _attackRangeColor`

- `Color _healRangeColor`

- `Color _skillRangeColor`

- `Color _locateRangeColor`

- `Color _overlapRangeColor`

- `MeshFilter m_meshFilter`

- `MeshRenderer m_meshRenderer`

- `EasyMeshGenerator m_generator`

- `Material m_rangeMaterial`

- `Boolean m_hasGiantBoss`

- `IDrawableRange m_giantBossLocateRnage`


## Properties

- `Boolean isEnabled`


## Methods

- `Boolean get_isEnabled()`

- `Void set_isEnabled(Boolean)`

- `Mesh _CreateMesh(IList`1)`

- `Mesh _CreateMeshAllDirection(IList`1, GridPosition)`

- `Void OnGameReset(BattleController)`

- `Void OnGameInit(Options)`

- `Void OnGameReady()`

- `Void OnGameStart()`

- `Void OnGameOver(GameResult)`

- `Void TurnOn(IList`1)`

- `Void TurnOn(UnorderedArray`1)`

- `Void RecordGiantBossLocateRange(IDrawableRange)`

- `Void ResetGiantBossLocateRange()`

- `Material _InitRangeMaterialIfNot()`

- `Void Awake()`

- `Void Update()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class GridRangeDrawer : MonoBehaviour, IBattleModule, IHotfixable
{
	private const String SHADER_UNSCALED_TIME_PROPERTY; // 0x0
	private readonly Color DISABLED_RANGED_COLOR; // 0x18
	private Material _rangeMaterial; // 0x28
	public Color _attackRangeColor; // 0x30
	public Color _healRangeColor; // 0x40
	public Color _skillRangeColor; // 0x50
	public Color _locateRangeColor; // 0x60
	public Color _overlapRangeColor; // 0x70
	protected MeshFilter m_meshFilter; // 0x80
	protected MeshRenderer m_meshRenderer; // 0x88
	protected List`1 m_ranges; // 0x90
	private HashSet`1 m_grids; // 0x98
	protected EasyMeshGenerator m_generator; // 0xa0
	protected Material m_rangeMaterial; // 0xa8
	protected Boolean m_hasGiantBoss; // 0xb0
	protected IDrawableRange m_giantBossLocateRnage; // 0xb8
	private static DelegateBridge __Hotfix0_get_isEnabled; // 0x0
	private static DelegateBridge __Hotfix0_set_isEnabled; // 0x8
	private static DelegateBridge __Hotfix0__CreateMesh; // 0x10
	private static DelegateBridge __Hotfix0__CreateMeshAllDirection; // 0x18
	private static DelegateBridge __Hotfix0_OnGameReset; // 0x20
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x28
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x30
	private static DelegateBridge __Hotfix0_OnGameStart; // 0x38
	private static DelegateBridge __Hotfix0_OnGameOver; // 0x40
	private static DelegateBridge __Hotfix0_TurnOn; // 0x48
	private static DelegateBridge __Hotfix0_TurnOnSkill; // 0x50
	private static DelegateBridge __Hotfix1_TurnOn; // 0x58
	private static DelegateBridge __Hotfix2_TurnOn; // 0x60
	private static DelegateBridge __Hotfix0_TurnOff; // 0x68
	private static DelegateBridge __Hotfix0_RecordGiantBossLocateRange; // 0x70
	private static DelegateBridge __Hotfix0_ResetGiantBossLocateRange; // 0x78
	private static DelegateBridge __Hotfix0__TurnOnInternal; // 0x80
	private static DelegateBridge __Hotfix0__TurnOffInternal; // 0x88
	private static DelegateBridge __Hotfix0__InitRangeMaterialIfNot; // 0x90
	private static DelegateBridge __Hotfix0_Awake; // 0x98
	private static DelegateBridge __Hotfix0_Update; // 0xa0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public Boolean isEnabled { get; set; }

	// RVA: 0x1c4ee24 VA: 0x7594266e24
	public Boolean get_isEnabled() { }
	// RVA: 0x1c4eea0 VA: 0x7594266ea0
	protected Void set_isEnabled(Boolean value) { }
	// RVA: 0x1c4ef90 VA: 0x7594266f90
	private Mesh _CreateMesh(IList`1 ranges) { }
	// RVA: 0x1c4f52c VA: 0x759426752c
	private Mesh _CreateMeshAllDirection(IList`1 ranges, GridPosition origin) { }
	// RVA: 0x1c4fb24 VA: 0x7594267b24
	public Void OnGameReset(BattleController controller) { }
	// RVA: 0x1c4fba8 VA: 0x7594267ba8
	public Void OnGameInit(Options levelOptions) { }
	// RVA: 0x1c4fc20 VA: 0x7594267c20
	public Void OnGameReady() { }
	// RVA: 0x1c4fc84 VA: 0x7594267c84
	public Void OnGameStart() { }
	// RVA: 0x1c4fce8 VA: 0x7594267ce8
	public Void OnGameOver(GameResult result) { }
	// RVA: 0x VA: 0x0
	public virtual Void TurnOn(T unit) { }
	// RVA: 0x VA: 0x0
	public virtual Void TurnOnSkill(T unit) { }
	// RVA: 0x VA: 0x0
	public Void TurnOn(IList`1 units) { }
	// RVA: 0x VA: 0x0
	public Void TurnOn(UnorderedArray`1 units) { }
	// RVA: 0x1c4fd60 VA: 0x7594267d60
	public virtual Void TurnOff() { }
	// RVA: 0x1c4fde0 VA: 0x7594267de0
	public Void RecordGiantBossLocateRange(IDrawableRange range) { }
	// RVA: 0x1c4fe6c VA: 0x7594267e6c
	public Void ResetGiantBossLocateRange() { }
	// RVA: 0x1c4fee0 VA: 0x7594267ee0
	protected virtual Void _TurnOnInternal(IList`1 ranges, Material material) { }
	// RVA: 0x1c4ffd4 VA: 0x7594267fd4
	protected virtual Void _TurnOffInternal() { }
	// RVA: 0x1c50038 VA: 0x7594268038
	protected Material _InitRangeMaterialIfNot() { }
	// RVA: 0x1c50128 VA: 0x7594268128
	private Void Awake() { }
	// RVA: 0x1c501f0 VA: 0x75942681f0
	private Void Update() { }
	// RVA: 0x1c502d0 VA: 0x75942682d0
	private Void OnDestroy() { }
	// RVA: 0x1c503f8 VA: 0x75942683f8
	public Void .ctor() { }
}
```