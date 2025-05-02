# Thorn2S3Renderer

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `String _mainEffect`

- `Boolean _useEndPointAsStartPos`

- `Boolean m_isProjectileReached`

- `Boolean m_isRenderering`

- `Thorn2PolygonRange m_range`

- `Boolean m_isLoop`


## Methods

- `Void _SetLineRenderer()`

- `Void GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnProjectileStop()`

- `Void <>xLuaBaseProxy_OnProjectileReached()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class Thorn2S3Renderer : Behaviour, IEffectSource
{
	private String _mainEffect; // 0x28
	private Boolean _useEndPointAsStartPos; // 0x30
	private ObjectPtr`1 m_mainEffect; // 0x38
	private LineRenderer[] m_lineRenderers; // 0x48
	private Boolean m_isProjectileReached; // 0x50
	private Boolean m_isRenderering; // 0x51
	private Vector3[] m_positions; // 0x58
	private Thorn2PolygonRange m_range; // 0x60
	private Boolean m_isLoop; // 0x68
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x8
	private static DelegateBridge __Hotfix0_OnProjectileReached; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0__SetLineRenderer; // 0x20
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1d78b70 VA: 0x7594390b70
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d78ee0 VA: 0x7594390ee0
	public override Void OnProjectileStop() { }
	// RVA: 0x1d78fe4 VA: 0x7594390fe4
	public override Void OnProjectileReached() { }
	// RVA: 0x1d79400 VA: 0x7594391400
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d79074 VA: 0x7594391074
	private Void _SetLineRenderer() { }
	// RVA: 0x1d794b4 VA: 0x75943914b4
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1d795c8 VA: 0x75943915c8
	public Void .ctor() { }
	// RVA: 0x1d796a4 VA: 0x75943916a4
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d796ac VA: 0x75943916ac
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
	// RVA: 0x1d796b4 VA: 0x75943916b4
	private Void <>xLuaBaseProxy_OnProjectileReached() { }
	// RVA: 0x1d796bc VA: 0x75943916bc
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```