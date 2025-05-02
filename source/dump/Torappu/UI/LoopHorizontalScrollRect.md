# LoopHorizontalScrollRect

**Namespace:** `Torappu.UI`


## Fields

- `Int32 _preloadMultiplier`

- `RectTransform _viewBoundImage`

- `RectTransform _contentBoundImage`

- `Boolean m_horizontal`

- `Boolean m_vertical`


## Methods

- `Single _WrapOptionWithPreload(Func`1)`

- `Void <>xLuaBaseProxy_Awake()`

- `Boolean <>xLuaBaseProxy_UpdateItems(Bounds, Bounds)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class LoopHorizontalScrollRect : LoopScrollRect
{
	private Int32 _preloadMultiplier; // 0x194
	public RectTransform _viewBoundImage; // 0x198
	public RectTransform _contentBoundImage; // 0x1a0
	private Boolean m_horizontal; // 0x1a8
	private Boolean m_vertical; // 0x1a9
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
	private static DelegateBridge __Hotfix0__WrapOptionWithPreload; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	protected override Boolean defaultHorizontal { get; }
	public override Boolean horizontal { get; set; }
	protected override Boolean defaultVertical { get; }
	public override Boolean vertical { get; set; }

	// RVA: 0x2226dd8 VA: 0x759483edd8
	protected override Boolean get_defaultHorizontal() { }
	// RVA: 0x2226e40 VA: 0x759483ee40
	public override Boolean get_horizontal() { }
	// RVA: 0x2226ea8 VA: 0x759483eea8
	public override Void set_horizontal(Boolean value) { }
	// RVA: 0x2226f28 VA: 0x759483ef28
	protected override Boolean get_defaultVertical() { }
	// RVA: 0x2226f8c VA: 0x759483ef8c
	public override Boolean get_vertical() { }
	// RVA: 0x2226ff4 VA: 0x759483eff4
	public override Void set_vertical(Boolean value) { }
	// RVA: 0x2227074 VA: 0x759483f074
	protected override Single GetSize(RectTransform item) { }
	// RVA: 0x2227440 VA: 0x759483f440
	protected override Single GetDimension(Vector2 vector) { }
	// RVA: 0x22274c4 VA: 0x759483f4c4
	protected override Vector2 GetVector(Single value) { }
	// RVA: 0x222753c VA: 0x759483f53c
	protected override Void Awake() { }
	// RVA: 0x22275b4 VA: 0x759483f5b4
	protected override Boolean UpdateItems(Bounds viewBounds, Bounds contentBounds) { }
	// RVA: 0x2227e38 VA: 0x759483fe38
	private Single _WrapOptionWithPreload(Func`1 singleAction) { }
	// RVA: 0x222800c VA: 0x759484000c
	public Void .ctor() { }
	// RVA: 0x2228218 VA: 0x7594840218
	private Void <>xLuaBaseProxy_Awake() { }
	// RVA: 0x2228220 VA: 0x7594840220
	private Boolean <>xLuaBaseProxy_UpdateItems(Bounds P0, Bounds P1) { }
}
```