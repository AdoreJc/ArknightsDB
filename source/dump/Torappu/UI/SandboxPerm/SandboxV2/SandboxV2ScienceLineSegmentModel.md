# SandboxV2ScienceLineSegmentModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String fromNodeId`

- `SandboxV2DevelopmentLineSegmentData segmentData`

- `Vector2 fromNodePos`

- `Vector2 toNodePos`

- `Boolean isSegmentUnlock`


## Properties

- `Boolean isPublic`


## Methods

- `Boolean get_isPublic()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ScienceLineSegmentModel : IHotfixable
{
	public String fromNodeId; // 0x10
	public SandboxV2DevelopmentLineSegmentData segmentData; // 0x18
	public Vector2 fromNodePos; // 0x20
	public Vector2 toNodePos; // 0x28
	public Boolean isSegmentUnlock; // 0x30
	private static DelegateBridge __Hotfix0_get_isPublic; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8

	public Boolean isPublic { get; }

	// RVA: 0x24e5fd8 VA: 0x7594afdfd8
	public Boolean get_isPublic() { }
	// RVA: 0x24e457c VA: 0x7594afc57c
	public Void .ctor() { }
}
```