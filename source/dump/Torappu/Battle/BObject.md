# BObject

**Namespace:** `Torappu.Battle`


## Fields

- `UInt32 <instanceUid>k__BackingField`

- `SideType <side>k__BackingField`

- `PlayerSide <playerSide>k__BackingField`

- `Boolean <inited>k__BackingField`

- `Boolean <borned>k__BackingField`

- `Boolean <isDisappeared>k__BackingField`

- `Int32 m_prdCounter`


## Properties

- `UInt32 instanceUid`

- `SideType side`

- `PlayerSide playerSide`

- `Boolean inited`

- `Boolean borned`

- `Boolean isValid`

- `Boolean validAndBorned`

- `Boolean isDisappeared`


## Methods

- `UInt32 get_instanceUid()`

- `Void set_instanceUid(UInt32)`

- `SideType get_side()`

- `Void set_side(SideType)`

- `PlayerSide get_playerSide()`

- `Void set_playerSide(PlayerSide)`

- `Boolean get_inited()`

- `Void set_inited(Boolean)`

- `Boolean get_borned()`

- `Void set_borned(Boolean)`

- `Boolean get_isValid()`

- `Boolean get_validAndBorned()`

- `Boolean get_isDisappeared()`

- `Void set_isDisappeared(Boolean)`

- `Int32 CompareTo(BObject)`

- `Int32 CompareTo(Object)`

- `Boolean SetDisappeared(Boolean)`

- `Void PreInit(SideType, PlayerSide)`

- `Void Init(SideType, PlayerSide, Vector2, Single)`

- `Void UpdateSideAndLayer(SideType)`

- `Void Reset()`

- `Void DestroyMe()`

- `Void DestroyMe(Single)`

- `PRDEntityHash GetPRDEntityHash(PRDRandomCategory)`

- `Int32 AllocatePRDEntitySubHash(PRDRandomCategory, IPRDRandomEntity)`

- `Void ResetPRDEntity()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BObject : VisualObject, IReusableObject, IReusable, IPtrObject, IComparable`1, IComparable, IPRDRandomEntity
{
	private static UInt32 s_globalCounter; // 0x0
	private UInt32 <instanceUid>k__BackingField; // 0x18
	private SideType <side>k__BackingField; // 0x1c
	private PlayerSide <playerSide>k__BackingField; // 0x20
	private Boolean <inited>k__BackingField; // 0x24
	private Boolean <borned>k__BackingField; // 0x25
	private Boolean <isDisappeared>k__BackingField; // 0x26
	private Int32 m_prdCounter; // 0x28
	private readonly List`1 m_prdSubEntities; // 0x30

	public UInt32 instanceUid { get; set; }
	public SideType side { get; set; }
	public PlayerSide playerSide { get; set; }
	public Boolean inited { get; set; }
	public Boolean borned { get; set; }
	public Boolean isValid { get; }
	public Boolean validAndBorned { get; }
	public Boolean isDisappeared { get; set; }
	public virtual Int32 priority { get; }

	// RVA: 0x3f7321c VA: 0x759658b21c
	public UInt32 get_instanceUid() { }
	// RVA: 0x3f73224 VA: 0x759658b224
	private Void set_instanceUid(UInt32 value) { }
	// RVA: 0x3f7322c VA: 0x759658b22c
	public SideType get_side() { }
	// RVA: 0x3f73234 VA: 0x759658b234
	private Void set_side(SideType value) { }
	// RVA: 0x3f7323c VA: 0x759658b23c
	public PlayerSide get_playerSide() { }
	// RVA: 0x3f73244 VA: 0x759658b244
	private Void set_playerSide(PlayerSide value) { }
	// RVA: 0x3f7324c VA: 0x759658b24c
	public Boolean get_inited() { }
	// RVA: 0x3f73254 VA: 0x759658b254
	private Void set_inited(Boolean value) { }
	// RVA: 0x3f73260 VA: 0x759658b260
	public Boolean get_borned() { }
	// RVA: 0x3f73268 VA: 0x759658b268
	private Void set_borned(Boolean value) { }
	// RVA: 0x3f73274 VA: 0x759658b274
	public Boolean get_isValid() { }
	// RVA: 0x3f73284 VA: 0x759658b284
	public Boolean get_validAndBorned() { }
	// RVA: 0x3f732a4 VA: 0x759658b2a4
	public Boolean get_isDisappeared() { }
	// RVA: 0x3f732ac VA: 0x759658b2ac
	private Void set_isDisappeared(Boolean value) { }
	// RVA: 0x3f732b8 VA: 0x759658b2b8
	public virtual Int32 get_priority() { }
	// RVA: 0x3f732c0 VA: 0x759658b2c0
	public Int32 CompareTo(BObject another) { }
	// RVA: 0x3f733d4 VA: 0x759658b3d4
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x3f73454 VA: 0x759658b454
	protected Void .ctor() { }
	// RVA: 0x3f734dc VA: 0x759658b4dc
	public virtual Void Born() { }
	// RVA: 0x3f73504 VA: 0x759658b504
	public Boolean SetDisappeared(Boolean value) { }
	// RVA: 0x3f7357c VA: 0x759658b57c
	protected Void PreInit(SideType sideType, PlayerSide playerSide) { }
	// RVA: 0x3f73584 VA: 0x759658b584
	protected Void Init(SideType side, PlayerSide playerSide, Vector2 pos, Single height) { }
	// RVA: 0x3f735e0 VA: 0x759658b5e0
	protected Void UpdateSideAndLayer(SideType side) { }
	// RVA: 0x3f736d8 VA: 0x759658b6d8
	protected Void Reset() { }
	// RVA: 0x3f738e4 VA: 0x759658b8e4
	protected Void DestroyMe() { }
	// RVA: 0x3f7393c VA: 0x759658b93c
	protected Void DestroyMe(Single delay) { }
	// RVA: 0x3f739f4 VA: 0x759658b9f4
	public virtual Void OnAllocate() { }
	// RVA: 0x3f73aa4 VA: 0x759658baa4
	public virtual Void OnRecycle() { }
	// RVA: 0x3f73b04 VA: 0x759658bb04
	public virtual Void OnTick(FP deltaTime) { }
	// RVA: 0x3f73b08 VA: 0x759658bb08
	public virtual Void OnLateTick(FP deltaTime) { }
	// RVA: 0x3f73b0c VA: 0x759658bb0c
	protected virtual Void OnReset() { }
	// RVA: 0x3f73b10 VA: 0x759658bb10
	protected virtual Void OnInit(Single initHeight) { }
	// RVA: 0x3f73b14 VA: 0x759658bb14
	protected virtual Void OnPostInit() { }
	// RVA: 0x3f73b18 VA: 0x759658bb18
	protected virtual Void OnBorn() { }
	// RVA: 0x3f73b1c VA: 0x759658bb1c
	protected virtual Void OnBeforeDisappearChanged(Boolean newValue) { }
	// RVA: 0x3f73b20 VA: 0x759658bb20
	protected virtual Void OnDisappearChanged(Boolean newValue) { }
	// RVA: 0x3f73b44 VA: 0x759658bb44
	public PRDEntityHash GetPRDEntityHash(PRDRandomCategory category) { }
	// RVA: 0x3f73b90 VA: 0x759658bb90
	public Int32 AllocatePRDEntitySubHash(PRDRandomCategory category, IPRDRandomEntity child) { }
	// RVA: 0x3f73704 VA: 0x759658b704
	public Void ResetPRDEntity() { }
}
```