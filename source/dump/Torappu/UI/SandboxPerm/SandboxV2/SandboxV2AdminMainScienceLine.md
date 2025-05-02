# SandboxV2AdminMainScienceLine

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Vector2 _startPos`

- `Vector2 _endPos`

- `Int32 _width`


## Methods

- `Void SetPosition(Vector2, Vector2)`

- `Void _DrawLine(VertexHelper, Vector2, Vector2)`

- `Void Update()`

- `Boolean <>xLuaBaseProxy_get_packIntoRuntimeAtlas()`

- `Void <>xLuaBaseProxy_SetClipRect(Rect, Boolean)`

- `Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainScienceLine : Image, IHotfixable
{
	private Vector2 _startPos; // 0x188
	private Vector2 _endPos; // 0x190
	private Int32 _width; // 0x198
	private UIVertex[] m_vertexArray; // 0x1a0
	private static DelegateBridge __Hotfix0_get_packIntoRuntimeAtlas; // 0x0
	private static DelegateBridge __Hotfix0_SetPosition; // 0x8
	private static DelegateBridge __Hotfix0_SetClipRect; // 0x10
	private static DelegateBridge __Hotfix0_OnPopulateMesh; // 0x18
	private static DelegateBridge __Hotfix0__DrawLine; // 0x20
	private static DelegateBridge __Hotfix0_Update; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override Boolean packIntoRuntimeAtlas { get; }

	// RVA: 0x24de0e0 VA: 0x7594af60e0
	public override Boolean get_packIntoRuntimeAtlas() { }
	// RVA: 0x24de144 VA: 0x7594af6144
	public Void SetPosition(Vector2 startPos, Vector2 endPos) { }
	// RVA: 0x24de264 VA: 0x7594af6264
	public override Void SetClipRect(Rect clipRect, Boolean validRect) { }
	// RVA: 0x24de33c VA: 0x7594af633c
	protected override Void OnPopulateMesh(VertexHelper vh) { }
	// RVA: 0x24de46c VA: 0x7594af646c
	private Void _DrawLine(VertexHelper vh, Vector2 startPos, Vector2 endPos) { }
	// RVA: 0x24df538 VA: 0x7594af7538
	public Void Update() { }
	// RVA: 0x24df59c VA: 0x7594af759c
	public Void .ctor() { }
	// RVA: 0x24df66c VA: 0x7594af766c
	private Boolean <>xLuaBaseProxy_get_packIntoRuntimeAtlas() { }
	// RVA: 0x24df674 VA: 0x7594af7674
	private Void <>xLuaBaseProxy_SetClipRect(Rect P0, Boolean P1) { }
	// RVA: 0x24df680 VA: 0x7594af7680
	private Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper P0) { }
}
```