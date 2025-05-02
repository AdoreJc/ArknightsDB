# FifthAnnivExploreMapNodeViewModel

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `Int32 indexInRoute`

- `Vector2 pos`

- `FifthAnnivNodeType nodeType`

- `FifthAnnivRouteType routeType`


## Methods

- `Boolean IsCurrentNode(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreMapNodeViewModel : IHotfixable
{
	public Int32 indexInRoute; // 0x10
	public Vector2 pos; // 0x14
	public FifthAnnivNodeType nodeType; // 0x1c
	public FifthAnnivRouteType routeType; // 0x20
	private static DelegateBridge __Hotfix0_IsCurrentNode; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x29253b0 VA: 0x7594f3d3b0
	public Boolean IsCurrentNode(Int32 currentIndex) { }
	// RVA: 0x2926354 VA: 0x7594f3e354
	public Void .ctor() { }
}
```