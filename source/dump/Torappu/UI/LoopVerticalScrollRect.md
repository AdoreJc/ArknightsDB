# LoopVerticalScrollRect

**Namespace:** `Torappu.UI`


## Fields

- `Boolean m_horizontal`

- `Boolean m_vertical`


## Methods

- `Void <>xLuaBaseProxy_Awake()`

- `Boolean <>xLuaBaseProxy_UpdateItems(Bounds, Bounds)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class LoopVerticalScrollRect : LoopScrollRect
{
	private Boolean m_horizontal; // 0x191
	private Boolean m_vertical; // 0x192
	private static DelegateBridge __Hotfix0_get_defaultHorizontal; // 0x0
	private static DelegateBridge __Hotfix0_get_horizontal; // 0x8
	private static DelegateBridge __Hotfix0_set_horizontal; // 0x10
	private static DelegateBridge __Hotfix0_get_defaultVertical; // 0x18
	private static DelegateBridge __Hotfix0_get_vertical; // 0x20
	private static DelegateBridge __Hotfix0_set_vertical; // 0x28
	private static DelegateBridge __Hotfix0_GetSize; // 0x30
	private static DelegateBridge __Hotfix0_GetDimension; // 0x38
	private static DelegateBridge __Hotfix0_GetVector; // 0x40
	private static DelegateBridge __Hotfix0_Awake; // 0x48
	private static DelegateBridge __Hotfix0_UpdateItems; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	protected override Boolean defaultHorizontal { get; }
	public override Boolean horizontal { get; set; }
	protected override Boolean defaultVertical { get; }
	public override Boolean vertical { get; set; }

	// RVA: 0x2232f90 VA: 0x759484af90
	protected override Boolean get_defaultHorizontal() { }
	// RVA: 0x2232ff4 VA: 0x759484aff4
	public override Boolean get_horizontal() { }
	// RVA: 0x223305c VA: 0x759484b05c
	public override Void set_horizontal(Boolean value) { }
	// RVA: 0x22330dc VA: 0x759484b0dc
	protected override Boolean get_defaultVertical() { }
	// RVA: 0x2233144 VA: 0x759484b144
	public override Boolean get_vertical() { }
	// RVA: 0x22331ac VA: 0x759484b1ac
	public override Void set_vertical(Boolean value) { }
	// RVA: 0x223322c VA: 0x759484b22c
	protected override Single GetSize(RectTransform item) { }
	// RVA: 0x2233338 VA: 0x759484b338
	protected override Single GetDimension(Vector2 vector) { }
	// RVA: 0x22333bc VA: 0x759484b3bc
	protected override Vector2 GetVector(Single value) { }
	// RVA: 0x2233438 VA: 0x759484b438
	protected override Void Awake() { }
	// RVA: 0x22334b0 VA: 0x759484b4b0
	protected override Boolean UpdateItems(Bounds viewBounds, Bounds contentBounds) { }
	// RVA: 0x2233834 VA: 0x759484b834
	public Void .ctor() { }
	// RVA: 0x22338ac VA: 0x759484b8ac
	private Void <>xLuaBaseProxy_Awake() { }
	// RVA: 0x22338b4 VA: 0x759484b8b4
	private Boolean <>xLuaBaseProxy_UpdateItems(Bounds P0, Bounds P1) { }
}
```