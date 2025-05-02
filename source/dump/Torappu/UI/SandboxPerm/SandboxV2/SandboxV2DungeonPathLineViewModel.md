# SandboxV2DungeonPathLineViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String lineId`

- `String concernedId`

- `Vector2 srcPos`

- `Vector2 dstPos`

- `Single delay`

- `Single cycleSpan`

- `Int32 focusDistanceIndex`

- `Single centerMinDistance`

- `Boolean isReversed`

- `PathType pathType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonPathLineViewModel : IHotfixable
{
	public const Single LENGTH_PER_CYCLE; // 0x0
	public String lineId; // 0x10
	public String concernedId; // 0x18
	public Vector2 srcPos; // 0x20
	public Vector2 dstPos; // 0x28
	public Single delay; // 0x30
	public Single cycleSpan; // 0x34
	public Int32 focusDistanceIndex; // 0x38
	public Single centerMinDistance; // 0x3c
	public Boolean isReversed; // 0x40
	public PathType pathType; // 0x44
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x25c29f0 VA: 0x7594bda9f0
	public Void .ctor() { }
}
```