# SandboxV2EnemyRushLineView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Single _lineWidth`

- `CanvasGroup _showHandler`

- `UIAnimationLocation _enterAnim`

- `Sprite _spriteEnemyRush`

- `Sprite _spriteMessenger`

- `Boolean m_inited`

- `SandboxV2EnterAnimTween m_enterAnimTween`

- `FadeSwitchTween m_showTween`

- `String m_cachedEnemyRushId`

- `String m_cachedLineId`

- `Vector2 m_cachedSrcPos`

- `Vector2 m_cachedDstPos`

- `Single m_cachedCycleSpan`

- `Boolean m_cachedSelected`

- `Boolean m_asyncShown`

- `SeqNumChecker m_dungeonChangeChecker`

- `SeqNumChecker m_enemyRushSelectionChecker`

- `SeqNumChecker m_enterAnimChecker`


## Methods

- `Void _InitIfNot()`

- `Void _OnRecycle()`

- `Void _RefreshShowStatus(Boolean)`

- `Void AsyncSetData(RenderParam)`

- `Void _LineTo(Vector2, Vector2)`

- `Void AsyncShow()`

- `Boolean <>xLuaBaseProxy_get_packIntoRuntimeAtlas()`

- `Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2EnemyRushLineView : Image, IAsyncDataView`1, IAsyncShowEffect, IHotfixable
{
	private Single _lineWidth; // 0x188
	private CanvasGroup _showHandler; // 0x190
	private UIAnimationLocation _enterAnim; // 0x198
	private Sprite _spriteEnemyRush; // 0x1a8
	private Sprite _spriteMessenger; // 0x1b0
	private Boolean m_inited; // 0x1b8
	private SandboxV2EnterAnimTween m_enterAnimTween; // 0x1c0
	private FadeSwitchTween m_showTween; // 0x1c8
	private String m_cachedEnemyRushId; // 0x1d0
	private String m_cachedLineId; // 0x1d8
	private Vector2 m_cachedSrcPos; // 0x1e0
	private Vector2 m_cachedDstPos; // 0x1e8
	private Single m_cachedCycleSpan; // 0x1f0
	private Boolean m_cachedSelected; // 0x1f4
	private Boolean m_asyncShown; // 0x1f5
	private SeqNumChecker m_dungeonChangeChecker; // 0x1f8
	private SeqNumChecker m_enemyRushSelectionChecker; // 0x208
	private SeqNumChecker m_enterAnimChecker; // 0x218
	private static DelegateBridge __Hotfix0_get_packIntoRuntimeAtlas; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__OnRecycle; // 0x10
	private static DelegateBridge __Hotfix0__RefreshShowStatus; // 0x18
	private static DelegateBridge __Hotfix0_AsyncSetData; // 0x20
	private static DelegateBridge __Hotfix0__LineTo; // 0x28
	private static DelegateBridge __Hotfix0_OnPopulateMesh; // 0x30
	private static DelegateBridge __Hotfix0_AsyncShow; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override Boolean packIntoRuntimeAtlas { get; }

	// RVA: 0x2564364 VA: 0x7594b7c364
	public override Boolean get_packIntoRuntimeAtlas() { }
	// RVA: 0x25643c8 VA: 0x7594b7c3c8
	private Void _InitIfNot() { }
	// RVA: 0x2564518 VA: 0x7594b7c518
	private Void _OnRecycle() { }
	// RVA: 0x25645b0 VA: 0x7594b7c5b0
	private Void _RefreshShowStatus(Boolean useTween) { }
	// RVA: 0x2564670 VA: 0x7594b7c670
	public Void AsyncSetData(RenderParam param) { }
	// RVA: 0x2564a78 VA: 0x7594b7ca78
	private Void _LineTo(Vector2 srcPos, Vector2 dstPos) { }
	// RVA: 0x2564c6c VA: 0x7594b7cc6c
	protected override Void OnPopulateMesh(VertexHelper vh) { }
	// RVA: 0x2565ae4 VA: 0x7594b7dae4
	public Void AsyncShow() { }
	// RVA: 0x2565b50 VA: 0x7594b7db50
	public Void .ctor() { }
	// RVA: 0x2565c5c VA: 0x7594b7dc5c
	private Boolean <>xLuaBaseProxy_get_packIntoRuntimeAtlas() { }
	// RVA: 0x2565c64 VA: 0x7594b7dc64
	private Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper P0) { }
}
```