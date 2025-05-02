# HandBookV2MapForceShadowView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Color _shadowColor`

- `HandBookV2AlphaHexagonView _shadowTemplate`

- `Transform _container`


## Methods

- `Void _RenderDot(HandBookV2PointData)`

- `Void Render(HandBookV2ForceViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2MapForceShadowView : MonoBehaviour, IHotfixable
{
	private Color _shadowColor; // 0x18
	private readonly Vector2 SHADOW_OFFSET; // 0x28
	private HandBookV2AlphaHexagonView _shadowTemplate; // 0x30
	private Transform _container; // 0x38
	private Dictionary`2 m_pointIndex2ShadowGoMap; // 0x40
	private static DelegateBridge __Hotfix0__RenderDot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2ed22f0 VA: 0x75954ea2f0
	private Void _RenderDot(HandBookV2PointData pointData) { }
	// RVA: 0x2ed2468 VA: 0x75954ea468
	public Void Render(HandBookV2ForceViewModel viewModel) { }
	// RVA: 0x2ed2564 VA: 0x75954ea564
	public Void .ctor() { }
}
```