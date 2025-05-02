# MagicCircuitRouteEffect

**Namespace:** ` `


## Fields

- `Effect effect`


## Methods

- `Void UpdateSelf()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class MagicCircuitRouteEffect : IHotfixable
{
	public Effect effect; // 0x10
	private List`1 positions; // 0x18
	private LineRenderer[] m_lineRenderers; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_lineRenderers; // 0x8
	private static DelegateBridge __Hotfix0_UpdateSelf; // 0x10

	protected LineRenderer[] lineRenderers { get; }

	// RVA: 0x400f884 VA: 0x7596627884
	public Void .ctor(String _effectKey, Entity _source, List`1 _positions) { }
	// RVA: 0x400fa10 VA: 0x7596627a10
	protected LineRenderer[] get_lineRenderers() { }
	// RVA: 0x400fac8 VA: 0x7596627ac8
	public Void UpdateSelf() { }
}
```